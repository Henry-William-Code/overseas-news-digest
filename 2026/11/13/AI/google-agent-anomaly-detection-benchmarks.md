# Google 公布 Agent Anomaly Detection 在外部安全基准上的测试结果

[当日日报](../日报.md#google-agent-anomaly-detection-benchmarks) · [首页](../../../../README.md#google-agent-anomaly-detection-benchmarks)

- **版块**: AI
- **来源**: Google Developers Blog
- **来源链接**: https://developers.googleblog.com/how-agent-anomaly-detection-scores-on-benchmarks-we-didnt-write/
- **原始发布时间**: 页面可见日期 NOV. 12, 2026。JSON-LD datePublished 也只有 2026-11-12，没有时区或钟点。读者可见时间因此只写日期，不编造钟点，也不把本条记为已经证实的 24 小时时刻。
- **上海时间**: 2026-11-12（页面仅有日期，钟点未核验）
- **窗口**: 仅有日期 2026-11-12（钟点未核验，不记为已证实的 24 小时时刻）

## 摘要

Google 工程师在开发者博客介绍 Agent Anomaly Detection（AAD）。这项功能今年 9 月已在 Gemini Enterprise Agent Platform 以 Private Preview 推出。这次用五份不是谷歌编写的公开智能体安全基准做了测试。AAD 异步读取 OpenTelemetry 追踪和日志，不给运行时增加延迟，用来标出智能体偏离预期边界的会话。

官方称，模型本身大约一半的有害指令没有被执行；在已经执行的有害指令里，AAD 标出了 87%。误报率随工具而不同，大约落在良性会话的 2% 到 16%。对写进长期记忆的攻击最弱：18 次造成实际行为的案例里只抓住 4 次。基准包括 AgentDojo、InjecAgent、Agent Security Bench、AgentDyn 和 AgentHarm，一共 1,774 个会话。

作者也写出限制：只用了一种智能体模型，任务是模拟应用，大约 6% 的会话没有返回结果。该功能仍是 Private Preview。文中数字是 Google 自己复现公开基准的结果，不是独立审计。

为何关注：智能体目标劫持已被列为主要风险之一；这份测试刻意不用自家题目，但功能尚未正式商用，且对投毒记忆一类攻击仍然薄弱。
