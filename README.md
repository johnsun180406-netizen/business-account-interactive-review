# Business Account Interactive Review

Current design: **v50** · 2026-11-16

PicPay is an example merchant. This prototype does not establish App/API implementation or acceptance.

- [Open interactive prototype](https://johnsun180406-netizen.github.io/business-account-interactive-review/prototype.html)
- [Version history / 版本记录 / Histórico / Historial](https://johnsun180406-netizen.github.io/business-account-interactive-review/versions.html)
- [Changelog](CHANGELOG.md) · [Versioning process](VERSIONING.md) · [Registry](versions.json)
- [Original project and IM review](https://johnsun180406-netizen.github.io/business-account-interactive-review/)
- Download [prototype.html](prototype.html) to open an offline interactive copy.

新增西班牙语（墨西哥）版本 / Add Spanish (Mexico) / Adicionar espanhol (México) / Agregar español (México)

- 增加Español (México)选项，补齐896条西班牙语文案及动态参数，语言选择可恢复。 / Add Español (México), 896 Spanish messages and dynamic placeholders, with saved language restoration. / Adicionar Español (México), 896 textos e parâmetros dinâmicos, com restauração do idioma salvo. / Agregar Español (México), 896 textos y parámetros dinámicos, con restauración del idioma guardado.
- 补齐状态分类、消息形态、通知授权、错误提示、场景步骤与团队版本记录的西语内容。 / Localize states, message formats, notification consent, errors, scenario steps and team version history. / Traduzir estados, formatos, consentimento, erros, etapas de cenários e histórico da equipe. / Traducir estados, formatos, consentimiento de avisos, errores, pasos de escenarios e historial del equipo.
- 保留既有中英葡语言及交互规则；示例商户名称、CNPJ、Pix、CPF和R$金额保留原始业务数据。 / Preserve existing Chinese, English, Portuguese and interaction rules; keep original merchant names, CNPJ, Pix, CPF and R$ amounts. / Preservar os idiomas e regras existentes; manter nomes dos comerciantes, CNPJ, Pix, CPF e valores em R$. / Conservar los idiomas y reglas existentes; mantener los nombres de empresas, CNPJ, Pix, CPF y montos en R$.

西语页面、22类预览状态、消息形态、弹层、九个场景及其所有步骤渲染检查通过；接受状态独立、输入和媒体上限、草稿保留、语言恢复及既有流程回归通过。尚未完成墨西哥母语审校和浏览器视觉验收。

PRD同步双向上限和禁用视频；Marketing一期范围、四项首条入口、CNPJ、接待提示及回执语义需收口；MIME、字节与计数细则、通讯录接口、分享、举报枚举及实际安全保护待确认。

[Nov 13 meeting recheck](Meeting-20261113-Recheck-v47.md)
