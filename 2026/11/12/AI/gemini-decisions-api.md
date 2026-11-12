# 谷歌推出 Gemini Decisions API，一次可评估最多 1000 个封闭式问题

[当日日报](../日报.md#hl-decisions) · [首页](../../../../README.md#hl-decisions)

- **版块**: AI
- **来源**: Google
- **来源标题**: Gemini Decisions API: Fast, calibrated multimodal decisions
- **来源链接**: https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/
- **原始发布时间**: 已打开谷歌官方博客。可见日期为 Nov 11, 2026。页面 meta article:published_time 为 2026-11-11，JSON-LD datePublished 为 2026-11-11T18:00:00+00:00，dateModified 为 2026-11-11T18:15:48.035680+00:00。18:00 为带时区的整点发布时间，不是午夜占位，按该发布时间换算上海时间。
- **上海时间**: 2026-11-12 02:00
- **窗口**: 24小时内

## 摘要

谷歌宣布推出 Gemini Decisions API，并由新模型 Gemini Decision 1（`gemini-decision-1`）提供支持，已在 Google AI Studio 的 Gemini API 中开放。官方说，它面向工具选择、策略检查、模型路由和内容打分等有明确选项的判断：一次可提交同一段多模态输入（文本、图像、音频、视频和 PDF，最长 256K token），并附上最多 1000 个相互独立的问题。

和逐 token 生成答案不同，公司称该模型在一次前向计算中给候选选项打分，返回概率和置信度；端到端延迟为 150–250 毫秒，定价为每百万输入 token 0.10 美元，输出 token 不计费。问题类型包括是否判断、2 到 255 项的选择题，以及有序量表打分。官方列举的内部用法包括 Gemini Notebook 的实时模型路由、Stitch 里的快速线框迭代，以及搜索里对 MCP 工具的安全检查，这些都是公司自身陈述。

基准对比和「比 Gemini 3.5 Flash-Lite 便宜近 5 倍」等说法同样来自谷歌，不是独立复核结论。目前可在 AI Studio 免费试用层做原型；文中写明，Google Cloud 上的 Gemini 支持即将推出。

为何关注：这是一条面向开发者的新接口，把「在固定选项里快速做判断」从生成式对话里单独拆出来，适合路由、审核和打分，而不是再发布一个通用聊天模型。
