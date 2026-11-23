# Business Account Interactive Review

Current design: **v51** · 2026-11-23

PicPay is an example merchant. This prototype does not establish App/API implementation or acceptance.

- [Open interactive prototype](https://johnsun180406-netizen.github.io/business-account-interactive-review/prototype.html)
- [Version history / 版本记录 / Histórico / Historial](https://johnsun180406-netizen.github.io/business-account-interactive-review/versions.html)
- [Changelog](CHANGELOG.md) · [Versioning process](VERSIONING.md) · [Registry](versions.json)
- [Original project and IM review](https://johnsun180406-netizen.github.io/business-account-interactive-review/)
- Download [prototype.html](prototype.html) to open an offline interactive copy.

按最新 Figma 更新首条消息授权与商业主页管理入口 / Align first-message consent and profile management with Figma / Alinhar consentimento inicial e gestão no perfil ao Figma / Alinear el consentimiento inicial y la administración en el perfil con Figma

- 移除商业会话右上角设置入口；通过商家名称或资料卡进入商业主页，日常消息管理、静音和屏蔽沿用主页入口。 / Remove chat-header settings; use the business name or profile card to access daily message, mute and block controls in the profile. / Remover configurações do cabeçalho; acessar gestão de mensagens, silenciamento e bloqueio pelo nome ou cartão de perfil. / Quitar los ajustes del encabezado; acceder a mensajes, silencio y bloqueo desde el nombre o la tarjeta de perfil.
- 首条消息后使用白色确认卡，左侧停止、右侧接受；接受后显示带停止入口的简短系统提示。 / Use a white card after the first message, with Stop left and Accept right; acceptance becomes a compact system notice with Stop. / Exibir cartão branco após a primeira mensagem, com Parar à esquerda e Aceitar à direita; a aceitação vira aviso compacto com Parar. / Mostrar una tarjeta blanca tras el primer mensaje, con Detener a la izquierda y Aceptar a la derecha; al aceptar aparece un aviso compacto con Detener.
- 补齐停止确认、已停止提示、重新接收确认及继续接收的闭环；停止只作用于当前消息类别，屏蔽作用于整个商家。 / Complete stop confirmation, inactive notice and reactivation confirmation. Stop affects the current category; Block affects the entire business. / Completar confirmação de parada, aviso desativado e reativação. Parar afeta a categoria atual; Bloquear afeta toda a empresa. / Completar la confirmación para detener, el aviso desactivado y la reactivación. Detener afecta la categoría actual; Bloquear afecta toda la empresa.
- 服务与营销分别确认；未选择或取消保持待确认，用户回复、添加联系人均不自动授权。主示例与文件测试场景复用同一交互。 / Keep service and marketing consent independent. Ignoring or cancelling stays pending; replies and contact saving never imply consent. Main and source scenarios share the flow. / Manter autorizações de serviço e marketing independentes. Ignorar ou cancelar mantém pendente; responder e salvar contato não autorizam. Exemplos e cenários compartilham o fluxo. / Mantener independientes los permisos de servicio y marketing. Ignorar o cancelar conserva el estado pendiente; responder y guardar contactos no autoriza. Los ejemplos y escenarios comparten el flujo.

四语授权独立性、接受/停止/恢复、取消、离线失败、屏蔽与解除反馈通过；全部预览状态和九个场景逐步渲染通过；已有联系人、H5、输入与长按等10组回归检查通过。

PRD同步双向上限和禁用视频；Marketing一期范围、四项首条入口、CNPJ、接待提示及回执语义需收口；MIME、字节与计数细则、通讯录接口、分享、举报枚举及实际安全保护待确认。

[Nov 13 meeting recheck](Meeting-20261113-Recheck-v47.md)
