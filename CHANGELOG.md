# Business Account · 版本更新记录 / Changelog / Histórico

当前设计版本 / Current design / Design atual: **v48**

vN 是设计版本，不代表 App 或 API 发布。发布日期按北京时间；历史验证未留存时明确标记。

## v48 · 2026-11-13 · 增加团队版本管理

### 中文

增加团队版本管理

设计稿顶部、版本记录、更新清单与发布流程

- 新增当前版本入口；可展开每版改动、影响范围、验证与待办。
- 以统一登记文件生成界面和更新清单，补录 v40–v47；更早提交作为原始记录归档。

版本数据／构建一致性及交互回归检查；浏览器视觉验收未完成。

待确认：认证字段／列表一致性、文件白名单与大小、通讯录接口复用、Will 分享卡片与短链、冠创团队举报枚举、安全服务说明。

### English

Team version management

Prototype header, history, changelog and release process

- Add a current-version entry with changes, impact, validation and pending work per release.
- Generate the interface and changelog from one registry; backfill v40–v47 and retain earlier commits as raw history.

Version data/build consistency and interaction regression checks; browser visual review incomplete.

Pending: badge field/list consistency, file types and sizes, Contacts API reuse, Will sharing card/shortlink, report taxonomy and security wording.

### Português (BR)

Gestão de versões para a equipe

Cabeçalho, histórico, registro de alterações e publicação

- Adicionar acesso à versão atual com alterações, impacto, validação e pendências.
- Gerar interface e registro a partir de um cadastro único; recuperar v40–v47 e preservar commits anteriores.

Verificações de dados/build e regressão; revisão visual no navegador incompleta.

Pendências: selo e consistência na lista, tipos/tamanhos de arquivos, API de contatos, cartão de compartilhamento/link curto de Will, denúncias e texto de segurança.

## v47 · 2026-11-13 · 输入区对齐截图并复核会议清单

### 中文

输入区对齐截图并复核会议清单

普通会话、首次联系、测试场景、11/13 清单

- 统一加号、表情、拍照、语音／发送切换；五项附件改为底部网格。
- 修正测试场景选择附件即发送；改为选好后点击发送，并新增逐项复核清单。

本地交互检查通过；浏览器视觉验收未完成。

待确认：认证字段／列表一致性、文件白名单与大小、通讯录接口复用、Will 分享卡片与短链、冠创团队举报枚举、安全服务说明。

### English

Composer alignment and meeting recheck

Regular chat, first contact, test cases and Nov 13 checklist

- Unify plus, emoji, camera and mic/send toggle; use a five-item bottom attachment grid.
- Fix immediate sending on attachment selection in test cases; require Send and add an itemized recheck.

Local interaction checks passed; browser visual review incomplete.

Pending: badge field/list consistency, file types and sizes, Contacts API reuse, Will sharing card/shortlink, report taxonomy and security wording.

### Português (BR)

Ajuste do campo de mensagem e revisão da reunião

Conversa, primeiro contato, cenários de teste e lista de 13/11

- Unificar adicionar, emoji, câmera e alternância microfone/enviar; grade inferior com cinco anexos.
- Corrigir envio imediato ao selecionar anexo nos testes; exigir Enviar e adicionar revisão item a item.

Verificações locais aprovadas; revisão visual no navegador incompleta.

Pendências: selo e consistência na lista, tipos/tamanhos de arquivos, API de contatos, cartão de compartilhamento/link curto de Will, denúncias e texto de segurança.

[Commit 2095bd8](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/2095bd860752d9810050c1e3d96db794115a8f76)

## v46 · 2026-11-13 · 去掉卡片的已添加联系人

### 中文

去掉卡片的已添加联系人

商业会话、首次联系及测试商户身份卡片

- 已添加后不显示“已添加联系人”行；未添加时保留入口。

本地交互检查通过；浏览器视觉验收未完成。

待确认：认证字段／列表一致性、文件白名单与大小、通讯录接口复用、Will 分享卡片与短链、冠创团队举报枚举、安全服务说明。

### English

Remove saved-contact label from cards

