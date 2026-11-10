# 2026年11月10日 · 海外资讯日报

上海时间 **2026-11-10 18:35** 更新。独立新闻 **30** 条，12 个来源，其中 AI **10** 条。仅展示审核通过内容。

Cursor 公开更新日志最新仍是 11 月 6 日。DeepSeek 与 Grok Bot 本期时间窗内仍无新的官方产品更新。

[当日完整版](2026/11/10/日报.md) · [往期索引](ARCHIVE.md)

---

## 今日重点

五条展开。下面各栏是短读，重点条目在栏里只留一句。

<a id="hl-claude52"></a>

### 1. Anthropic 推出 Claude Fable 5.2，Mythos 5.2 先对核定机构开放

The Verge 报道，Anthropic 宣布两款新模型：Claude Fable 5.2 和 Claude Mythos 5.2。Fable 5.2 当天开放。Mythos 5.2 起初只给核定过的机构。公司称它们面向难度高的技术问题，编程、推理和视觉好于今年 9 月的 5.1，输出也更快。

Anthropic 还说，预发布测试里模型帮工程师完成了原本做不成的软件迁移，并在 30 小时内形式化了费马大定理的证明。这些是公司对测试的描述，不是独立复核过的结论。

发布：上海时间2026-11-10 03:00｜[The Verge](https://www.theverge.com/ai-artificial-intelligence/1030005/anthropic-claude-fable-mythos-5-2)  
[单篇档案](2026/11/10/AI/anthropic-claude-fable-mythos-5-2-the-verge.md)

---

<a id="hl-ember"></a>

### 2. Meta 发布轻量模型 Muse Ember，面向代理日常高并发执行

Meta 超级智能实验室在研究博客宣布 Muse Ember，称它是目前最小、效率最高的模型，面向代理整天重复的执行：工具调用、编码子任务、路由、抽取和长文档解析。模型标识为 muse-ember-1.0，已在 Muse Code 和 Meta Model API 上线。定价为每百万输入 token 0.10 美元、缓存输入 0.004 美元、输出 0.50 美元；超过 20 万 token 的更长提示另有更高价格。上下文窗口为 100 万 token，输出最长约 51.2 万 token。

官方写道，可与更大的 Muse Wonder 搭配：Wonder 负责规划，Ember 处理体量。文中引用 Artificial Analysis 等评测，也写明部分结果是内部评测；在 FrontierCode 2.0-AA 上，Ember 的分数低于 Claude Haiku 5.5。安全部分称，按 Meta 超级智能扩展框架评估后，它仍低于该框架的高风险阈值。

钟点以 TechCrunch 的 datePublished 2026-11-09T18:00:00+00:00 为准，合上海时间 2026-11-10 02:00。官方页可见日期是 November 9, 2026，JSON-LD 的午夜 UTC 更像日期占位。

发布：上海时间2026-11-10 02:00｜[Meta](https://research.meta.ai/blog/muse-ember)  
[单篇档案](2026/11/10/AI/meta-muse-ember.md)

---

<a id="hl-australia"></a>

### 3. 澳大利亚宣布将立法强制 AI 安全标准，并拟设专门监管机构

澳大利亚政府 11 月 10 日宣布，将通过澳大利亚 AI 标准立法，对希望在澳大利亚运营的前沿 AI 公司施加强制性安全与安保义务，并由拟新设的专门 AI 安全监管机构执行。该机构将与澳大利亚 AI 安全研究所合作。这是即将立法和拟设机构的官方宣布，不是法律已经生效。

官方列出的要求包括：在开发和部署各阶段维持安全控制、识别并管理严重风险、允许对模型做独立评估、迅速向澳大利亚政府强制通报事件、维护并公布安全与安保框架，以及随技术变化响应更新后的标准。监管机构可对未履行强制义务的公司处以显著处罚。

同日另一份总理府声明公布针对 OpenAI 智能体进入澳大利亚政府健康网站的快速审查。审查在今年 9 月 OpenAI 告知政府后启动，涉及包括 Medicare 统计报告服务门户在内的政府网站。政府称事件不可接受、披露不充分，接受审查的 18 项建议并已开始落实，其中包括强制报告、考虑修订刑法，以及加强事件响应。

发布：上海时间2026-11-10 10:22｜[澳大利亚总理府](https://www.pm.gov.au/media/new-australian-ai-safety-and-security-protections)  
[单篇档案](2026/11/10/AI/australia-ai-safety-standards-pm.md)

---

<a id="hl-tpu"></a>

### 4. 谷歌扩充第八代 TPU：新增 8tx 保密推理与 8i Max 大上下文系统

谷歌官方博客宣布，在既有第八代 TPU 8t 与 8i 之外，再推出两套系统，使这一代在一年内达到四套。TPU 8tx 面向安全与保密推理，也可用于小规模训练。官方称它在硬件层保护使用中的敏感数据和模型权重，并采用与实时推理相同的低延迟 Boardfly 网络，延迟最多可比 TPU 8t 低约 2 倍，性能损失接近于零。因此可以在同一系统上做私有微调、蒸馏和强化学习，而不必在不同集群之间迁移敏感数据。

TPU 8i Max 把两枚低延迟 TPU 8i 芯片封装在一起。官方称它提供相当于 8i 两倍的算力、SRAM 和 HBM 带宽，用来应对大上下文和机柜密度。文中还介绍了 TorchTPU、TPU Sync、Cloud Pathways 和 GKE 动态切片等软件与编排更新。页面末尾提到当天太平洋时间上午 9 点有一场广播；这里的发布时间采用 JSON-LD 的 datePublished，即 2026-11-09T13:00:00+00:00。

发布：上海时间2026-11-09 21:00｜[Google](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/)  
[单篇档案](2026/11/10/科技/google-tpu-8tx-8i-max.md)

---

<a id="hl-fda"></a>

### 5. 美国 FDA 要求所有 GLP-1 类药品更新标签，提示可能增加罕见眼病风险

美国 FDA 在 11 月 9 日的药品安全通讯里要求，所有 GLP-1 受体激动剂在“警告与注意事项”中加入非动脉炎性前部缺血性视神经病变（NAION）的信息。NAION 罕见，可导致一只眼急性、无痛的视力下降，包括永久性视力丧失。涉及的药品包括 Ozempic、Wegovy、Mounjaro、Zepbound 等。

这是“潜在增加的罕见 NAION 风险”，不是已经证实的因果关系。FDA 对 126 项随机对照试验的荟萃分析给出每 10 万人年 6.4 例，对照为 3.8 例；共 15 例可能的 NAION 事件，用药组 10 例、安慰剂 5 例。FDA 自己的 Sentinel 真实世界研究里，与 SGLT-2 抑制剂相比，风险增加没有统计学显著性（HR 1.19，95% CI 0.91–1.54）；与 DPP-4 抑制剂相比则观察到升高（HR 1.43，95% CI 1.02–2.01）。动物数据没有找出机制。不良事件报告因为危险因素和用药人群重叠，难以单独解释。CNBC 转述诺和诺德称，公司仍认为数据没有建立因果关系，并对药品的获益-风险状况保持信心。这是公司表态，不是 FDA 的结论。

发布：上海时间2026-11-09（官方仅标注日期，未给出具体时刻）｜[U.S. FDA](https://www.fda.gov/drugs/drug-safety-communications/fda-requires-safety-labeling-changes-glucagon-peptide-1-receptor-agonists-glp-1-ras-due-potential)  
[单篇档案](2026/11/10/健康/fda-glp1-naion-label.md)

---

## 栏目

[AI](#ai) · [科技](#keji) · [搞笑](#gaoxiao) · [健康](#jiankang) · [社会](#shehui) · [财经](#caijing) · [娱乐](#yule) · [体育](#tiyu) · [其他](#qita)

<a id="ai"></a>

## AI

### Anthropic 推出 Claude Fable 5.2，Mythos 5.2 先对核定机构开放

已在[今日重点](#hl-claude52)展开。The Verge 报道，Anthropic 当天推出 Claude Fable 5.2；Mythos 5.2 先只给核定过的机构。公司称编程、推理和视觉好于 5.1。物理和数学上的结果，是它自己的测试说法。

发布：上海时间2026-11-10 03:00｜[The Verge](https://www.theverge.com/ai-artificial-intelligence/1030005/anthropic-claude-fable-mythos-5-2)  
[单篇档案](2026/11/10/AI/anthropic-claude-fable-mythos-5-2-the-verge.md)

### Meta 发布轻量模型 Muse Ember，面向代理日常高并发执行

已在[今日重点](#hl-ember)展开。Meta 称 Muse Ember 已在 Muse Code 和 Meta Model API 上线，面向代理重复执行的高并发任务，并可与 Muse Wonder 搭配。

发布：上海时间2026-11-10 02:00｜[Meta](https://research.meta.ai/blog/muse-ember)  
[单篇档案](2026/11/10/AI/meta-muse-ember.md)

### 澳大利亚宣布将立法强制 AI 安全标准，并拟设专门监管机构

已在[今日重点](#hl-australia)展开。这是即将立法和拟设监管机构的宣布，法律尚未生效。

发布：上海时间2026-11-10 10:22｜[澳大利亚总理府](https://www.pm.gov.au/media/new-australian-ai-safety-and-security-protections)  
[单篇档案](2026/11/10/AI/australia-ai-safety-standards-pm.md)

### OpenAI 发布教育报告：学生已普遍用 AI 做作业，但指导明显落后

OpenAI 的教育报告引用 ThinkYoung：受访学生中 79% 表示曾用 AI 完成作业，只有 47% 表示有人教过如何使用。报告把这称为指导差距，并写明这些是早期经验，不是可以照搬的模式。

发布：上海时间2026-11-10（官方仅标注日期，未给出具体时刻）｜[OpenAI](https://openai.com/index/closing-ai-guidance-gap-education)  
[单篇档案](2026/11/10/AI/openai-education-guidance-gap.md)

### Medium 推出写作应用 TK，把 AI 助手直接做进编辑器

TechCrunch 报道，Medium 推出写作应用 TK。在编辑器里输入 “@TK” 即可调用 AI 助手。先上线网页版，桌面应用还在规划中。拥有 Medium 账户的用户可以免费使用。内容不加密。

发布：上海时间2026-11-10 00:12｜[TechCrunch](https://techcrunch.com/2026/11/09/mediums-new-tk-app-brings-ai-assistance-directly-into-the-writing-process/)  
[单篇档案](2026/11/10/AI/medium-tk-writing-app-techcrunch.md)

### ChatGPT Enterprise 进入 AWS Marketplace

OpenAI 称，ChatGPT Enterprise 已可在 AWS Marketplace 购买，账单走现有 AWS 账户。企业版包含 ChatGPT、Codex 和 dots。

发布：上海时间2026-11-10 03:00｜[OpenAI](https://openai.com/index/chatgpt-enterprise-aws-marketplace)  
[单篇档案](2026/11/10/AI/chatgpt-enterprise-aws-marketplace-openai.md)

### OpenAI 在研究环境部署 Control Room，用来叫停模型任务

OpenAI 说，研究用的模型任务已经接入 Control Room。决定叫停后，最迟约 35 秒内不再继续生成。对外服务的下线机制是另一套。

发布：上海时间2026-11-09 21:00｜[OpenAI](https://openai.com/index/control-room)  
[单篇档案](2026/11/10/AI/openai-control-room.md)

### Logic Pro 可以单次购买 49.99 美元的 Apple Intelligence 用量包

Logic Pro 已能以 49.99 美元一次买断额外的 Apple Intelligence 用量。未用完的额度按月结转，购买满 12 个月后过期。其他创意应用还没开这个入口。

发布：上海时间2026-11-10 03:09｜[The Verge](https://www.theverge.com/tech/1030084/apple-intelligence-usage-packs-ai-features-creator-studio-logic-pro)  
[单篇档案](2026/11/10/AI/apple-intelligence-usage-packs-the-verge.md)

### Instagram 在美国上线可用提示词做滤镜的 Effect Builder

Effect Builder 已向美国 18 岁以上用户开放。用文字描述滤镜，也可附参考图。滤镜要先过安全审核，才会出现在其他人的 Stories 里。

发布：上海时间2026-11-10 02:07｜[The Verge](https://www.theverge.com/tech/1030061/instagram-ai-effect-builder-filters)  
[单篇档案](2026/11/10/AI/instagram-effect-builder-the-verge.md)

### Claude Code 的“不再询问”可能把密钥写进后来被公开的设置文件

Ars Technica 援引 Apiiro：选择“不再询问”时，命令内容可能写进本地设置文件。这些文件已经出现在公开的 GitHub 仓库里，其中有数据库密码和 API 密钥。

发布：上海时间2026-11-10 01:24｜[Ars Technica](https://arstechnica.com/ai/2026/11/claude-code-settings-files-expose-thousands-of-secrets-on-github/)  
[单篇档案](2026/11/10/AI/claude-code-settings-secrets-arstechnica.md)

---

<a id="keji"></a>

## 科技

### 谷歌扩充第八代 TPU：新增 8tx 保密推理与 8i Max 大上下文系统

已在[今日重点](#hl-tpu)展开。谷歌在第八代 TPU 里增加 8tx 保密推理和 8i Max 大上下文两套系统。8t 与 8i 仍是这一代原有的两套。

发布：上海时间2026-11-09 21:00｜[Google](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/)  
[单篇档案](2026/11/10/科技/google-tpu-8tx-8i-max.md)

### GitHub 密钥扫描开始检查 Actions 工作流日志（公开预览）

GitHub 的密钥扫描开始检查 Actions 工作流日志，目前是公开预览，默认关闭。只扫描开启之后完成的运行，预览期间不发通知。通用模式、自定义模式和已被掩盖的密钥不会被检出。

发布：上海时间2026-11-09 17:01｜[GitHub](https://github.blog/changelog/2026-11-09-secret-scanning-detects-secrets-in-github-actions-workflow-logs/)  
[单篇档案](2026/11/10/科技/github-secret-scanning-actions-logs.md)

### 研究用电流噪声探测铜氧化物超导体，认为赝能隙与电子配对有关

Ars Technica 介绍《科学》上的一项实验。团队用扫描隧道显微镜测量铜氧化物 BSCCO 的散粒噪声，在赝能隙对应的能量上看到额外噪声；磁场最高约 6 特斯拉后，噪声回到接近单电子的水平。文章写明，这不能外推成室温超导，也还没排除其他结构与配对交织。

发布：上海时间2026-11-08 20:15｜[Ars Technica](https://arstechnica.com/science/2026/11/physicists-listened-to-electrical-noise-to-crack-a-superconductor-mystery/)  
[单篇档案](2026/11/10/科技/superconductor-shot-noise-ars.md)

### ESCAPADE 两艘探测器完成带动力的地球飞越，正在前往火星

NASA 说，两艘 ESCAPADE 探测器各自完成了一次带动力的地球飞越，现已在前往火星的路上。这是已经完成的飞越，不是发射预告。

发布：上海时间2026-11-10 00:01｜[NASA](https://science.nasa.gov/science-research/heliophysics/nasas-escapade-completes-powered-earth-flybys-now-en-route-to-mars/)  
[单篇档案](2026/11/10/科技/nasa-escapade-earth-flyby.md)

### 钱德拉望远镜称找到一颗巨恒星反复爆发的触发来源

NASA 的公开摘要说，天文学家用钱德拉 X 射线天文台，找到了一颗巨大且不稳定的恒星反复爆发的触发因素。摘要没有写出该因素的名称。

发布：上海时间2026-11-10 02:55｜[NASA](https://science.nasa.gov/missions/chandra/nasas-chandra-finds-source-of-stars-mysterious-outbursts/)  
[单篇档案](2026/11/10/科技/nasa-chandra-star-outbursts.md)

### SpaceX 发射副总裁称公司已是基础设施公司，猎鹰 9 走向退役

文章发于 11 月 9 日，记录的是上周 UP.Summit 上的发言。Kiko Dontchev 说公司本质上已是基础设施公司，猎鹰 9 正在走向退役。第 15 次星舰飞行仍是计划。

发布：上海时间2026-11-09 23:39｜[Ars Technica](https://arstechnica.com/space/2026/11/spacex-now-fundamentally-an-infrastructure-company-senior-official-says/)  
[单篇档案](2026/11/10/科技/spacex-infrastructure-company-arstechnica.md)

---

<a id="gaoxiao"></a>

## 搞笑

### 开发者用讽刺脚本 Ram-Altman 拿电脑空闲内存开萨姆·奥特曼的玩笑

Ars Technica 介绍开发者 Iain Kay 的恶搞脚本 Ram-Altman：Linux 若报告超过 10% 的内存可分配，脚本每天最多生成一封拿萨姆·奥特曼开玩笑的邮件。仓库没有真实邮箱。报道建议只用 dry-run。脚本量的是某一时刻的空闲容量，不是内存被占用的时间比例。

发布：上海时间2026-11-10 04:49｜[Ars Technica](https://arstechnica.com/gadgets/2026/11/a-sam-altman-parody-offers-an-amusing-lesson-in-memory-management/)  
[单篇档案](2026/11/10/搞笑/ram-altman-memory-parody-ars.md)

---

<a id="jiankang"></a>

## 健康

### 美国 FDA 要求所有 GLP-1 类药品更新标签，提示可能增加罕见眼病风险

已在[今日重点](#hl-fda)展开。这是潜在增加的罕见 NAION 风险，不是已经证实的因果关系。官方数字是每 10 万人年 6.4 对 3.8，共 15 例事件。

发布：上海时间2026-11-09（官方仅标注日期，未给出具体时刻）｜[U.S. FDA](https://www.fda.gov/drugs/drug-safety-communications/fda-requires-safety-labeling-changes-glucagon-peptide-1-receptor-agonists-glp-1-ras-due-potential)  
[单篇档案](2026/11/10/健康/fda-glp1-naion-label.md)

### 泽西岛水务初步试验：一处站点 PFAS 浓度约降 30%，完整结论仍需一年

BBC 报道，泽西岛水务首席执行官 Helier Smith 说，Augres 水处理厂的试验里 PFAS 浓度大约降了 30%。结果是初步的。完整中试大约需要 200 万英镑、12 个月，最终报告计划在 2027 年底公布。报道提到的既往健康关联，不是这次试验的新结论。

发布：上海时间2026-11-09 19:40｜[BBC](https://www.bbc.com/news/articles/cxm232l34rqgo)  
[单篇档案](2026/11/10/健康/jersey-pfas-trial-bbc.md)

### 僵人综合征的 CAR-T 试验出现早期改善，尚不知能否维持

《卫报》报道，梅奥诊所在试验中用 CAR-T 治疗僵人综合征，部分患者恢复了日常活动。结果刊在《JAMA Neurology》。研究者说还不知道改善能否持续，也不是已获批疗法。

发布：上海时间2026-11-10 00:42｜[The Guardian](https://www.theguardian.com/science/2026/nov/09/medical-breakthrough-offers-hope-to-people-with-same-stiff-person-syndrome-as-celine-dion)  
[单篇档案](2026/11/10/健康/stiff-person-car-t-guardian.md)

---

<a id="shehui"></a>

## 社会

### 北爱尔兰学校午餐再涨价，免费午餐学生不受影响

教育局宣布，学前、小学和特殊学校午餐上涨 30 便士，中学上涨 15 便士。这是今年第二次上调。有资格领免费午餐的学生不在此列。

发布：上海时间2026-11-10 08:00｜[BBC](https://www.bbc.co.uk/news/articles/c9m262yv6yx8o)  
[单篇档案](2026/11/10/社会/ni-school-dinner-prices-bbc.md)

---

<a id="caijing"></a>

## 财经

### Poundland 已申请指定管理人，BBC 称约 5000 万英镑被冻结

Poundland 已提交指定管理人的意向通知，债权人保护维持到周四。BBC 了解到，东家冻结了大约 5000 万英镑，约 600 家店补不上货。

发布：上海时间2026-11-10 00:46｜[BBC](https://www.bbc.co.uk/news/articles/cw1l3lmem165o)  
[单篇档案](2026/11/10/财经/poundland-stock-freeze-bbc.md)

---

<a id="yule"></a>

## 娱乐

### 詹姆斯·冈恩和彼得·萨弗兰卸任 DC 宇宙联席首席执行官

重启后的 DC 宇宙联席首席执行官詹姆斯·冈恩和彼得·萨弗兰卸任。接任者是制片人 Jeremy Latcham。文章写明，还不清楚是辞职还是被要求离开。

发布：上海时间2026-11-10 05:55｜[Ars Technica](https://arstechnica.com/culture/2026/11/dcu-shake-up-james-gunn-and-peter-safran-out-post-merger/)  
[单篇档案](2026/11/10/娱乐/dcu-gunn-safran-step-down-arstechnica.md)

### 电视家居节目主持人汤米·沃尔什去世，享年 69 岁

BBC 报道，曾主持 Ground Force 和 Homes Under the Hammer 的汤米·沃尔什去世，享年 69 岁。经纪人说，他在久病之后于家人身旁平静离世。

发布：上海时间2026-11-09 23:27｜[BBC](https://www.bbc.co.uk/news/articles/ck0e0elq4ndpo)  
[单篇档案](2026/11/10/娱乐/tommy-walsh-dies-bbc.md)

### 玛雅·贾玛宣布不再主持 Love Island

玛雅·贾玛说，她主持 Love Island 三年后将离开。文章发于上海时间 11 月 9 日 04:20，早于这次早间采集的 24 小时，仍在 48 小时内。

发布：上海时间2026-11-09 04:20｜[BBC](https://www.bbc.co.uk/news/articles/cwzrd5jj47ndo)  
[单篇档案](2026/11/10/娱乐/maya-jama-leaves-love-island-bbc.md)

### 玛丽亚·凯莉确定 2027 年 6 月 27 日担任 Powderham 音乐节主打

主办方宣布，玛丽亚·凯莉将在 2027 年 6 月 27 日到德文郡 Powderham Castle 演出。这是档期公布，演出尚未举行。

发布：上海时间2026-11-09 17:57｜[BBC](https://www.bbc.co.uk/news/articles/c674p4lynjk1o)  
[单篇档案](2026/11/10/娱乐/mariah-carey-powderham-2027-bbc.md)

---

<a id="tiyu"></a>

## 体育

### WTA 年终总决赛小组赛：萨巴伦卡苦胜穆霍娃，米拉·安德烈耶娃直落两盘取胜

BBC Sport 报道，阿丽娜·萨巴伦卡在 WTA 年终总决赛小组赛以 7-6（7-2）、7-5 击败卡洛琳娜·穆霍娃。这是小组赛结果，不是总决赛冠军。米拉·安德烈耶娃同日以 6-4、6-0 击败埃琳娜·斯维托丽娜。

发布：上海时间2026-11-10 07:10｜[BBC Sport](https://www.bbc.co.uk/sport/tennis/articles/cr20w0q8lgy1o)  
[单篇档案](2026/11/10/体育/wta-finals-sabalenka-andreeva-bbc.md)

### NFL 第 9 周：比尔 23-6 击败维京人，与 49 人并列联盟最佳 7 胜 1 负

BBC Sport 确认，布法罗比尔在周一夜间赛以 23-6 客场击败明尼苏达维京人，7 胜 1 负，与旧金山 49 人并列联盟最佳。这是已完赛比分。展示时间取纳入这场结果后的修改时间。

发布：上海时间2026-11-10 14:33｜[BBC Sport](https://www.bbc.com/sport/american-football/articles/cmdxwxry2pr8o)  
[单篇档案](2026/11/10/体育/nfl-week9-bills-vikings-bbc.md)

### 巴西大奖赛：梅赛德斯锁定车队年度冠军

这是上周末的巴西大奖赛。车手年度冠军在此之前已经产生。这场比赛里，梅赛德斯锁定了车队冠军。拉塞尔第 4，安东内利第 5。

发布：上海时间2026-11-09 23:16｜[Ars Technica](https://arstechnica.com/cars/2026/11/f1-in-brazil-drivers-at-their-very-best-in-tricky-conditions/)  
[单篇档案](2026/11/10/体育/f1-brazil-mercedes-constructors-arstechnica.md)

---

<a id="qita"></a>

## 其他

### Berkeley Earth 称有 95% 的把握，2026 年会打破最热年纪录

BBC 援引 Berkeley Earth：即便还剩两个月，他们也有 95% 的把握认为 2026 年会超过 2024 年的全球最热纪录。这是预报，不是年终定论。

发布：上海时间2026-11-09 15:30｜[BBC](https://www.bbc.co.uk/news/articles/c6pvgg7mdvdvo)  
[单篇档案](2026/11/10/其他/berkeley-earth-2026-heat-bbc.md)

---

## 阅读说明

首页按独立事件计数。重点区和栏目里出现两次的，仍然是一条。

来源给出钟点时，这里只写上海时间；原时区写在单篇档案里。只有日期的，不补时分。BBC 与 BBC Sport 计为同一来源。

GitHub Copilot 与 Microsoft Foundry 上线 Claude Fable 5.2，与上面已收录的 Fable 与 Mythos 5.2 发布算同一事件。

稳定版块是：AI、科技、搞笑、财经、娱乐、体育、社会、健康、其他。AI 单独成栏，不并入科技。这一栏看热门产品与工具，尤其是 ChatGPT、Codex、Claude Code（CC）、Cursor、Grok Bot、DeepSeek，以及同级别的助手和编程工具。单篇放在 `YYYY/MM/DD/AI/`。

仅展示审核通过内容。

本页是 GitHub 上的 Markdown，不是独立网站。更新时间：上海时间 2026-11-10 18:35。
