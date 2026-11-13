# Business Account 设计稿版本管理

本规则管理可点击设计稿。`vN` 不等于 App、API 或生产功能版本；GitHub 提交和 Sites 发布回执分别保留。

## 团队查看

- `prototype.html` 顶部显示当前版本；点击“版本记录”查看各版变化、影响范围、验证、待办、历史提交及上一版对比。
- `versions.html` 是独立可分享的中英葡版本记录页。
- `CHANGELOG.md` 是可复制到会议记录／Confluence 的三语更新清单。
- `versions.json` 是版本说明的唯一数据源；上述页面从它生成。
- v40–v47 根据已有提交补录，更早记录保留原始提交标题。没有历史验证证据的版本标为“未补录”，不推断验收完成。

## 每次改动的登记字段

| 字段 | 要求 |
|---|---|
| version | 当前版本 + 1；不重用旧版本 |
| date | 发布日期，YYYY-MM-DD，Asia/Shanghai |
| title | 本次改动主题，中／英／葡 |
| impact | 影响页面和场景，中／英／葡 |
| changes | 本次相对上一版本发生了什么，中／英／葡逐项对应 |
| validation | 实际执行及结果；未验收、失败或受阻必须写明 |
| pending | 仍需谁确认什么；无待办可写“无新增待办” |
| commit | 可核实的历史 GitHub SHA；当前版本提交尚未产生时为 null |
| sourceSha256 | 工具按源代码自动计算；无需人工填写 |

## 操作顺序

1. 完成本次交互修改，将已产生的当前版提交 SHA 补到即将成为历史版的记录中；不要修改历史改动说明。未取得证据的字段保留未确认。
2. 创建一个新版本条目的 JSON，包含上述三语字段。运行下列命令，登记新版本；旧条目会保留：

```powershell
node scripts/release-tools.cjs add versions.json source/ba-business-clean-runtime.js new-release.json source/design.html
```

3. 使用现有交互稿同步与导出流程嵌入新登记数据，再生成记录页：

```powershell
node scripts/build-versions.cjs versions.json source/ba-business-clean-runtime.js .
```

4. 检查普通会话、首次联系和测试场景受影响的交互，以及中英葡文案；执行相关回归检查。验证结果写入该条目的 validation。缺少浏览器视觉验收时不得写“全部验收通过”。
5. 将交互稿、版本页、更新清单和登记数据一起提交；同步 Sites 与 GitHub Pages。等部署完成后读回线上文件，确认版本和文件一致。
6. 下一版登记前，用实际提交 SHA 完成当前版的历史快照链接；历史版本通过 GitHub 提交和 compare 查看，不直接回退线上站点。

### 当前工作区命令

```powershell
node output/release-tools.cjs add output/prototype-versions.json output/ba-business-clean-runtime.js output/new-release.json "C:/Users/johns/.codex/visualizations/2026/10/26/01a177d2-2bb7-7fb0-9949-ed3ac13ca5a5/phizchat-business-interactions.html"
node output/sync-business-runtime.cjs
node output/build-versions.cjs
```

运行代码或界面结构／样式变动后如未登记新版本，同步与打包校验会报错；重复或逆序版本号、缺少任一语言、空变更清单也会被拒绝。更新源代码后，不通过手改 sourceSha256 或 designSha256 绕过登记。

仓库的 `source` 和 `scripts` 用于追溯与版本校验；完整交互稿仍按已有同步、导出及发布流程生成。脚本不自动发布、不更改分享权限、不发送团队消息。

## 新条目示例

```json
{
  "version": 49,
  "date": "2026-11-14",
  "title": {"zh":"调整主题","en":"Updated topic","pt":"Tema atualizado"},
  "impact": {"zh":"受影响场景","en":"Affected scenes","pt":"Cenários afetados"},
  "changes": [{"zh":"具体变化","en":"Concrete change","pt":"Alteração específica"}],
  "validation": {"zh":"实际检查结果","en":"Actual check results","pt":"Resultados reais"},
  "pending": {"zh":"待确认事项","en":"Pending decisions","pt":"Decisões pendentes"},
  "commit": null
}
```
