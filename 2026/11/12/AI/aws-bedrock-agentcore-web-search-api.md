# Amazon Bedrock AgentCore 的网页搜索 API 已一般可用

[当日日报](../日报.md#aws-bedrock-agentcore-web-search-api) · [首页](../../../../README.md#aws-bedrock-agentcore-web-search-api)

- **版块**: AI
- **来源**: Amazon Web Services
- **来源标题**: Amazon Bedrock AgentCore now offers a Web Search API
- **来源链接**: https://aws.amazon.com/about-aws/whats-new/2026/11/amazon-bedrock-agentcore-web-search-api/
- **原始发布时间**: 页面可见 Posted on: Nov 10, 2026；内嵌字段 postDateTime="2026-11-10T00:00:00Z"。AWS What’s New 正文只写日期。postDateTime 为午夜 00:00:00Z，按规则视为日期占位，不作为真实钟点，也不换算成已确认的上海时刻。本条按 48 小时窗口收入。
- **上海时间**: 2026-11-10（官方仅标注日期；页面另有 00:00:00Z 占位时刻，不采用）
- **窗口**: 48小时内（官方仅标注日期；页面另有 00:00:00Z 占位时刻，不采用）

## 摘要

AWS 宣布，Amazon Bedrock AgentCore 上的 Web Search API 已一般可用。官方说明，网页搜索此前已经作为 MCP 工具通过 AgentCore Gateway 提供；新的 InvokeWebSearch API 让应用、自定义代理循环和数据管道用一次 API 调用即可拿到搜索结果，而不必再额外创建网关资源。

该接口返回由 Amazon 自行运营的网页索引给出的排序结果。官方称，每条结果包含文本摘录，并在可用时附上标题、网址和发布时间；请求还可按域名和发布时间过滤。调用可通过 AWS SDK 或 CLI 进行，使用 IAM 鉴权，也支持经 PrivateLink 从 VPC 访问，并把请求记录为 CloudTrail 数据事件。

定价为每 1000 次查询 7 美元，官方称与通过 AgentCore Gateway 使用网页搜索的费率相同，且不含网关费用。目前开放区域包括美国东部（弗吉尼亚北部、俄亥俄）、美国西部（俄勒冈）、亚太（悉尼、东京）和欧洲（爱尔兰）。

为何关注：做代理应用的人如果只是想让模型查一下近期公开网页，现在可以少搭一层网关，按查询次数付费即可。