Business chat, first contact and test merchant identity cards

- Hide the added-contact row after saving; retain the action before saving.

Local interaction checks passed; browser visual review incomplete.

Pending: badge field/list consistency, file types and sizes, Contacts API reuse, Will sharing card/shortlink, report taxonomy and security wording.

### Português (BR)

Remover indicação de contato adicionado dos cartões

Cartões de identidade em conversas, primeiro contato e testes

- Ocultar a linha de contato adicionado após salvar; manter a ação antes de salvar.

Verificações locais aprovadas; revisão visual no navegador incompleta.

Pendências: selo e consistência na lista, tipos/tamanhos de arquivos, API de contatos, cartão de compartilhamento/link curto de Will, denúncias e texto de segurança.

[Commit 6960d91](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/6960d914e2b2770821811afd57a18b625e44af23)

## v45 · 2026-11-13 · 落实 11/13 会议交互要求

### 中文

落实 11/13 会议交互要求

访问路径、会话列表、输入、主页及消息操作

- 新增入口汇总、H5 冷／热启动到商户主页、联系人表单及语音演示。
- 补齐消息回执、文本／图片／文件模板、Push 兜底、默认头像、安全说明和举报候选项。
- 商业帐户说明改为不可点击，移除主页 Favourites 和限时消息。

本地交互检查通过；浏览器视觉验收未完成。

待确认：认证字段／列表一致性、文件白名单与大小、通讯录接口复用、Will 分享卡片与短链、冠创团队举报枚举、安全服务说明。

### English

Nov 13 meeting interaction updates

Access paths, chat list, composer, profile and message actions

- Add an access hub, H5 cold/warm launch to business profile, contact form and voice demo.
- Add receipts, text/image/document templates, Push fallback, default avatar, security details and candidate report types.
- Make account details static; remove profile Favourites and temporary messages.

Local interaction checks passed; browser visual review incomplete.

Pending: badge field/list consistency, file types and sizes, Contacts API reuse, Will sharing card/shortlink, report taxonomy and security wording.

### Português (BR)

Atualizações de interação da reunião de 13/11

Acesso, lista de conversas, entrada, perfil e ações de mensagem

- Adicionar central de acesso, abertura fria/quente do H5 para o perfil, formulário de contato e demonstração de voz.
- Adicionar recibos, modelos de texto/imagem/arquivo, fallback de Push, avatar padrão, segurança e tipos propostos de denúncia.
- Tornar detalhes comerciais estáticos; remover Favoritos do perfil e mensagens temporárias.

Verificações locais aprovadas; revisão visual no navegador incompleta.

Pendências: selo e consistência na lista, tipos/tamanhos de arquivos, API de contatos, cartão de compartilhamento/link curto de Will, denúncias e texto de segurança.

[Commit 2b008d6](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/2b008d676a393df894683e8825a3b02f0998b5c3)

## v44 · 2026-11-12 · 采用 H5 定稿

### 中文

采用 H5 定稿

H5 正常落地页、失效页

- 使用浮动 PhizChat 横幅、居中商户卡片和法律页脚；失效链接显示不可用页。

已核实提交记录；历史验证结果未补录。

以该版本提交为准；后续规则可覆盖旧规则。

### English

Final H5 layout

Available and unavailable H5 landing pages

- Use the floating PhizChat banner, centered merchant card and legal footer; show an unavailable page for invalid links.

Commit verified; historical validation results were not backfilled.

Refer to this commit; later rules may supersede it.

### Português (BR)

Layout final do H5

Páginas H5 disponíveis e indisponíveis

- Usar faixa flutuante do PhizChat, cartão comercial central e rodapé legal; mostrar indisponibilidade para links inválidos.

Commit verificado; resultados históricos de validação não foram recuperados.

Consulte o commit; regras posteriores podem substituí-lo.

[Commit cd598d0](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/cd598d02439808c36d7ca790235a4754d4899f00)

## v43 · 2026-11-12 · 统一商户身份卡片

### 中文

统一商户身份卡片

会话内商户卡片

- 居中头像、名称、认证时间及固定介绍；屏蔽／主页并列，添加联系人单独保留。

