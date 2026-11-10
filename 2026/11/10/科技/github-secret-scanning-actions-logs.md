# GitHub 密钥扫描开始检查 Actions 工作流日志（公开预览）

[当日日报](../日报.md#github-secrets) · [首页](../../../../README.md#keji)

- **版块**: 科技
- **来源**: GitHub
- **来源标题**: Secret scanning detects secrets in GitHub Actions workflow logs
- **来源链接**: https://github.blog/changelog/2026-11-09-secret-scanning-detects-secrets-in-github-actions-workflow-logs/
- **原始发布时间**: JSON-LD datePublished 2026-11-09T09:01:37+00:00（等同 2026-11-09T01:01:37-08:00）。页面可见日期为 November 9, 2026
- **上海时间**: 2026-11-09 17:01
- **窗口**: 48小时内

## 摘要

GitHub Changelog 宣布，密钥扫描除议题、wiki、讨论和拉取请求外，也可以扫描 GitHub Actions 工作流日志。功能处于公开预览。工作流运行完成后，GitHub 按提供商模式扫描日志。发现项出现在仓库的密钥扫描告警列表里，并链回对应日志。对受支持的密钥类型会做有效性检查。日志随后被删除，告警仍保留。

预览面向启用了 GitHub Secret Protection 或 GitHub Advanced Security 的 GitHub Enterprise Cloud 企业，包括 GHE.com 上的数据驻留。企业所有者需要在企业策略里开启。默认关闭，而且只作用于已经启用密钥扫描的仓库。

启用后只扫描之后完成的运行，不回扫旧日志。通用模式、自定义模式、AI 检出的密钥，以及已经被 Actions 掩盖的密钥，预览期间不会被检出。预览阶段这类告警也不发送通知，需要直接查看告警列表。
