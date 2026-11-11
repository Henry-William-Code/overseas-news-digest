# DeepMind 发布 Gemini Robotics 2.5，奔驰工厂零件分拣试点成功率约 96%

[当日日报](../日报.md#gemini-robotics-2-5) · [首页](../../../../README.md#gemini-robotics-2-5)

- **版块**: AI
- **来源**: Google DeepMind
- **来源标题**: Gemini Robotics 2.5: Accelerating Physical Intelligence
- **来源链接**: https://deepmind.google/blog/gemini-robotics-2-5-accelerates-real-world-physical-intelligence/
- **原始发布时间**: 已打开DeepMind官方博客。页面meta property=article:published_time为2026-11-10T15:00:00+00:00；正文可见日期为November 10, 2026。
- **上海时间**: 2026-11-10 23:00
- **窗口**: 24小时内

## 摘要

DeepMind 发布视觉-语言-动作模型 Gemini Robotics 2.5，称其在技能广度、可靠性和安全性上有提升，并开始向机器人合作伙伴推送。官方说该模型在 200 多项任务中评估，相较此前基线，成功率按任务类型提高 30% 到 100%，完成速度提高 20% 到 30%，覆盖工具使用、柔性物体操作和精细抓取等。

在与 Apptronik、梅赛德斯-奔驰的概念验证中，Apollo 2 人形机器人在匈牙利凯奇凯梅特和德国辛德芬根的生产线上做汽车零件配盘，成功率约 96%。安全方面，模型用推理时引导避开危险，官方称在障碍物附近安全完成任务提高 33%，在人员附近提高 43%。

DeepMind 同时开源机器人越狱测试基准 ASIMOV-Jailbreak，并称 Gemini 4 Argon 的越狱抵抗率为 99.5%，高于此前基线 Gemini Robotics ER 2 的 82%。

2.5 把「看得懂指令」和「把手伸出去做事」拆成体现推理模型与动作模型的配合，并强调可以适配不同机器人形态，包括 Apollo 2 和双指夹爪平台。工厂试点做的是重复性很高的配盘：从料箱抓取金属支架并按顺序放入托盘。96% 的成功率来自官方披露的概念验证，原文把它称为迈向工业应用的进展，而不是已经可以大规模替换产线工人。

安全部分同样需要按研究/试点阶段来读。新的障碍规避和开源越狱基准说明 DeepMind 在为更少结构化的环境做准备，但 Gemini Robotics 2.5 并未宣布对公众通用开放。致谢中点名的合作方包括 Agile、Apptronik 和梅赛德斯-奔驰。

这是工业场景里的概念验证，不是面向普通消费者的通用机器人产品；官方也写明目前是向合作伙伴滚动提供。

上述成功率和安全比例来自官方披露，不是独立复核结论。
