# 谷歌扩充第八代 TPU：新增 8tx 保密推理与 8i Max 大上下文系统

[当日日报](../日报.md#tpu) · [首页](../../../../README.md#hl-tpu)

- **版块**: 科技
- **来源**: Google
- **来源标题**: Our newest TPUs: 8tx and 8i Max, built for the agentic era
- **来源链接**: https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/
- **原始发布时间**: JSON-LD datePublished 2026-11-09T13:00:00+00:00。正文可见 Nov 09, 2026
- **上海时间**: 2026-11-09 21:00
- **窗口**: 24小时内

## 摘要

谷歌官方博客宣布，在既有第八代 TPU 8t 与 8i 之外，再推出两套系统，使这一代在一年内达到四套。TPU 8tx 面向安全与保密推理，也可用于小规模训练。官方称它在硬件层保护使用中的敏感数据和模型权重，并采用与实时推理相同的低延迟 Boardfly 网络，延迟最多可比 TPU 8t 低约 2 倍，性能损失接近于零。因此可以在同一系统上做私有微调、蒸馏和强化学习，而不必在不同集群之间迁移敏感数据。

TPU 8i Max 把两枚低延迟 TPU 8i 芯片封装在一起。官方称它提供相当于 8i 两倍的算力、SRAM 和 HBM 带宽，用来应对大上下文和机柜密度。文中还介绍了 TorchTPU、TPU Sync、Cloud Pathways 和 GKE 动态切片等软件与编排更新。

页面末尾提到当天太平洋时间上午 9 点有一场广播。这里的发布时间采用 JSON-LD 的 datePublished，即 2026-11-09T13:00:00+00:00，早于那场广播。
