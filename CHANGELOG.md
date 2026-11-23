# Business Account · 版本更新记录 / Changelog / Histórico

当前设计版本 / Current design / Design atual: **v51**

vN 是设计版本，不代表 App 或 API 发布。发布日期按北京时间；历史验证未留存时明确标记。

## v51 · 2026-11-23 · 按最新 Figma 更新首条消息授权与商业主页管理入口

### 中文

按最新 Figma 更新首条消息授权与商业主页管理入口

商业会话、企业首次联系、两类消息同时待确认、九个源文件测试场景及四语版本记录

- 移除商业会话右上角设置入口；通过商家名称或资料卡进入商业主页，日常消息管理、静音和屏蔽沿用主页入口。
- 首条消息后使用白色确认卡，左侧停止、右侧接受；接受后显示带停止入口的简短系统提示。
- 补齐停止确认、已停止提示、重新接收确认及继续接收的闭环；停止只作用于当前消息类别，屏蔽作用于整个商家。
- 服务与营销分别确认；未选择或取消保持待确认，用户回复、添加联系人均不自动授权。主示例与文件测试场景复用同一交互。

四语授权独立性、接受/停止/恢复、取消、离线失败、屏蔽与解除反馈通过；全部预览状态和九个场景逐步渲染通过；已有联系人、H5、输入与长按等10组回归检查通过。

本次为交互原型更新，不代表 App/API 已实现或发布；中、西语为设计稿对应译文，母语审校仍待完成。原 PRD/API 接口、分享及举报枚举等待办继续按原清单跟进。

### English

Align first-message consent and profile management with Figma

Business chats, first contact, dual-category requests, nine source scenarios and four-language version history

- Remove chat-header settings; use the business name or profile card to access daily message, mute and block controls in the profile.
- Use a white card after the first message, with Stop left and Accept right; acceptance becomes a compact system notice with Stop.
- Complete stop confirmation, inactive notice and reactivation confirmation. Stop affects the current category; Block affects the entire business.
- Keep service and marketing consent independent. Ignoring or cancelling stays pending; replies and contact saving never imply consent. Main and source scenarios share the flow.

Four-language independent consent, accept/stop/resume, cancel, offline failure and block feedback passed. All preview states and nine scenario steps render. Ten existing regression groups passed.

Prototype update only, not an App/API implementation or release. Chinese and Mexican Spanish equivalents await native review. Existing PRD/API, sharing and report-type follow-ups remain.

### Português (BR)

Alinhar consentimento inicial e gestão no perfil ao Figma

Conversas comerciais, primeiro contato, duas categorias pendentes, nove cenários e histórico em quatro idiomas

- Remover configurações do cabeçalho; acessar gestão de mensagens, silenciamento e bloqueio pelo nome ou cartão de perfil.
- Exibir cartão branco após a primeira mensagem, com Parar à esquerda e Aceitar à direita; a aceitação vira aviso compacto com Parar.
- Completar confirmação de parada, aviso desativado e reativação. Parar afeta a categoria atual; Bloquear afeta toda a empresa.
- Manter autorizações de serviço e marketing independentes. Ignorar ou cancelar mantém pendente; responder e salvar contato não autorizam. Exemplos e cenários compartilham o fluxo.

Aprovados consentimento independente, aceitar/parar/reativar, cancelar, falha offline e bloqueio em quatro idiomas. Estados e nove cenários renderizados; dez grupos de regressão aprovados.

Atualização apenas do protótipo, sem implementação ou lançamento do App/API. Traduções chinesa e mexicana aguardam revisão nativa. Pendências de PRD/API, compartilhamento e denúncias permanecem.

### Español (México)

Alinear el consentimiento inicial y la administración en el perfil con Figma

Chats de empresa, primer contacto, dos categorías pendientes, nueve escenarios e historial en cuatro idiomas

- Quitar los ajustes del encabezado; acceder a mensajes, silencio y bloqueo desde el nombre o la tarjeta de perfil.
- Mostrar una tarjeta blanca tras el primer mensaje, con Detener a la izquierda y Aceptar a la derecha; al aceptar aparece un aviso compacto con Detener.
- Completar la confirmación para detener, el aviso desactivado y la reactivación. Detener afecta la categoría actual; Bloquear afecta toda la empresa.
- Mantener independientes los permisos de servicio y marketing. Ignorar o cancelar conserva el estado pendiente; responder y guardar contactos no autoriza. Los ejemplos y escenarios comparten el flujo.