已核实提交记录；历史验证结果未补录。

以该版本提交为准；后续规则可覆盖旧规则。

### English

Unified merchant identity cards

In-chat merchant cards

- Center avatar, name, verification date and fixed introduction; place Block/Profile together and keep Add contact separately.

Commit verified; historical validation results were not backfilled.

Refer to this commit; later rules may supersede it.

### Português (BR)

Cartões de identidade comercial unificados

Cartões comerciais na conversa

- Centralizar avatar, nome, data de verificação e apresentação fixa; agrupar Bloquear/Perfil e manter Adicionar contato separado.

Commit verificado; resultados históricos de validação não foram recuperados.

Consulte o commit; regras posteriores podem substituí-lo.

[Commit 86ccf6e](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/86ccf6ecc46d0f1c110e5f96e7d45003279be2f9)

## v42 · 2026-11-12 · 帐户资料卡片跳转会话

### 中文

帐户资料卡片跳转会话

商户主页帐户资料块

- 当时将帐户资料块设为会话入口；此交互已被 v45 的不可点击规则替代。

已核实提交记录；历史验证结果未补录。

以该版本提交为准；后续规则可覆盖旧规则。

### English

Account details card opens chat

Business profile account-details block

- At that time, account details opened chat; v45 superseded this with static account details.

Commit verified; historical validation results were not backfilled.

Refer to this commit; later rules may supersede it.

### Português (BR)

Cartão de dados comerciais abre conversa

Bloco de dados no perfil comercial

- Na época, os dados comerciais abriam a conversa; v45 substituiu isso por dados estáticos.

Commit verificado; resultados históricos de validação não foram recuperados.

Consulte o commit; regras posteriores podem substituí-lo.

[Commit 3ba4ac8](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/3ba4ac8656ff6b6be9be845ab64941111cb52595)

## v41 · 2026-11-12 · 商户主页按 A／B 场景展示

### 中文

商户主页按 A／B 场景展示

未创建／已创建会话的主页

- 采用封面式主页；未创建会话显示 A 区，创建后显示全部；关联入口按关联状态展示。

已核实提交记录；历史验证结果未补录。

以该版本提交为准；后续规则可覆盖旧规则。

### English

Business profile A/B states

Profiles before/after conversation creation

- Use a cover-style profile; show A sections before creation and all sections afterwards; linked entries follow availability.

Commit verified; historical validation results were not backfilled.

Refer to this commit; later rules may supersede it.

### Português (BR)

Estados A/B do perfil comercial

Perfis antes/depois da criação da conversa

- Usar perfil com capa; mostrar seções A antes da criação e todas depois; acessos vinculados seguem disponibilidade.

Commit verificado; resultados históricos de validação não foram recuperados.

Consulte o commit; regras posteriores podem substituí-lo.

[Commit 728c73a](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/728c73a66711cd54ce5ed4234cef59d05bc7c945)

## v40 · 2026-11-12 · 补齐预览状态与备注

### 中文

补齐预览状态与备注

预览状态分类、会话列表场景说明

- 七类预览场景补充备注，增加无小程序及频道／小程序均未关联场景。

已核实提交记录；历史验证结果未补录。

以该版本提交为准；后续规则可覆盖旧规则。

### English

Preview states and remarks

Preview-state groups and chat-list scenario notes

- Add remarks across seven preview groups, including no Mini App and neither Channel nor Mini App linked.

Commit verified; historical validation results were not backfilled.

Refer to this commit; later rules may supersede it.

### Português (BR)

Estados de prévia e observações

Grupos de estados e notas da lista de conversas

- Adicionar observações em sete grupos, incluindo ausência de Mini App e ausência de ambos os vínculos.

Commit verificado; resultados históricos de validação não foram recuperados.

Consulte o commit; regras posteriores podem substituí-lo.

[Commit d4a8ff1](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/d4a8ff1104d766c05d251847500f3bfb614452e0)

## 更早提交 / Earlier commits / Commits anteriores

原始提交标题保留；未追补设计版本号或历史验收结果。

