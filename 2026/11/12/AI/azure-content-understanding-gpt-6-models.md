# Azure Content Understanding 新增 GPT-5.6、GPT-6 和 GPT-6.1 可选模型

[当日日报](../日报.md#azure-content-understanding-gpt-6-models) · [首页](../../../../README.md#azure-content-understanding-gpt-6-models)

- **版块**: AI
- **来源**: Microsoft
- **来源标题**: Content Understanding adds GPT-5.6, GPT-6, and GPT-6.1: Choose the right model for your workload
- **来源链接**: https://devblogs.microsoft.com/foundry/content-understanding-adds-gpt-5-6-gpt-6-and-gpt-6-1-choose-the-right-model-for-your-workload/
- **原始发布时间**: 可见日期 November 11th, 2026；meta article:published_time 与 JSON-LD datePublished 均为 2026-11-11T18:24:28+00:00；dateModified=2026-11-11T19:40:51+00:00。Microsoft Foundry Blog 的 article:published_time 与 JSON-LD datePublished 均为带显式 +00:00 的非整点时间戳，不像午夜或正午占位。
- **上海时间**: 2026-11-12 02:24
- **窗口**: 24小时内

## 摘要

微软在 Foundry 博客宣布，Azure Content Understanding 现在除原有 GPT-5 系列外，还支持 GPT-5.6、GPT-6 和 GPT-6.1 模型家族，可用于文档、文本、语音和视频工作流。官方把选模型比作调音台，认为不是所有任务都需要上最贵、最强的配置。

对标准文档抽取，微软建议先从 GPT-6.1 Sol 起步；更在意 token 成本时再测试 GPT-6 Luna；只有在剩余错误会带来较高复核或下游损失时，再试验 GPT-6 Astra。文中给出的抽取准确率、分段 F1、视频 Generation F1，以及 Astra 在文档测试中补全 token 费用约为 Sol 五倍等数字，都来自微软自己的评测，需要视为公司陈述，且官方也写明结果会随任务和内容变化很大。

文章还建议：在升级到更贵模型之前，可以先给分析器补充少量已标注示例；文档、视频、语音应分别比较，不要把不同任务的百分比加总成单一排行。团队可在 Content Understanding Studio 或 REST API 里对同一批材料只更换模型部署，再比较质量、延迟和用量。

为何关注：已经在用 Azure 做票据、合同或音视频抽取的团队，多了几档 GPT-6 系列选项，但官方自己也提醒要按自己的材料实测，而不是只看榜单。
