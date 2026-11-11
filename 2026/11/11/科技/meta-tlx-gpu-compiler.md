# Meta 介绍生产级 GPU 编译扩展 TLX，用于推荐模型与大模型预训练

[当日日报](../日报.md#meta-tlx-gpu-compiler) · [首页](../../../../README.md#meta-tlx-gpu-compiler)

- **版块**: 科技
- **来源**: Meta Engineering
- **来源标题**: How We Built TLX: A Hardware-Native GPU Compiler for Production ML at Scale
- **来源链接**: https://engineering.fb.com/2026/11/10/open-source/tlx-a-hardware-native-gpu-compiler-for-production-ml/
- **原始发布时间**: 已打开Meta Engineering官网。JSON-LD与meta article:published_time均为2026-11-10T16:59:31+00:00。页面另有一处article:modified_time为2026-11-09T23:33:59+00:00，早于发布时刻，更像草稿或系统时间，本稿采用datePublished。
- **上海时间**: 2026-11-11 00:59
- **窗口**: 24小时内

## 摘要

Meta 工程博客详细介绍了 Triton Low-Level Extensions（TLX），这是在 Triton 上增加的一层执行编排扩展，用于在保留 Python 与自动调优的同时，显式管理现代 GPU 上的 warp group、异步数据搬运、张量内存和集群级协同。文章称 TLX 已在 Meta 生产环境运行数月，覆盖推荐模型训练与推理，以及大规模大语言模型预训练，并支持 NVIDIA 与 AMD GPU。

文中给出三组内部案例，包括广告生成式模型训练在数千张 Blackwell GPU 上达到约 20%–25% 的端到端 MFU、推荐推理中的核内广播优化，以及专家并行预训练里的分布式 grouped GEMM。这是一篇生产实践与编程模型说明，正文重点不是宣布面向公众的新产品上线，也未在文中把「今日开源」作为独立发布点来表述。

文中的性能数字是公司内部案例，不是独立复核结论。