Pasaron las pruebas de permisos independientes, aceptar/detener/reactivar, cancelar, sin conexión y bloqueo en cuatro idiomas. Se renderizan los estados y nueve escenarios; pasaron diez grupos de regresión.

Actualización solo del prototipo, no de la implementación o publicación de App/API. Las traducciones al chino y español de México esperan revisión nativa. Siguen los pendientes de PRD/API, compartir y reportes.

## v50 · 2026-11-16 · 新增西班牙语（墨西哥）版本

### 中文

新增西班牙语（墨西哥）版本

语言切换、会话列表、商业会话、商业主页、H5访问路径、弹层、全部九个测试场景和版本记录

- 增加Español (México)选项，补齐896条西班牙语文案及动态参数，语言选择可恢复。
- 补齐状态分类、消息形态、通知授权、错误提示、场景步骤与团队版本记录的西语内容。
- 保留既有中英葡语言及交互规则；示例商户名称、CNPJ、Pix、CPF和R$金额保留原始业务数据。

西语页面、22类预览状态、消息形态、弹层、九个场景及其所有步骤渲染检查通过；接受状态独立、输入和媒体上限、草稿保留、语言恢复及既有流程回归通过。尚未完成墨西哥母语审校和浏览器视觉验收。

PRD同步双向上限和禁用视频；Marketing一期范围、四项首条入口、CNPJ、接待提示及回执语义需收口；MIME、字节与计数细则、通讯录接口、分享、举报枚举及实际安全保护待确认。

### English

Add Spanish (Mexico)

Language switcher, chat list, business chat/profile, H5 access, sheets, all nine test scenarios and version history

- Add Español (México), 896 Spanish messages and dynamic placeholders, with saved language restoration.
- Localize states, message formats, notification consent, errors, scenario steps and team version history.
- Preserve existing Chinese, English, Portuguese and interaction rules; keep original merchant names, CNPJ, Pix, CPF and R$ amounts.

Spanish page, 22-preset, format, sheet and all nine scenario-step render checks passed. Independent consent, input/media limits, draft retention, saved language and existing flow regressions passed. Native Mexican review and browser visual acceptance remain pending.

Align PRD limits and no-video scope; resolve Marketing phase, first-contact controls, CNPJ, handoff notices and receipt semantics. MIME/byte/counting rules, Contacts API, sharing, report types and actual security protection remain pending.

### Português (BR)

Adicionar espanhol (México)

Seletor de idioma, lista, conversa e perfil comercial, acesso H5, painéis, nove cenários e histórico

- Adicionar Español (México), 896 textos e parâmetros dinâmicos, com restauração do idioma salvo.
- Traduzir estados, formatos, consentimento, erros, etapas de cenários e histórico da equipe.
- Preservar os idiomas e regras existentes; manter nomes dos comerciantes, CNPJ, Pix, CPF e valores em R$.

Aprovadas verificações de páginas, 22 estados, formatos, painéis, nove cenários e etapas, consentimento independente, limites, rascunhos, idioma salvo e regressão. Revisão por falante mexicano e aceite visual pendentes.

Alinhar limites e ausência de vídeo no PRD; resolver Marketing, controles iniciais, CNPJ, avisos de atendimento e recibos. MIME/bytes/contagem, API de contatos, compartilhamento, denúncias e proteção real pendentes.

### Español (México)

Agregar español (México)

Selector de idioma, lista de chats, conversación y perfil de empresa, acceso H5, paneles, nueve escenarios e historial

- Agregar Español (México), 896 textos y parámetros dinámicos, con restauración del idioma guardado.
- Traducir estados, formatos, consentimiento de avisos, errores, pasos de escenarios e historial del equipo.
- Conservar los idiomas y reglas existentes; mantener los nombres de empresas, CNPJ, Pix, CPF y montos en R$.

Pasaron las revisiones de páginas, 22 estados, formatos, paneles, nueve escenarios y sus pasos, consentimiento independiente, límites, borradores, idioma guardado y regresión. Quedan pendientes la revisión por un hablante mexicano y la validación visual en navegador.

Alinear los límites y la exclusión de video en el PRD; resolver Marketing, controles iniciales, CNPJ, avisos de atención y recibos. MIME, bytes, conteo, API de contactos, compartir, reportes y protección real siguen pendientes.

