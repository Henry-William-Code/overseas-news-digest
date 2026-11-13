# Salesforce 开源发布 SOV-Transcribe-1 语音转写模型

[当日日报](../日报.md#salesforce-sov-transcribe-1) · [首页](../../../../README.md#salesforce-sov-transcribe-1)

- **版块**: AI
- **来源**: Hugging Face Blog (Salesforce)
- **来源链接**: https://huggingface.co/blog/salesforce-sovereign-intelligence/sov-transcribe-1
- **原始发布时间**: 页面写 Published November 12, 2026。JSON-LD datePublished 为 2026-11-12T16:43:41.057Z，换算为上海时间 11 月 13 日 00:43。页内另有 datetime=2026-11-11T23:26:17 的 time 元素，可能是较早的草稿或资源时间，不以该钟点为发布时间。来源记为 Salesforce，博文发布在 Hugging Face。
- **上海时间**: 2026-11-13 00:43
- **窗口**: 24小时内

## 摘要

Salesforce 的 Missionforce Sovereign AI 团队宣布开源 SOV-Transcribe-1。这是一款非流式自动语音识别的开权模型，采用 Apache 2.0 许可，总参数约 260 亿，激活约 40 亿。官方介绍，它面向电话号码、邮箱等实体，也面向口音和噪声环境，并支持用自然语言指令控制转写风格，以及用关键词做上下文偏置。权重已在 Hugging Face 发布。

文章给出的排名和误差率，包括截至 2026 年 11 月 12 日在 Artificial Analysis 的开权非流式语音转写中列第一、整体第七，以及 VoiceCodeBench 等结果，都是该公司引用的基准或自己的评测，不是独立审计。

为何关注：对企业想在自有基础设施上做通话转写或语音智能体的团队，这是又一个可自行部署的开权选项；具体质量仍需用自己的音频复查厂商榜单。