- 2026-11-12T02:54:53Z · [Document conversation-list states and add unlinked Mini App preview](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/e54acdacb8ddbb22495f6c487e7cb0a800dc4099)
- 2026-11-11T08:13:32Z · [Keep platform delivery restrictions ahead of category consent](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/940513fa90e7d4227a094e2d6969b908d2fbf98c)
- 2026-11-11T08:10:12Z · [Classify preview states and preserve independent conversation consent](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/727f321a49dbb7fc48902314469bc622c8bb8839)
- 2026-11-05T11:02:27Z · [Simulate second marketing delivery after independent consent](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/643d662b352e1ba9e2baad6e46a9af8e9042d863)
- 2026-11-05T10:56:55Z · [Use a single add-contact entry on business profiles](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/fc84e4f4e886daca772c2271146bd204af71b21a)
- 2026-11-05T10:47:54Z · [Fit the PicPay banner to its message card](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/75dadf3e33919671a47954cb32429fc104e0df18)
- 2026-11-05T10:45:58Z · [Show PicPay marketing as an image, copy and offer action](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/d4d95e812a3d360091238af45e1d75add71bae18)
- 2026-11-05T10:26:44Z · [Simplify in-chat consent to one message-specific action](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/5214255d31afc260e95d9aacb58504cf2e20674a)
- 2026-11-05T09:37:07Z · [Attach Business Account consent to Utility and Marketing messages](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/6c43ec9925bd63b8205110488c7a9f9226531e1f)
- 2026-11-05T03:59:42Z · [Share business management and notification settings across all conversation previews](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/1edf54c5de6e91f6f15e46b247c140acd67c56ac)
- 2026-11-05T03:45:38Z · [Unify PhizChat Push, inline acceptance and check confirmation; centralize notification management](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/dbee6be27ecc4bf039fd4f050c4c7c0eaeab890a)
- 2026-11-05T03:32:02Z · [Restore source-file inline Phiz consent card and direct Accept notices button](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/dd410cc3ae021086bc992d8dd1c3a8be095c02a0)
- 2026-11-05T03:20:40Z · [Add business management menu and scoped subscription notification controls](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/e3bf70cc1fa3070be8f62a6dafc25aa01d456765)
- 2026-11-05T02:36:09Z · [Unify business profiles and scoped consent; refine in-app billing page](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/c518bd11008b4b1d5ef06cdb7a2c113bc69ad6c8)
- 2026-11-04T21:01:39Z · [Restore scenario content verbatim from supplied Phase 1 HTML](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/16ddea24ab9106b3d59a3e3f74cfdc1cfce0f56e)
- 2026-11-04T20:43:29Z · [Align merchant cases with shared chat UI and close consent/control flows](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/0313a063fef4ea57047c7f7611f9274f6f3e7c6f)
- 2026-11-04T20:27:03Z · [Add nine Phase 1 merchant test scenarios and align message scope](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/5bfe627feeb72889b3ab4aedd4f8ddb053a2623c)
- 2026-11-04T06:52:27Z · [Keep Add to contacts on its own row and remove duplicate chat entry](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/514b8bfa7c0aab606dae87b916d4006751494ff2)
- 2026-11-04T06:29:15Z · [Show first-contact add reminder only after accepting and reloading](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/e9d753f4fb003096131a413bc7123e1d4d4dac18)
- 2026-11-04T06:16:28Z · [Clarify created conversation preview without service window](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/3b7fc76c1147cf54ec49ee0b5ff0bf612e20bbc5)
- 2026-11-04T06:12:40Z · [Update v19: profile stages, contact reminder and acceptance system message](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/caefd1a395eb1e5d1ade51a336e4e2d60588005b)
- 2026-11-02T08:48:47Z · [Update Business Account interactive design to v18](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/897a1da4de3f51293b268e176ffa4c700ec86b4a)
- 2026-10-29T06:54:26Z · [Add interactive Business Account review](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/ea83322a605bfb9699b64d5126022c9ed84cd12c)
- 2026-10-29T06:45:56Z · [Initial commit](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/0ed4559e19c1fec728504bfb1249dfdde06e3d4d)