[Commit 0729725](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/07297253476986df9169ca583d1c1d7f11d505de)

## v49 · 2026-11-16 · 安全提示定稿、双向媒体上限与PRD差异复核

### 中文

安全提示定稿、双向媒体上限与PRD差异复核

商业会话、首次联系、测试场景、附件选择、文本发送、版本记录与审核报告

- 顶部黄色提示与安全弹层按11/16截图统一，底部按钮进入对应企业主页。
- 上下行统一图片5MB、音频16MB、普通文件100MB、文本4096字符；本期不提供视频。增加超限提示并保留待发送内容。
- 对照在线总PRD快照d1:3175完成25项差异复核，区分PRD待同步、范围裁决、文案、原型覆盖和联调验证。

三语安全文案、跳转、内容上限/超限、4096/4097码点、失败保留输入及既有交互回归通过；真实媒体链路和浏览器视觉验收尚未完成。

PRD同步双向上限和禁用视频；Marketing一期范围、四项首条入口、CNPJ、接待提示及回执语义需收口；MIME、字节与计数细则、通讯录接口、分享、举报枚举及实际安全保护待确认。

### English

Security copy, bidirectional media limits and PRD audit

Business chat, first contact, test cases, attachments, text sending, history and audit

- Match the yellow notice and security sheet to the Nov 16 screenshot; the CTA opens the corresponding company profile.
- Unify both directions: image 5 MB, audio 16 MB, document 100 MB, text 4096 characters; no video. Reject over-limit input while preserving drafts.
- Audit 25 differences against live master PRD snapshot d1:3175, separating document updates, scope decisions, wording, prototype coverage and integration.

Trilingual copy, profile routing, limits/overflow, 4096/4097 code points, draft retention and existing regression checks passed; real media integration and browser visual review remain incomplete.

Align PRD limits and no-video scope; resolve Marketing phase, first-contact controls, CNPJ, handoff notices and receipt semantics. MIME/byte/counting rules, Contacts API, sharing, report types and actual security protection remain pending.

### Português (BR)

Texto de segurança, limites bidirecionais e revisão do PRD

Conversa comercial, primeiro contato, testes, anexos, envio de texto, histórico e revisão

- Alinhar aviso amarelo e painel à captura de 16/11; o botão abre o perfil da empresa correspondente.
- Unificar ambas as direções: imagem 5 MB, áudio 16 MB, arquivo 100 MB, texto 4096 caracteres; sem vídeo. Rejeitar excesso mantendo o rascunho.
- Revisar 25 diferenças frente ao PRD online d1:3175, separando atualização documental, escopo, redação, cobertura do protótipo e integração.

Texto em três idiomas, navegação, limites/excesso, 4096/4097 pontos de código, rascunhos e regressão aprovados; integração real de mídia e revisão visual ainda incompletas.

Alinhar limites e ausência de vídeo no PRD; resolver Marketing, controles iniciais, CNPJ, avisos de atendimento e recibos. MIME/bytes/contagem, API de contatos, compartilhamento, denúncias e proteção real pendentes.

### Español (México)

Texto de seguridad, límites bidireccionales y revisión del PRD

Chat de empresa, primer contacto, pruebas, adjuntos, texto, historial y revisión

- Alinear el aviso amarillo y el panel de seguridad con la captura del 16/11; el botón abre el perfil de la empresa correspondiente.
- Unificar ambas direcciones: imagen 5 MB, audio 16 MB, documento 100 MB, texto 4096 caracteres; sin video. Rechazar los excesos conservando el borrador.
- Revisar 25 diferencias con el PRD principal online d1:3175, separando cambios documentales, decisiones de alcance, redacción, cobertura e integración.

Pasaron las revisiones de tres idiomas, navegación, límites/excesos, 4096/4097 puntos de código, conservación de borradores y regresión. La integración multimedia real y la revisión visual en navegador siguen pendientes.

Alinear los límites y la exclusión de video en el PRD; resolver Marketing, controles iniciales, CNPJ, avisos de atención y recibos. MIME, bytes, conteo, API de contactos, compartir, reportes y protección real siguen pendientes.

[Commit 2008ad5](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/2008ad53a1e04ebd720d32e9816d197750934cdf)

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

### Español (México)

Administración de versiones para el equipo

