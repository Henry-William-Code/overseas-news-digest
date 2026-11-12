# Moonshot AI 的 Kimi K3.1 Pro Highspeed 已在 Amazon Bedrock 上线

[当日日报](../日报.md#kimi-k3-1-pro-amazon-bedrock) · [首页](../../../../README.md#kimi-k3-1-pro-amazon-bedrock)

- **版块**: AI
- **来源**: Amazon Web Services
- **来源标题**: Introducing Kimi K3.1 Pro on Amazon Bedrock
- **来源链接**: https://aws.amazon.com/blogs/machine-learning/introducing-kimi-k3-1-pro-on-amazon-bedrock/
- **原始发布时间**: 可见署名行 on 10 NOV 2026；meta article:published_time 与 article:modified_time 均为 2026-11-10T17:07:19-08:00。AWS Machine Learning 博客 article:published_time 带显式 -08:00（2026 年 11 月为美国太平洋标准时间）。本条落在 48 小时窗口。
- **上海时间**: 2026-11-11 09:07
- **窗口**: 48小时内

## 摘要

AWS 宣布，Moonshot AI 的 Kimi K3.1 Pro Highspeed 已在 Amazon Bedrock 上提供。博文转述 Moonshot 的说法：它是 Kimi K3 的后训练版本，沿用同一套约 3T 参数量级的开放权重架构和 100 万 token 上下文，并针对长程代理任务、专业办公和部分编程场景做了加强；Highspeed 版本的输出速度，按 Moonshot 的说法约为 Kimi K3.1 Pro 的 2 到 3 倍。这些能力与速度对比均为供应商陈述。

AWS 称，该模型支持工具调用、结构化输出、可配置推理强度、图像输入和流式输出，并可通过 OpenAI 兼容的 Chat Completions / Responses API，以及 Bedrock 的 Converse、Invoke API 调用。官方还写明：数据在 AWS 边界内处理，不会与 Moonshot AI 共享，也不会用于训练该模型；推理请求始终启用零数据保留。上述数据与安全安排是 AWS 的产品政策说明。

开发者可按需求选择 global、us 或 in 等跨区域推理配置文件。文章还介绍了价格减半但可能更慢的 Flex 层，以及显式提示缓存。若已在 Bedrock 上使用 Kimi K3，官方称通常只需更换模型 ID 即可试用。

为何关注：已经把应用接在 Bedrock 上的团队，又多了一个可切换的长上下文编码和代理模型，而且不必单独再对接 Moonshot 的接口。
