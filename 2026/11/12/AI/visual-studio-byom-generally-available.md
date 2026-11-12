# Visual Studio 正式提供「自带模型」，可不登录 GitHub 使用自有或本地接口

[当日日报](../日报.md#visual-studio-byom-generally-available) · [首页](../../../../README.md#visual-studio-byom-generally-available)

- **版块**: AI
- **来源**: Visual Studio Blog
- **来源标题**: Bring Your Own Model is now generally available in Visual Studio
- **来源链接**: https://devblogs.microsoft.com/visualstudio/bring-your-own-model-is-now-generally-available-in-visual-studio/
- **原始发布时间**: 已打开 Microsoft Visual Studio 官方博客。可见日期为 November 11th, 2026。meta article:published_time 与 JSON-LD datePublished 均为 2026-11-11T17:00:48+00:00。按该带时区时间换算上海时间。
- **上海时间**: 2026-11-12 01:00
- **窗口**: 24小时内

## 摘要

微软 Visual Studio 博客宣布，Bring Your Own Model（BYOM）已在 Visual Studio 18.12 正式可用。用户可把自有托管模型、供应商 API 密钥，或本机运行的模型接入 Visual Studio，而不必离开这套开发环境。

此次更新支持为同一供应商保存多套配置并分别命名，新增面向 OpenAI 兼容服务和本地模型的自定义端点，可选择 Completions、Responses 或 Anthropic Messages 等接口格式，并改进了代理支持。官方写明，不需要登录 GitHub；只要模型端点可达且满足认证要求，也可在隔离网络里使用内部或本地模型。管理员可通过组织策略开启或关闭 BYOM。若界面里看不到「添加模型供应商」，可能是管理员已关闭该功能。
