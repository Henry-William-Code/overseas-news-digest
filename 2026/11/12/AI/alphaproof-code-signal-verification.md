# DeepMind 介绍 AlphaProof Code：用形式化方法验证 Signal 协议核心代码的关键安全属性

[当日日报](../日报.md#hl-alphaproof) · [首页](../../../../README.md#hl-alphaproof)

- **版块**: AI
- **来源**: Google DeepMind
- **来源标题**: Introducing AlphaProof Code: a breakthrough in verifying complex software at depth
- **来源链接**: https://deepmind.google/blog/introducing-alphaproof-code/
- **原始发布时间**: 已打开 DeepMind 官方博客。页面可见日期为 November 10, 2026。meta article:published_time 与 JSON-LD datePublished 均为 2026-11-10T12:00:00+00:00，dateModified 为 2026-11-10T13:17:48.367397+00:00。12:00:00+00:00 更像按日占位，不当作真实钟点，故只保留日期。
- **上海时间**: 2026-11-10（官方页面日期为 November 10, 2026；meta 与 JSON-LD 给出 12:00:00+00:00，更像按日占位，不当作真实钟点）
- **窗口**: 48小时内

## 摘要

DeepMind 介绍了新的智能体框架 AlphaProof Code，并称研究人员在人类专家指导下，用它对数十亿私人通讯所依赖的 Signal 协议核心密码学代码，就其关键安全属性做了形式化验证。官方把这称为首次以这一深度用 AI 验证广泛部署的密码协议，也是首次以任何方法验证这类已广泛部署协议的实现；这些定位来自公司陈述。

官方说，人类专家与模型先把安全目标写成形式化规范并经人工审阅，再由 Gemini Carbon 驱动的智能体完成证明，生成逾 600 万行 Lean 代码；智能体随后审计证明，并把约 1% 的代码标出供人工复核，其余由 Lean 自动检查。公司称整个验证过程用了四周。为检验系统能否区分正确与有缺陷的代码，研究人员把两个此前已修复的已知缺陷重新放入隔离版本，系统均给出了该有缺陷版本不安全的机器检查证明。

需要区分范围：这是对 Signal 协议核心密码学实现之关键属性的验证，不是对整个 Signal 应用程序的验证。官方说，在所考察的部分中没有发现新的漏洞，并正在开源相关形式化验证产物。Signal 首席技术官 Ehren Kret 在官方稿中表示，先前的形式化验证多集中在较小范围，此次方法带来了明显扩展。

为何关注：形式化验证一直被认为费时费力，这次展示的是 AI 辅助下对真实、广泛使用的密码实现做更深检查的一次尝试，但其覆盖范围仍有边界，也还不是面向所有软件的通用产品。
