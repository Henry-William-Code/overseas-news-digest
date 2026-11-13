# AWS 与 RadixArk 推出 SGLang-Neuron，可在 Trainium 上按 SGLang 接口提供模型服务

[当日日报](../日报.md#aws-sglang-neuron-trainium) · [首页](../../../../README.md#aws-sglang-neuron-trainium)

- **版块**: AI
- **来源**: AWS Machine Learning Blog
- **来源链接**: https://aws.amazon.com/blogs/machine-learning/deploy-frontier-ai-models-on-aws-trainium-with-sglang-neuron/
- **原始发布时间**: AWS 博客的 article:published_time 与 time 元素均为 2026-11-12T14:03:34-08:00（太平洋标准时间，UTC-8），换算为上海时间 11 月 13 日 06:03。正文署名为 12 NOV 2026。
- **上海时间**: 2026-11-13 06:03
- **窗口**: 24小时内

## 摘要

Amazon 宣布 SGLang-Neuron 已公开发布，可以通过 AWS Deep Learning Container 获取，由 RadixArk 与 Annapurna Labs 合作推出。开发者可以在 AWS Trainium 上沿用现有的 SGLang 服务接口来提供模型，并生成强化学习的 rollout。

服务启动后仍使用同样的生成 API。底层走原生 PyTorch，并用仓库外插件把 Trainium 支持与 SGLang 核心拆开。设置 SGLANG_PLATFORM=neuron 即可选用这一平台。插件负责模型、注意力、MoE 和计算图运行，也支持预填充与解码分离，通过 NIXL 经 Elastic Fabric Adapter 传递 KV cache。

文章给出了在 Trainium3 的 EC2 实例上，用 pytorch-inference-sglang-neuronx 容器启动并调用 openai/gpt-oss-120b 的示例，并指向入门指南和代码库文档。

为何关注：如果团队已经在用 SGLang 做推理或强化学习，这提供了一条不必重写服务栈、把工作放到 Trainium 上的官方路径。
