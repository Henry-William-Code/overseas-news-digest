# Claude Code 的“不再询问”可能把密钥写进后来被公开的设置文件

[当日日报](../日报.md#claude-code) · [首页](../../../../README.md#ai)

- **版块**: AI
- **来源**: Ars Technica
- **来源标题**: Claude Code is accidentally exposing secrets all over GitHub
- **来源链接**: https://arstechnica.com/ai/2026/11/claude-code-settings-files-expose-thousands-of-secrets-on-github/
- **原始发布时间**: 2026-11-09 17:24 UTC
- **上海时间**: 2026-11-10 01:24
- **窗口**: 24小时内

## 摘要

Ars Technica 报道，安全公司 Apiiro 在公开 GitHub 仓库的 Claude Code 设置文件里发现了数以千计的密钥，包括数据库密码、API 令牌和 root 登录信息。触发点是用户批准自动执行命令时选择不再询问。这个选择会写成本地设置文件里的规则，命令原文有时连同其中的敏感内容一起被保存。

Anthropic 的文档说，该设置文件会被加入全局 gitignore。Ars 写明，这不等于仓库级别一定忽略它。Apiiro 还称，不少情况下工具会在用户没有另行确认时提交这个文件。文件留在本机时风险有限；一旦进入公开仓库，密钥就暴露了。
