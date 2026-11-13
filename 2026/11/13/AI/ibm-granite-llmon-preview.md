# IBM 发布实验性 LLMON 标记语言及 Granite 4.1 预览模型

[当日日报](../日报.md#ibm-granite-llmon-preview) · [首页](../../../../README.md#ibm-granite-llmon-preview)

- **版块**: AI
- **来源**: Hugging Face Blog (IBM Granite)
- **来源链接**: https://huggingface.co/blog/ibm-granite/llmon-an-llm-native-markup-language-now-in-granite
- **原始发布时间**: 页面写 Published November 12, 2026。JSON-LD datePublished 为 2026-11-12T19:07:35.672Z，换算为上海时间 11 月 13 日 03:07。页内另有 time 元素 datetime=2026-11-12T18:55:40，与 datePublished 接近，采用 JSON-LD。来源记为 IBM，博文发布在 Hugging Face。
- **上海时间**: 2026-11-13 03:07
- **窗口**: 24小时内

## 摘要

IBM Granite 团队在 Hugging Face 博客宣布 LLMON（LLM Object Notation）。这是一种面向语言模型的标记格式，用保留的特殊 token 把指令、数据、约束和执行块分开，想把上下文里的结构说清楚。同时发布的两款实验性预览模型，从 Granite 4.1 基座衍生而来：granite-4.1-3b-LLMON-preview 与 granite-4.1-8b-LLMON-preview，工具库和示例开源。

官方称，在 OPI 等针对静态间接提示注入的基准上，LLMON 模型大多会忽略藏在用户数据里的指令，攻击成功率可以降到接近零，通用能力则与 Granite 4.1 Instruct 大致持平。这些抗注入和能力数字都是 IBM 自己的评估。文章写明，这是 experimental preview，可供探索和评测，不适合生产环境。

为何关注：把指令和数据在格式上分开，是应对间接提示注入的一条技术路线；但目前仍是预览，且主要针对静态注入，作者也提到自适应、多轮攻击仍在研究。
