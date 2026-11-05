# Business Account Interactive Review

PhizChat Business Account project and IM review, with an integrated interactive prototype. PicPay is an example merchant.

- [Review page](https://johnsun180406-netizen.github.io/business-account-interactive-review/) — existing project and IM documents, with the updated prototype in the “交互原型 / Interactive prototype” section.
- [Open the latest interactive prototype](https://johnsun180406-netizen.github.io/business-account-interactive-review/prototype.html)
- Download [prototype.html](prototype.html) and open it in a browser for an offline interactive copy.

## Design v25 · 2026-11-05

- First-contact consent appears with the first merchant message, separate from the identity card.
- Test scenarios use shared conversation rows, bubbles, composer and sheets.
- Nine merchant scenarios are available in Test scenarios, with source-file content preserved verbatim; specification conflicts are flagged separately.
- Interactive cases cover handoff, file retry, URL failures, reply/list actions, expiry and Utility pause/resume.
- Users can reply before accepting; replying does not grant consent.
- Accept is separate from adding the business to contacts.
- Profiles show public information before conversation creation, and full settings afterwards. Add to contacts occupies its own row near the top; the duplicate conversation row is removed. The Support shortcut below the logo opens the conversation. Block remains at the bottom.
- For first business contact, Add to contacts appears only after acceptance and a page reload. Accept and Add to contacts are never shown together. Other conversation prompts are unchanged. Saving a contact does not grant consent.
- The business introduction is fixed; acceptance inserts a separate system message.
- Blocking and unblocking insert system notices in the conversation.
- Conversation previews stay on one line with the time aligned to the right.
- English, 简体中文 and Português (BR) are supported.

The original project and IM review documents are preserved. Their text is not a statement that backend capabilities are implemented. This prototype simulates interactions locally; it does not send real messages or process payments.

中文：保留既有立项与 IM 评审文档，更新内嵌交互稿。独立交互稿支持下载后用浏览器打开。

Português (Brasil): os documentos existentes de revisão foram preservados e o protótipo integrado foi atualizado. A versão independente pode ser aberta localmente no navegador.
