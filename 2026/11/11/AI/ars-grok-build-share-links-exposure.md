# 研究称数万个 Grok Build 分享链接可被枚举，部分应用暴露敏感信息

[当日日报](../日报.md#hl-grok) · [首页](../../../../README.md#hl-grok)

- **版块**: AI
- **来源**: Ars Technica
- **来源链接**: https://arstechnica.com/security/2026/11/grok-build-coding-agent-leaks-oodles-of-confidential-info-some-belonging-to-spacexsi/
- **原始发布时间**: Ars 稿件 byline “Dan Goodin – Nov 10, 2026 4:12 pm”。页面未标明时区，故不把换算钟点写成已确认的首次发布时间。
- **上海时间**: 原文 byline 为 Nov 10, 2026 4:12 pm，页面未标明时区，不换算为已确认的上海时间
- **窗口**: byline 未标时区

## 摘要

Ars Technica 报道，安全公司 Claroc 的研究发现，Grok Build 用于分享应用的链接可被枚举。研究者称，检索到 43,601 个以 grok.me 结尾的链接，其中超过 35,000 个（约 95%）是公开的，打开后可以看到应用及其存储的数据。测试还称，默认设置为「任何持有链接的人可访问」，用户需手动改为仅邀请或仅自己可见。

报道称，暴露内容包括企业内部材料和个人敏感信息。Ars 还写道，其中也包括 SpaceXSI 自己搭建的应用，并把 SpaceXSI 称为 SpaceX 与 xAI 合并后的公司；这一说法按 Ars 的转述记录，本稿没有另行核实。Claroc 已在周日通知该公司；在 Ars 发问后，上述应用链接被移除。Ars 称，Cursor / SpaceXSI 回复说应用默认私密、只有创建者选择分享才会公开，但这一说法与研究者的默认设置测试并不一致。文章建议，除非有意公开，否则不要使用「任何持有链接的人可访问」。

为何关注：分享链接的默认权限和 URL 设计，会直接决定用 Grok Build 快速搭出的内部工具会不会在无意中对外暴露。
