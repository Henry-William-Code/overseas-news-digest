# Git 项目发布 2.56.1 等修复版本，修补六个安全漏洞

[当日日报](../日报.md#git-security-vulnerabilities-2-56-1) · [首页](../../../../README.md#git-security-vulnerabilities-2-56-1)

- **版块**: 科技
- **来源**: GitHub Blog
- **来源标题**: Git security vulnerabilities announced
- **来源链接**: https://github.blog/open-source/git/git-security-vulnerabilities-announced-7/
- **原始发布时间**: 已打开 GitHub 官方博客。可见日期为 November 10, 2026。meta article:published_time 与 JSON-LD datePublished 为 2026-11-10T18:00:00+00:00（同时给出 2026-11-10T10:00:00-08:00），dateModified 为 2026-11-10T19:02:20+00:00。按带时区的首次发布时间换算上海时间。
- **上海时间**: 2026-11-11 02:00
- **窗口**: 48小时内

## 摘要

GitHub 博客发布 Git 项目的安全更新说明：新版本修复六个安全漏洞，涉及递归克隆、引用处理、合并、二进制补丁和导入等环节，其中包括在递归克隆恶意仓库时可能执行代码、写入非预期文件，以及处理合并或二进制补丁时的内存损坏。

修复已包含在 Git 2.56.1 中，并回溯到 2.55.1、2.54.1、2.53.1、2.52.1、2.51.3 和 2.50.2。官方建议更新到 2.56.1 或自己所用维护分支的修补版，同时更新捆绑了 Git 的应用程序。GitHub 称已在 github.com 及相关云服务部署修复，并列出了 GitHub Enterprise Server 的对应更新版本。若暂时无法升级，官方建议只从受信任的服务器克隆，并避免对不受信任的仓库做递归克隆，但这些做法不能替代安装修补。
