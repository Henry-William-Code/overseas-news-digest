# Claude Code 2.1.323 增加实验性 Code Mode，可用 JavaScript 调用工具

[当日日报](../日报.md#hl-cc-codemode) · [首页](../../../../README.md#hl-cc-codemode)

- **版块**: AI
- **来源**: Claude Code GitHub Releases
- **来源链接**: https://github.com/anthropics/claude-code/releases/tag/v2.1.323
- **原始发布时间**: 时间取自 GitHub API 对该正式版（prerelease=false，draft=false）的 published_at：2026-11-12T22:12:13Z；created_at 为 2026-11-12T22:11:53Z。换算为上海时间 11 月 13 日 06:12。发布说明中的文档链接 https://code.claude.com/docs/en/code-mode 在核验时返回 404，因此不以该文档页为来源，只依据已发布的官方 release notes。
- **上海时间**: 2026-11-13 06:12
- **窗口**: 24小时内

## 摘要

Anthropic 于 11 月 12 日发布 Claude Code 正式版 v2.1.323。发布说明称，新增的 Code Mode 是实验性功能，需要主动打开：Claude 会编写 JavaScript 来调用它的工具。个人可以打开或关闭，组织也可以统一关掉。

同一版本还在 plugin.json 中加入 engines["claude-code"] 的版本范围约束。超出范围的插件不会被安装、更新或加载。claude plugin validate 也增加了 TypeScript hooks 的类型检查等插件校验。

其余大量条目是权限、沙箱、后台会话登录和终端显示方面的修复，不在这里逐条展开。Code Mode 的专门文档页返回 404，细节只以这条 GitHub 发布说明为准。

为何关注：这是本窗口内 Claude Code 的实际产品更新，但 Code Mode 仍是实验性选择加入功能，组织可以关闭；不宜理解成默认工作方式已改变。