Encabezado del prototipo, historial, registro de cambios y proceso de publicación

- Agregar una entrada de versión actual con cambios, impacto, validación y pendientes por publicación.
- Generar interfaz y registro desde una sola fuente; recuperar v40–v47 y conservar los commits anteriores como historial original.

Revisiones de datos, consistencia de compilación y regresión; revisión visual en navegador pendiente.

Pendientes: insignia y consistencia, formatos/tamaños de archivos, API de contactos, tarjeta/enlace de Will, clasificación de reportes y texto de seguridad.

[Commit 3c38a56](https://github.com/johnsun180406-netizen/business-account-interactive-review/commit/3c38a56864ea69dbaee3779fc78d170ee00ccd7c)

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

### Español (México)

Alineación de entrada y revisión de la reunión

Chat normal, primer contacto, pruebas y lista del 13/11

- Unificar agregar, emoji, cámara y alternancia voz/enviar; usar una cuadrícula inferior de cinco adjuntos.
- Corregir el envío inmediato al elegir adjuntos en pruebas; exigir Enviar y agregar revisión por punto.

Revisiones locales de interacción aprobadas; revisión visual en navegador pendiente.

Pendientes: insignia y consistencia, formatos/tamaños de archivos, API de contactos, tarjeta/enlace de Will, clasificación de reportes y texto de seguridad.

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

### Español (México)

Quitar la indicación de contacto agregado de las tarjetas

Tarjetas de identidad en chats, primer contacto y pruebas

- Ocultar la fila de contacto agregado después de guardar; mantener la acción antes de guardarlo.

Revisiones locales de interacción aprobadas; revisión visual en navegador pendiente.

Pendientes: insignia y consistencia, formatos/tamaños de archivos, API de contactos, tarjeta/enlace de Will, clasificación de reportes y texto de seguridad.

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

### Español (México)

Actualizaciones de interacción de la reunión del 13/11

Rutas de acceso, lista, entrada, perfil y acciones de mensajes

- Agregar una central de acceso, apertura H5 en frío/caliente al perfil, formulario de contacto y demostración de voz.
- Agregar recibos, plantillas de texto/imagen/documento, alternativa Push, avatar predeterminado, seguridad y tipos de reporte propuestos.
- Hacer estáticos los datos comerciales; quitar Favoritos del perfil y mensajes temporales.

Revisiones locales de interacción aprobadas; revisión visual en navegador pendiente.

Pendientes: insignia y consistencia, formatos/tamaños de archivos, API de contactos, tarjeta/enlace de Will, clasificación de reportes y texto de seguridad.

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

### Español (México)

Diseño final del H5

Páginas H5 disponibles y no disponibles

- Usar la franja flotante de PhizChat, tarjeta central y pie legal; mostrar la página no disponible para enlaces inválidos.

Commit verificado; no se recuperaron resultados históricos de validación.

Consulta este commit; las reglas posteriores pueden reemplazarlo.

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

### Español (México)

Tarjetas de identidad de empresa unificadas

Tarjetas de empresa en el chat

- Centrar avatar, nombre, fecha de verificación e introducción fija; Bloquear y Perfil juntos, con Agregar contacto por separado.

Commit verificado; no se recuperaron resultados históricos de validación.

Consulta este commit; las reglas posteriores pueden reemplazarlo.

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

### Español (México)

La tarjeta de datos comerciales abre el chat

Bloque de datos de la cuenta en el perfil

- En ese momento los datos abrían el chat; v45 lo sustituyó por datos estáticos.

Commit verificado; no se recuperaron resultados históricos de validación.

Consulta este commit; las reglas posteriores pueden reemplazarlo.

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

### Español (México)

Estados A/B del perfil de empresa

Perfiles antes y después de crear la conversación

- Usar un perfil con portada; mostrar secciones A antes de crear el chat y todas después; los accesos vinculados dependen de su disponibilidad.

Commit verificado; no se recuperaron resultados históricos de validación.

Consulta este commit; las reglas posteriores pueden reemplazarlo.

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

### Español (México)

Estados de vista previa y notas

Grupos de estados y notas de la lista de chats

- Agregar notas a siete grupos, incluida la falta de Mini App y la ausencia de Canal y Mini App.

Commit verificado; no se recuperaron resultados históricos de validación.

Consulta este commit; las reglas posteriores pueden reemplazarlo.

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
