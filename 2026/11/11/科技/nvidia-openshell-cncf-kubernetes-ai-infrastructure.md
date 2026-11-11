# 英伟达向 CNCF 捐赠 OpenShell，并发布面向 Kubernetes 的 AI 基础设施组件

[当日日报](../日报.md#nvidia-openshell-cncf-kubernetes-ai-infrastructure) · [首页](../../../../README.md#nvidia-openshell-cncf-kubernetes-ai-infrastructure)

- **版块**: 科技
- **来源**: NVIDIA Blog
- **来源链接**: https://blogs.nvidia.com/blog/open-source-openshell-infrastructure/
- **原始发布时间**: meta / JSON-LD article:published_time 为 2026-11-10T16:00:03+00:00，合上海时间 2026-11-11 00:00。article:modified_time 为 2026-11-10T19:19:20+00:00。
- **上海时间**: 2026-11-11 00:00
- **窗口**: 24小时内

## 摘要

英伟达在 KubeCon 期间宣布，将用于约束和治理自主代理的开源运行时 NVIDIA OpenShell 捐给云原生计算基金会（CNCF），成为 Sandbox 项目。公司还表示参与由 Google 发起、同样进入 CNCF Sandbox 的 Agent Substrate，并为该框架与 NVIDIA Dynamo、KAI Scheduler 的配合提供支持。官方称 OpenShell 可对代理使用工具、调用推理服务和执行任务施加确定性策略，并允许对接现有计算、推理、凭证和监控系统。

与此同时，英伟达为 DSX AI Factory Platform 新增组件：现已公开预览的 NVIDIA Kubernetes Engine（NVKE）和 NVIDIA Kubernetes Recipes（NVKR），以及开源的 NVIDIA Snapshot。官方称 Snapshot 可在数秒内恢复已做检查点的副本，而不必重新加载模型或预热。设计伙伴 Crusoe 在自身云上测试 GLM-5.3 时，称工作负载就绪时间从约 8 分钟降至 31 秒；Saturn Cloud 则称将 vLLM 启动时间从 2 至 8.5 分钟降至 6 秒和 34 秒。上述数字来自英伟达稿件中的伙伴测试陈述。
