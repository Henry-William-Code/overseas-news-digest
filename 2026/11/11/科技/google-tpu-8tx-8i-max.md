# Google 推出第八代 TPU 新系统 8tx 与 8i Max

[当日日报](../日报.md#hl-tpu) · [首页](../../../../README.md#hl-tpu)

- **版块**: 科技
- **来源**: Google
- **来源链接**: https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/
- **原始发布时间**: meta published_time / JSON-LD datePublished 为 2026-11-09T13:00:00+00:00。正文日期行为 Nov 09, 2026。
- **上海时间**: 2026-11-09 21:00
- **窗口**: 48小时内

## 摘要

Google 宣布在第八代 TPU 组合中新增两套系统：面向安全与机密推理（也适用于小规模训练）的 TPU 8tx，以及面向超大上下文、追求机柜计算密度的 TPU 8i Max。公司称这是其首次在同一年推出四套 TPU 系统，前两套是今年 4 月 Cloud Next 上的 8t（训练）和 8i（实时推理）。

官方介绍，8tx 与 8t 使用相同硅片，并搭配第 5 代 AMD EPYC 主机，把安全做到硬件层，使敏感数据和模型权重在使用中仍保持保护与隔离；相较 TPU 8t，延迟最高可降低约 2 倍。8i Max 则把两颗低延迟 8i 芯片封装在一起，官方称可提供相对 8i 两倍的计算、SRAM 和 HBM 带宽，并在原有机柜占地内放入更多硅片。稿件还谈到开源 TorchTPU、推理与代理基准，以及 Cloud Pathways、GKE 动态切片等软件，但这些是配套软件进展，不等同于芯片本身的第三方实测。
