# Amazon Bedrock AgentCore 下一代运行时成为新建运行时的默认选项

[当日日报](../日报.md#aws-agentcore-runtime-next-gen) · [首页](../../../../README.md#aws-agentcore-runtime-next-gen)

- **版块**: AI
- **来源**: AWS Machine Learning Blog
- **来源链接**: https://aws.amazon.com/blogs/machine-learning/run-agents-securely-and-efficiently-with-the-next-generation-agentcore-runtime/
- **原始发布时间**: AWS 博客的 article:published_time 与 time 元素均为 2026-11-12T09:59:59-08:00。11 月为太平洋标准时间（UTC-8），换算为上海时间 11 月 13 日 01:59。同期 What’s New 稿标注 Posted on: Nov 12, 2026，其 datePublished 为 2026-11-12T05:00:00Z，更像批量占位，因此条目时间以这篇博客为准。这与已刊的 AgentCore Web Search API 正式商用不是同一事件。
- **上海时间**: 2026-11-13 01:59
- **窗口**: 24小时内

## 摘要

AWS 宣布更新 Amazon Bedrock AgentCore 的运行时。每个会话仍在独立的 Firecracker 微虚拟机里运行。官方称，新版会话启动最快可以到大约 15 倍，计算规格最高扩大到 4 倍（8 个 vCPU、32 GB 内存），并支持最大 10 GB 的容器镜像。What’s New 还给出公司自己的测试：在 2 GB 镜像上，P75 启动时间从 29.7 秒降到 2 秒以内。

运行时会在智能体空闲后缩到零，并在内存释放后的数分钟内回收。官方称，多轮会话最多可以减少大约 68% 的内存用量。会话还可以动态挂载文件系统，例如带 FUSE 的 S3，把数据留在同一信任边界内。What’s New 写明：自即日起，所列多个区域里新建的 runtime 默认使用这一代；已经存在的 runtime 仍留在旧版本，直到把 platformVersion 设为 V2。

上述性能和用量数字都是 AWS 或其客户的表述，不是独立审计。这也不是此前已经报道的 AgentCore Web Search API 正式商用。

为何关注：智能体要在生产里长时间跑代码、浏览器或本地模型，隔离、冷启动和按实际使用计费往往比模型本身更先成为瓶颈；现有工作负载不会自动升级，需要主动切到 V2。
