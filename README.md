# 2026年11月12日 · 海外资讯日报

上海时间 **2026-11-12 18:34** 更新。独立新闻 **43** 条，**15** 个来源，其中 AI **17** 条。仅展示审核通过内容。

这是 11 月 12 日晚间增量，在早间 19 条基础上新增 24 条，不是新的一天。本窗口内，Cursor 官方博客仍停在 11 月 10 日的 Projects 多人协作，changelog 仍停在 11 月 6 日的 Voice Chat；Anthropic 新闻室、DeepSeek 与 xAI / Grok Bot 官方新闻室仍没有新的产品稿。Anthropic 对齐科学博客有一篇多人多代理研究报告，已收入 AI 栏。

来源按不重复出口计算：谷歌官方博客、DeepMind 博客与 Google Developers Blog 计为一家「谷歌」；OpenAI 早间两条与晚间帮助中心稿计为一家；GitHub Blog 的安全公告与 Changelog 计为一家；BBC News 与 BBC Sport 计为一家；The Guardian 各条计为一家；微软 Visual Studio Blog 与 Foundry 博客计为一家「微软」。WTA、NBA.com、ABC News 延续早间已计入。晚间新计入 Anthropic、Databricks、Amazon Web Services（两条计为一家）、The Verge（两条计为一家）、IBM Newsroom、NPR。

[当日完整版](2026/11/12/日报.md) · [往期索引](ARCHIVE.md)

---

## 今日重点

五条展开。下面各栏是短读，重点条目在栏里只留一句。

<a id="hl-carplay"></a>

### 1. Google 把 Gemini Live 带到 Apple CarPlay，可在车机上免提对话

Google 在官方博客宣布，继 Android Auto 和内置 Google 系统的汽车之后，把 Gemini 应用直接带到 Apple CarPlay。官方称，iOS 用户可以在车机屏幕上用 Gemini Live 进行免提、可来回打断的对话，用来查看当天日程、整理未读邮件、了解沿途地点，或在车上练习陈述、讨论问题。

稿件写明，CarPlay 上的对话会自动同步到 iPhone 上的 Gemini 应用，停车后可以在聊天记录里接着看摘要和笔记。使用前需要更新到最新版 Gemini 应用、开启麦克风权限，并至少在手机上使用过一次 Gemini Live；再次把手机连到车机后，点击 CarPlay 上的 Gemini 图标即可开始或接续对话。

官方称这一功能即日起向所有 Gemini 的 iOS 用户、在所有已支持的 Gemini Live 语言中全球推送。文末注明：Daily Brief 需先开启；包括 Daily Brief 在内的部分个性化功能不向 18 岁以下用户，以及欧洲经济区（EEA）和尼日利亚的用户提供。上述范围和排期均为公司产品发布陈述。

为何关注：开车时用语音处理日程和邮件，是很多 iPhone 用户最常碰到的场景；这次是 Gemini Live 进入 CarPlay，而不只是手机端功能平移。

发布：上海时间2026-11-12 01:00｜[Google](https://blog.google/innovation-and-ai/products/gemini-app/gemini-on-apple-carplay/)  
[单篇档案](2026/11/12/AI/gemini-on-apple-carplay.md)

---

<a id="hl-a2ui"></a>

### 2. Google 发布 A2UI 1.0：智能体可用开放协议生成原生交互界面

Google 在开发者博客宣布推出 A2UI 1.0，称之为其生成式用户界面开放协议的首个稳定版。按官方说明，智能体负责描述要展示的界面，接收方应用再用自己的原生组件来绘制，从而在网页、手机和桌面里显示表单、图表等可交互屏幕，而不是只返回大段文字。

1.0 提供面向 React、Angular、Lit、Flutter、SwiftUI 的开源渲染库，以及 Python、TypeScript 和 Dart 的智能体 SDK。官方还提到双向函数调用（例如在选择航班或预约时当场查询是否有空位）、无障碍支持和扩展元数据。Jetpack Compose 渲染器目前支持 0.9.1，官方称 1.0 支持即将到来。网页和 Flutter 渲染器也可在支持 MCP Apps 的助手（文中举例 Claude 和 Gemini）里显示 A2UI 界面。

稿件点名 Atlassian、Alation、Bloomberg 和 ByteDance 已在使用。例如 Atlassian 计划让 Jira 里的智能体用交互卡片向团队追问缺失信息；Alation 用 A2UI 在自家产品或 Claude 对话中呈现指标卡和图表。这些合作陈述来自 Google 稿件及其中引用的对方负责人表态，并非第三方评测。

为何关注：如果智能体的回答从纯文字变成可点选的原生界面，购物对比、改计划、审批这类日常操作会少很多来回确认。

发布：上海时间2026-11-11（官方仅标注日期，未给出具体时刻）｜[Google Developers Blog](https://developers.googleblog.com/en/a2ui-10-build-delightful-fast-reliable-agentic-experiences/)  
[单篇档案](2026/11/12/AI/google-a2ui-1-0.md)

---

<a id="hl-dfa"></a>

### 3. 欧盟公布《数字公平法》草案，拟限制游戏战利品箱、成瘾设计和未标明的网红营销

The Verge 报道，欧盟委员会于周三公布《数字公平法》（Digital Fairness Act）草案，称希望让人们的上网体验更公平，并针对被指诱导消费者多花时间、多花钱的做法，包括误导性价格或库存信息、带有成瘾设计的功能（稿中举例包括游戏里的战利品箱）、未充分披露的网红营销等。

欧盟委员会在通报中称，该法案将保护在网上购物和浏览的各年龄段消费者，并预计相关规则可为欧盟消费者每年节省最多 137 亿欧元（约 151 亿美元）；这是委员会自己的估算，并非独立复核结论。报道还提到，草案覆盖面较广，可能影响到视频和社交平台的推荐算法，以及对用户持续提醒互动的应用。报道还写明，关于成瘾设计的限制也适用于「AI 伴侣和通用对话聊天机器人」。部分游戏行业组织已批评草案中关于虚拟货币、战利品箱以及向未成年人提供小额内购的限制。

稿件明确写明：这仍是草案，还需经过欧洲议会和欧盟理事会审批，现有措施可能在立法过程中被修改或删除。欧盟委员会表示，若将来生效，违规企业可能面临最高相当于全球年营业额 6% 的罚款。欧盟委员迈克尔·麦克格拉思说，希望企业凭产品和服务本身竞争，而不是靠利用消费者或规避规则。

为何关注：这还不是已经生效的法律，但如果草案大致按现有方向走完立法，可能改变游戏内购、推荐算法和网红营销的常见做法。

发布：上海时间2026-11-12 02:13｜[The Verge](https://www.theverge.com/policy/1031575/digital-fairness-act-eu-dfa-consumer-protection)  
[单篇档案](2026/11/12/科技/eu-digital-fairness-act-proposal.md)

---

<a id="hl-ibm"></a>

### 4. IBM 公布下一代量子芯片规划：2027 年拟把两枚处理器连成超 1000 量子比特系统

IBM 在官方新闻室宣布，下一代处理器 IBM Quantum Nighthawk r3 将按可在 520 个可编程量子比特上准确执行 1 万次量子操作来设计，并计划在 2027 年把两枚 Nighthawk r3 连接成一个超过 1000 量子比特、官方写明为 1040 量子比特的单一系统。公司称，r3 共有 2034 个物理量子比特，保留现款的方形晶格连接和快速操作，并引入 10 条称为 l-coupler 的芯片间互连。

关于已经交付的 Nighthawk r2，IBM 说它于 9 月推出，可在 120 个量子比特上支持超过 7500 次量子操作，并称客户和合作伙伴已在其上运行超过 340 亿条线路，反馈最高约 19 倍加速；文中举例包括能源公司 E.ON 在电网优化相关量子机器学习中报告 15 倍加速等。这些成绩和倍数均来自公司及合作方陈述，不是独立评测结论。

在模块化方面，IBM 称今年已用 4 条 l-coupler 连接 Nighthawk r1 处理器，量子态传输保真度达到 99.3%，并向 99.9% 的长期目标推进；同时首次把两个低温模块连成一个系统，称可在五天内达到运行温度并冷却到 15 毫开尔文以下。官方强调，有用的量子计算既取决于精度，也取决于能否在合理时间内给出足够多样本，而 2027 年的双芯片系统仍属路线图中的计划，不是已经上线的机器。

为何关注：这是 IBM 对公开路线图的一次具体调整：用两枚更大的芯片，去接近此前用多枚小芯片才能达到的上千量子比特规模，但仍是 2027 年的计划。

发布：上海时间2026-11-11（仅有日期，时区与钟点未标明，不换算到小时）｜[IBM Newsroom](https://newsroom.ibm.com/2026-11-11-ibm-quantum-nighthawk-demonstrates-new-levels-of-speed-and-quality,-with-plans-to-scale-beyond-1,000-qubits-in-2027)  
[单篇档案](2026/11/12/科技/ibm-nighthawk-r3-1040-qubit-plan.md)

---

<a id="hl-ukgdp"></a>

### 5. 英国第三季度经济增速达逾两年来最快，服务业和计算机编程是主要推手

英国广播公司报道，官方数据显示，英国经济在截至 9 月的三个月（7 月至 9 月）增长 0.7%，增速快于上一季度，为逾两年来最快。报道称，这显示出夏季经济韧性好于一些预期。占经济主体的服务业是主要支撑，其中计算机编程录得过去三年最快增速；BBC 写明这一块得到与人工智能相关支出的帮助，并且编程和咨询服务是今年迄今增长的最大驱动力。

英国国家统计局首席经济学家格兰特·菲茨纳表示，若没有中东局势等因素带来的影响，增长原本“可能更高”。他也提醒，家庭未必已经明显感到更宽裕，物价上涨速度也可能再度超过工资。咨询公司普华永道高级经济学家杰克·芬尼则警告，除非能源市场稳定下来，否则未来几个月增长可能放缓。

报道称，按最新数字，英国有望成为七国集团（G7）中增速第二快的经济体。首相安迪·伯纳姆把这些数字称为“值得欢迎的消息”，并表示尽管过去一年外部事件推高了国内成本，经济仍在增长。需要区分的是：这是已经公布的季度统计，不是对四季度的预测。

为何关注：这是英国最新的官方季度增速，也是观察家庭感受、能源价格和后续增长能否持续时最直接的一套数字。

发布：上海时间2026-11-12 15:05（首次发表；页面更新约 17:43）｜[BBC News](https://www.bbc.com/news/articles/ck3rgd429zd5o)  
[单篇档案](2026/11/12/财经/uk-q3-gdp-fastest-in-over-two-years.md)

---

## 栏目

[AI](#ai) · [科技](#keji) · [搞笑](#gaoxiao) · [财经](#caijing) · [娱乐](#yule) · [体育](#tiyu) · [社会](#shehui) · [健康](#jiankang) · [其他](#qita)

<a id="ai"></a>

## AI

<a id="hl-decisions"></a>
<a id="cat-gemini-decisions-api"></a>

### 谷歌推出 Gemini Decisions API，一次可评估最多 1000 个封闭式问题

谷歌宣布推出 Gemini Decisions API，由 Gemini Decision 1 提供支持，一次可对同一段多模态输入评估最多 1000 个封闭式问题。延迟和价格来自官方陈述，Google Cloud 上的支持仍为即将推出。

发布：上海时间2026-11-12 02:00｜[Google](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)  
[单篇档案](2026/11/12/AI/gemini-decisions-api.md)

<a id="hl-alphagenome"></a>
<a id="cat-alphagenome-2"></a>

### DeepMind 发布 AlphaGenome 2，用于预测基因变异在特定细胞类型中的影响

DeepMind 发布 AlphaGenome 2，用于预测 DNA 变异如何影响特定的人类细胞类型。该模型仅供研究使用，尚未针对临床或诊断用途通过验证或获得批准；文中基准是公司陈述。

发布：上海时间2026-11-11 23:00｜[Google DeepMind](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)  
[单篇档案](2026/11/12/AI/alphagenome-2.md)

<a id="hl-alphaproof"></a>
<a id="cat-alphaproof-code-signal-verification"></a>

### DeepMind 介绍 AlphaProof Code：用形式化方法验证 Signal 协议核心代码的关键安全属性

DeepMind 介绍 AlphaProof Code，称已在人类专家指导下对 Signal 协议核心密码学代码的关键安全属性做形式化验证。验证范围不是整个 Signal 应用，相关定位来自公司陈述。

发布：上海时间2026-11-10（官方页面日期为 November 10, 2026；meta 与 JSON-LD 给出 12:00:00+00:00，更像按日占位，不当作真实钟点）｜[Google DeepMind](https://deepmind.google/blog/introducing-alphaproof-code/)  
[单篇档案](2026/11/12/AI/alphaproof-code-signal-verification.md)

<a id="hl-freelance"></a>
<a id="cat-openai-upwork-freelance-work"></a>

### OpenAI 与 Upwork 研究：AI 相关兼职项目预算更高、任务组合也更杂

OpenAI 与 Upwork 的研究称，在同期、同类工作的比较中，AI 相关项目的固定价格预算约高 52%，前 90 天记录工时约多 41%。这些是控制了工作类别和发布月份后的比较结果，不能直接读成整体就业结论。

发布：上海时间2026-11-10（官方仅标注日期，未给出具体时刻）｜[OpenAI](https://openai.com/index/ai-effect-on-freelance-work)  
[单篇档案](2026/11/12/AI/openai-upwork-freelance-work.md)

<a id="google-labs-tabletop"></a>

### 谷歌 Labs 推出 Tabletop：可生成行程、投票和分账工具的协作空间，美国 18 岁以上需排队

谷歌 Labs 宣布推出实验项目 Tabletop，面向小组实时协作。用户可放入链接、文件和想法，然后向 @tabletop 发出提示，或选用起始模板，生成可互动的旅行行程、聚餐投票、费用分摊和比赛对阵等页面；完成后把邀请链接发到群聊，多人可像在 Google 文档里一样同时使用。

该实验正在美国向 18 岁及以上用户以等候名单形式推送，登记地址为 labs.google/tabletop。这是 Labs 实验，不是已经向全球所有谷歌账号开放的正式产品。

发布：上海时间2026-11-12 00:00｜[Google](https://blog.google/innovation-and-ai/models-and-research/google-labs/tabletop/)  
[单篇档案](2026/11/12/AI/google-labs-tabletop.md)

<a id="multimodal-knowledge-agent-benchmark"></a>

### 谷歌与 Artificial Analysis 发布多模态知识工作基准 MKA，含 200 项非公开任务

谷歌与评测机构 Artificial Analysis 宣布推出 Multimodal Knowledge Agent（MKA）基准，用来评估智能体如何在视觉复杂的文件中完成知识工作。官方说，任务由 10 个行业、83 种职业的领域专家共同设计，评估集共 200 项；每项相当于熟练专业人员 3 到 8 小时的工作，并配有约 70 条是非评分标准，其中 75% 看事实准确性，25% 看视觉设计。

所有模型都在同一开源智能体框架 Stirrup 中、用同样的工具、沙箱和轮次预算运行。评分由基于非谷歌模型的自动评审完成；官方称，领域专家亲自打分时，与自动评审的一致率为 96%。200 项评估集由 Artificial Analysis 运行并保持非公开，另有 10 项公开任务放在 Hugging Face。谷歌称，Gemini 4 Carbon 在所测模型中质量排第 2，平均成本约为最高分模型的六分之一；这是公司陈述，需结合独立评测看待。

发布：上海时间2026-11-11 00:00｜[Google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/multimodal-knowledge-agent-benchmark/)  
[单篇档案](2026/11/12/AI/multimodal-knowledge-agent-benchmark.md)

<a id="openai-caregivers-ai-skills-jam"></a>

### OpenAI 与护理组织在美国五城举办面向照护者的免费 ChatGPT 工作坊

OpenAI 宣布，在美国「国家家庭照护者月」期间，OpenAI Academy 与 Caregiver Action Network、阿尔茨海默病协会和美国糖尿病协会合作，于 11 月 10 日在奥克兰、坦帕、匹兹堡、亚特兰大和底特律举办免费线下工作坊，帮助照护者安全、实际地使用 ChatGPT。

活动面向个人和家庭照护者、支持机构，以及有慢性或严重健康问题的人，内容包括整理照护日程和清单、把可信教育材料改写成更易读的文本、查找社区资源，以及准备互助讨论提纲。官方强调要保护个人信息、理解工具边界，并在需要时咨询专业人士，AI 不能替代医疗、法律或财务建议。OpenAI 还给出一项保护隐私的使用估计：2026 年 10 月 9 日至 29 日，美国每周超过 4000 万条与医疗相关的 ChatGPT 消息，是在为他人询问医疗问题。这是公益培训说明，不是新的付费产品发布。

发布：上海时间2026-11-10（官方仅标注日期，未给出具体时刻）｜[OpenAI](https://openai.com/index/helping-caregivers-use-ai-in-everyday-life)  
[单篇档案](2026/11/12/AI/openai-caregivers-ai-skills-jam.md)

<a id="visual-studio-byom-generally-available"></a>

### Visual Studio 正式提供「自带模型」，可不登录 GitHub 使用自有或本地接口

微软 Visual Studio 博客宣布，Bring Your Own Model（BYOM）已在 Visual Studio 18.12 正式可用。用户可把自有托管模型、供应商 API 密钥，或本机运行的模型接入 Visual Studio，而不必离开这套开发环境。

此次更新支持为同一供应商保存多套配置并分别命名，新增面向 OpenAI 兼容服务和本地模型的自定义端点，可选择 Completions、Responses 或 Anthropic Messages 等接口格式，并改进了代理支持。官方写明，不需要登录 GitHub；只要模型端点可达且满足认证要求，也可在隔离网络里使用内部或本地模型。管理员可通过组织策略开启或关闭 BYOM。若界面里看不到「添加模型供应商」，可能是管理员已关闭该功能。

发布：上海时间2026-11-12 01:00｜[Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/bring-your-own-model-is-now-generally-available-in-visual-studio/)  
[单篇档案](2026/11/12/AI/visual-studio-byom-generally-available.md)

<a id="cat-gemini-on-apple-carplay"></a>

### Google 把 Gemini Live 带到 Apple CarPlay，可在车机上免提对话

已在[今日重点](#hl-carplay)展开。Google 宣布 Gemini Live 即日起可在 Apple CarPlay 上免提使用，部分个性化功能不向 18 岁以下以及欧洲经济区和尼日利亚用户提供，这些范围均为公司陈述。

发布：上海时间2026-11-12 01:00｜[Google](https://blog.google/innovation-and-ai/products/gemini-app/gemini-on-apple-carplay/)  
[单篇档案](2026/11/12/AI/gemini-on-apple-carplay.md)

<a id="cat-google-a2ui-1-0"></a>

### Google 发布 A2UI 1.0：智能体可用开放协议生成原生交互界面

已在[今日重点](#hl-a2ui)展开。官方把 A2UI 1.0 称为生成式用户界面开放协议的首个稳定版；Jetpack Compose 渲染器的 1.0 支持仍是即将到来。

发布：上海时间2026-11-11（官方仅标注日期，未给出具体时刻）｜[Google Developers Blog](https://developers.googleblog.com/en/a2ui-10-build-delightful-fast-reliable-agentic-experiences/)  
[单篇档案](2026/11/12/AI/google-a2ui-1-0.md)

<a id="anthropic-mamubench-worse-together"></a>

### Anthropic 研究：多人各自把任务交给自己的代理，群体结果往往更差

Anthropic 对齐科学博客的研究报告称，在四个模拟环境里，单个协调代理的群体结果都好于每人各用一个代理；对 Claude Opus 5 和 Claude Sonnet 5，差距大约在 10 到 45 个百分点。这些数字来自模拟评测，不能直接等同于某一款消费级产品的真实事故率。

发布：上海时间2026-11-11（官方仅标注日期，未给出具体时刻）｜[Anthropic](https://alignment.anthropic.com/2026/worse-together/)  
[单篇档案](2026/11/12/AI/anthropic-mamubench-worse-together.md)

<a id="databricks-always-on-genie"></a>

### Databricks 发布第二代 Genie：现有助手已开放，全天候代理仍待预览

Databricks 宣布第二代 Genie：Genie 和 Genie Ontology 已对所有客户一般可用，而这次强调的 always-on（全天候）Genie 仍是即将进入预览。新闻稿里 HelloFresh 称识别优胜创意的时间缩短 75%，这一数字来自客户表述，并非独立审计结果。

发布：上海时间2026-11-11（官方仅标注日期；页面 meta 虽有 02:06，但未标明时区，故不换算）｜[Databricks](https://www.databricks.com/company/newsroom/press-releases/databricks-launches-new-always-genie-autonomous-ai-complex)  
[单篇档案](2026/11/12/AI/databricks-always-on-genie.md)

<a id="openai-retiring-advanced-standard-voice"></a>

### OpenAI 将于 12 月 11 日停用 ChatGPT 的 Advanced 和 Standard 语音

OpenAI 帮助中心确认，将于 2026 年 12 月 11 日停用 ChatGPT Voice 的 Advanced 和 Standard 语音，此前已选择它们的用户将被默认转到 GPT-Live。这是已公布的计划下线，不是当天已经关闭。

发布：帮助中心未给出可核验的首次发布时间；正文写明通知自 2026-11-10 开始、功能于 2026-12-11 下线（官方仅标注日期）。页面在上海时间 2026-11-12 约 18:10 打开时显示 Updated: 9 hours ago，只说明最近一次更新大约在当天上午，不能当作首次发布时间。｜[OpenAI](https://help.openai.com/en/articles/20001638-retiring-advanced-and-standard-voice-in-chatgpt)  
[单篇档案](2026/11/12/AI/openai-retiring-advanced-standard-voice.md)

<a id="azure-content-understanding-gpt-6-models"></a>

### Azure Content Understanding 新增 GPT-5.6、GPT-6 和 GPT-6.1 可选模型

微软宣布 Azure Content Understanding 现支持 GPT-5.6、GPT-6 和 GPT-6.1。文中准确率和费用对比来自微软自己的评测，官方也写明结果会随任务和内容变化很大。

发布：上海时间2026-11-12 02:24｜[Microsoft](https://devblogs.microsoft.com/foundry/content-understanding-adds-gpt-5-6-gpt-6-and-gpt-6-1-choose-the-right-model-for-your-workload/)  
[单篇档案](2026/11/12/AI/azure-content-understanding-gpt-6-models.md)

<a id="google-ai-edge-gallery-on-device-speech"></a>

### Google AI Edge Gallery 上线端侧语音识别和语音合成，可完全离线使用

Google 宣布在 AI Edge Gallery 中加入可完全在设备上运行的语音识别和语音合成。文中的语言覆盖和速度数字来自 Google 自己的说明，需要视为公司评测陈述。

发布：上海时间2026-11-10（官方仅标注日期，未给出具体时刻）｜[Google Developers Blog](https://developers.googleblog.com/en/on-device-speech-recognition-and-text-to-speech-in-google-ai-edge-gallery/)  
[单篇档案](2026/11/12/AI/google-ai-edge-gallery-on-device-speech.md)

<a id="kimi-k3-1-pro-amazon-bedrock"></a>

### Moonshot AI 的 Kimi K3.1 Pro Highspeed 已在 Amazon Bedrock 上线

AWS 宣布 Moonshot AI 的 Kimi K3.1 Pro Highspeed 已在 Amazon Bedrock 上提供。约 3T 参数、100 万 token 上下文，以及输出速度约为 Kimi K3.1 Pro 的 2 到 3 倍，均为供应商陈述。

发布：上海时间2026-11-11 09:07｜[Amazon Web Services](https://aws.amazon.com/blogs/machine-learning/introducing-kimi-k3-1-pro-on-amazon-bedrock/)  
[单篇档案](2026/11/12/AI/kimi-k3-1-pro-amazon-bedrock.md)

<a id="aws-bedrock-agentcore-web-search-api"></a>

### Amazon Bedrock AgentCore 的网页搜索 API 已一般可用

AWS 宣布 Amazon Bedrock AgentCore 的 Web Search API 已一般可用，定价为每 1000 次查询 7 美元。页面只标注日期，另有 00:00:00Z 占位时刻，不作为真实钟点。

发布：上海时间2026-11-10（官方仅标注日期；页面另有 00:00:00Z 占位时刻，不采用）｜[Amazon Web Services](https://aws.amazon.com/about-aws/whats-new/2026/11/amazon-bedrock-agentcore-web-search-api/)  
[单篇档案](2026/11/12/AI/aws-bedrock-agentcore-web-search-api.md)

---

<a id="keji"></a>

## 科技

<a id="git-security-vulnerabilities-2-56-1"></a>

### Git 项目发布 2.56.1 等修复版本，修补六个安全漏洞

GitHub 博客发布 Git 项目的安全更新说明：新版本修复六个安全漏洞，涉及递归克隆、引用处理、合并、二进制补丁和导入等环节，其中包括在递归克隆恶意仓库时可能执行代码、写入非预期文件，以及处理合并或二进制补丁时的内存损坏。

修复已包含在 Git 2.56.1 中，并回溯到 2.55.1、2.54.1、2.53.1、2.52.1、2.51.3 和 2.50.2。官方建议更新到 2.56.1 或自己所用维护分支的修补版，同时更新捆绑了 Git 的应用程序。GitHub 称已在 github.com 及相关云服务部署修复，并列出了 GitHub Enterprise Server 的对应更新版本。若暂时无法升级，官方建议只从受信任的服务器克隆，并避免对不受信任的仓库做递归克隆，但这些做法不能替代安装修补。

发布：上海时间2026-11-11 02:00｜[GitHub Blog](https://github.blog/open-source/git/git-security-vulnerabilities-announced-7/)  
[单篇档案](2026/11/12/科技/git-security-vulnerabilities-2-56-1.md)

<a id="google-adobe-partnership-integrations"></a>

### 谷歌与 Adobe 扩大合作：将把 Acrobat 等工具更深接入 Drive、Gmail 和 Gemini

谷歌宣布，在 Adobe MAX 上扩展与 Adobe 的合作：把 Adobe 的创作和生产力工具更深接入日常谷歌产品，同时也把谷歌的前沿 AI 模型带进 Adobe 应用。官方列出的计划包括：Google Drive 和 Gmail 将出现通向 Adobe Acrobat 的直接入口，并在文件预览中提供「Edit with」；Adobe 将扩大在 Gemini 和 Gemini Enterprise 中的连接器，并把创作工具带进搜索的 AI 模式；企业将可在 Gemini Enterprise 中使用 Adobe 的 CX Enterprise Coworker 智能体。

Adobe 与 Google DeepMind 还将探索面向专业创作者的新编辑能力，起步是一款可能用于 Photoshop、接近实时修改的图像模型。文中多用「即将」「将」来描述这些能力，因此本稿把它记为合作与功能规划的宣布，而不是上述入口和模型都已经全部上线。

发布：上海时间2026-11-10 22:00｜[Google](https://blog.google/company-news/inside-google/company-announcements/adobe-google-partnership-integration/)  
[单篇档案](2026/11/12/科技/google-adobe-partnership-integrations.md)

<a id="github-issue-types-fields-personal-accounts"></a>

### GitHub 向个人账号仓库开放议题类型与自定义字段

GitHub 宣布，议题类型（issue types）和议题字段（issue fields）已在个人账号拥有的仓库中一般可用，个人开发者和开源维护者可以用与组织仓库相同的规划能力，来规范流程并跨仓库整理议题。

个人账号设置里的默认议题类型是 Bug、Task 和 Feature，最多可自定义 25 种；默认字段包括 Priority、Effort、Start date 和 Target date，同样最多 25 个，支持文本、数字、日期、单选和多选，也可把字段固定到某种类型。创建或查看议题时可填写这些信息，也可在 Projects 里做自定义视图和批量更新，并通过 REST、GraphQL API 和 webhook 管理。同一篇更新还写明，现在可以直接在议题页创建标签和里程碑，而不必先转到仓库的相应页面。

发布：上海时间2026-11-12 01:16｜[GitHub Blog](https://github.blog/changelog/2026-11-11-issue-types-and-fields-are-available-for-personal-accounts/)  
[单篇档案](2026/11/12/科技/github-issue-types-fields-personal-accounts.md)

<a id="apple-support-community-closing"></a>

### 有28年历史的苹果官方用户论坛将于11月20日关闭，现已改为只读

The Verge 报道，苹果用户论坛 Apple Support Community 将于 2026 年 11 月 20 日永久关闭，即日起改为只读。苹果尚未说明数十年来的历史帖文将如何处理。

发布：上海时间2026-11-11 20:19｜[The Verge](https://www.theverge.com/tech/1031507/apple-community-support-forum-shutting-down)  
[单篇档案](2026/11/12/科技/apple-support-community-closing.md)

<a id="cat-eu-digital-fairness-act-proposal"></a>

### 欧盟公布《数字公平法》草案，拟限制游戏战利品箱、成瘾设计和未标明的网红营销

已在[今日重点](#hl-dfa)展开。欧盟委员会公布的《数字公平法》仍是草案，还需欧洲议会和欧盟理事会审批，不是已经生效的法律。

发布：上海时间2026-11-12 02:13｜[The Verge](https://www.theverge.com/policy/1031575/digital-fairness-act-eu-dfa-consumer-protection)  
[单篇档案](2026/11/12/科技/eu-digital-fairness-act-proposal.md)

<a id="cat-ibm-nighthawk-r3-1040-qubit-plan"></a>

### IBM 公布下一代量子芯片规划：2027 年拟把两枚处理器连成超 1000 量子比特系统

已在[今日重点](#hl-ibm)展开。IBM 计划在 2027 年把两枚 Nighthawk r3 连成官方写明为 1040 量子比特的系统，这仍是路线图中的计划，不是已经上线的机器。

发布：上海时间2026-11-11（仅有日期，时区与钟点未标明，不换算到小时）｜[IBM Newsroom](https://newsroom.ibm.com/2026-11-11-ibm-quantum-nighthawk-demonstrates-new-levels-of-speed-and-quality,-with-plans-to-scale-beyond-1,000-qubits-in-2027)  
[单篇档案](2026/11/12/科技/ibm-nighthawk-r3-1040-qubit-plan.md)

---

<a id="gaoxiao"></a>

## 搞笑

本期暂无通过审核的稿件。

---

<a id="caijing"></a>

## 财经

<a id="rwe-kkr-norfolk-vanguard-offshore-wind"></a>

### 英国宣布 120 亿英镑融资，用于在诺福克近海建设两座风电场

BBC 报道，能源公司 RWE 与投资机构 KKR 宣布了一项 120 亿英镑融资，用于建设诺福克近海的 Vanguard West 和 Vanguard East 海上风电场。这两个项目预计 2030 年全部投运，海上施工计划于 2027 年初开始。

融资中包括英国国家财富基金的 10 亿英镑。RWE 称，这两个项目是英国最大的海上风电开发之一，装机约 2.8 吉瓦，足以供约 300 万户家庭用电；场址距海岸约 50 到 80 公里。英国政府称，该投资将在建设和运营阶段支持 2400 多个岗位。RWE 还表示，陆上电缆和变电站等前期工作已经推进。这是融资与建设安排的宣布，不是风电场已经建成发电。

发布：上海时间2026-11-12 03:30｜[BBC News](https://www.bbc.com/news/articles/c539gkxwjz3vo)  
[单篇档案](2026/11/12/财经/rwe-kkr-norfolk-vanguard-offshore-wind.md)

<a id="cat-uk-q3-gdp-fastest-in-over-two-years"></a>

### 英国第三季度经济增速达逾两年来最快，服务业和计算机编程是主要推手

已在[今日重点](#hl-ukgdp)展开。官方数据显示英国第三季度经济增长 0.7%，这是已经公布的季度统计，不是对四季度的预测。

发布：上海时间2026-11-12 15:05（首次发表；页面更新约 17:43）｜[BBC News](https://www.bbc.com/news/articles/ck3rgd429zd5o)  
[单篇档案](2026/11/12/财经/uk-q3-gdp-fastest-in-over-two-years.md)

<a id="ofwat-tightens-water-bonus-ban"></a>

### 英国水务监管机构将收紧奖金禁令，指部分公司用留任金等方式绕开规则

《卫报》报道，Ofwat 称英格兰和威尔士有九家水务公司被禁止在 2025–26 财年发放奖金，并指责部分高额支付像是在绕开禁令，将加快检讨规则。这是监管表态，不是已经完成的规则修订。

发布：上海时间2026-11-12 15:59｜[The Guardian](https://www.theguardian.com/business/2026/nov/12/water-industry-bonus-ban-tightened-ofwat)  
[单篇档案](2026/11/12/财经/ofwat-tightens-water-bonus-ban.md)

---

<a id="yule"></a>

## 娱乐

<a id="dua-lipa-first-british-woman-coachella-headliner"></a>

### 杜阿·利帕将成科切拉首个英国女头牌，与 Tame Impala、SZA 分日压轴

BBC 报道，杜阿·利帕将在 2027 年科切拉两个周末的周五担任头牌，成为该音乐节首位单独演出的英国女头牌。这是已经发布的阵容公告，演出要到 2027 年 4 月才举行。

发布：上海时间2026-11-11 18:53｜[BBC News](https://www.bbc.com/news/articles/cjr4g0n9d1g5o)  
[单篇档案](2026/11/12/娱乐/dua-lipa-first-british-woman-coachella-headliner.md)

<a id="irma-p-hall-dies-aged-91"></a>

### 美国演员厄玛·P·霍尔去世，享年91岁，曾出演《灵魂食物》与《女杀手数人》

《卫报》报道，美国演员厄玛·P·霍尔去世，享年 91 岁；家人证实她于 2026 年 11 月 10 日去世。本稿记录的是已由家人确认的去世消息。

发布：上海时间2026-11-12 03:47｜[The Guardian](https://www.theguardian.com/film/2026/nov/11/irma-p-hall-actor-dies)  
[单篇档案](2026/11/12/娱乐/irma-p-hall-dies-aged-91.md)

---

<a id="tiyu"></a>

## 体育

<a id="hl-andreeva"></a>
<a id="cat-wta-finals-andreeva-sabalenka-semifinal"></a>

### 年终总决赛：安德烈耶娃 6-4、6-0 击败萨巴伦卡，首次晋级半决赛

WTA 官方报道，米拉·安德烈耶娃以 6-4、6-0 击败阿里娜·萨巴伦卡，首次晋级年终总决赛半决赛。这是已经结束的小组赛结果，半决赛尚未进行。

发布：上海时间2026-11-12 08:10｜[WTA](https://www.wtatennis.com/news/4607998/andreeva-wins-45-of-final-55-points-to-rout-sabalenka-reach-first-fage-wta-finals-semifinal)  
[单篇档案](2026/11/12/体育/wta-finals-andreeva-sabalenka-semifinal.md)

<a id="nba-nov10-celtics-blazers-knicks"></a>

### NBA：凯尔特人 123-101 击败 76 人，升至东部第一；开拓者击败雷霆

NBA.com 在 11 月 11 日的每日综述中汇总了已结束比赛的结果。凯尔特人以 123-101 击败 76 人，取得四连胜，并以 9 胜 2 负超过 76 人（9 胜 3 负），升至东部第一。保罗·乔治得到 36 分，投篮 14 中 22，三分球 6 记；杰森·塔图姆得到 21 分。波士顿全场三分球 49 投 22 中，并把杰伦·布朗限制在赛季最低的 13 分。

其他已结束的比赛还包括：开拓者 123-103 击败雷霆，达米安·利拉德 25 分，下半场以 64-44 拉开差距；尼克斯 117-85 击败雄鹿，杰伦·布伦森 23 分，卡尔-安东尼·唐斯 21 分 16 篮板，这是他本季连续第 10 场两双；热火 115-109 击败爵士；太阳 133-110 击败快船；魔术 107-100 击败国王。本稿只记录综述中已经结束的比赛，不把文中对当晚后续比赛的预告写成赛果。

发布：上海时间2026-11-11 23:48｜[NBA.com](https://www.nba.com/news/starting-5-november-11-2026)  
[单篇档案](2026/11/12/体育/nba-nov10-celtics-blazers-knicks.md)

<a id="svitolina-beats-muchova-wta-finals"></a>

### 斯维托丽娜逆转穆霍娃，年终总决赛小组赛战至1胜1负

WTA 官网报道，斯维托丽娜以 3-6、6-2、6-2 逆转穆霍娃，小组赛战绩来到 1 胜 1 负。周五对萨巴伦卡的比赛尚未开始，不能写成已经晋级。

发布：上海时间2026-11-12 06:18｜[WTA](https://www.wtatennis.com/news/4607921/elina-svitolina-comes-back-from-a-set-down-to-beat-karolina-muchova-moves-to-1-1-at-fage-wta-finals)  
[单篇档案](2026/11/12/体育/svitolina-beats-muchova-wta-finals.md)

<a id="james-anderson-signs-for-surrey"></a>

### 44岁的英格兰名将安德森离开兰开夏，签约萨里征战2027赛季

BBC Sport 报道，44 岁的詹姆斯·安德森已与萨里签约，合同针对 2027 赛季。这是已经宣布的转会签约，不是对未来比赛结果的预告。

发布：上海时间2026-11-12 17:00｜[BBC Sport](https://www.bbc.com/sport/cricket/articles/c6879g5z0v0wo)  
[单篇档案](2026/11/12/体育/james-anderson-signs-for-surrey.md)

<a id="ponga-waaka-golden-boot-2026"></a>

### 新西兰组合庞加与瓦卡分获2026年橄榄球联盟黄金靴奖男女奖项

ABC News 报道，卡林·庞加与斯泰西·瓦卡分获 2026 年橄榄球联盟黄金靴奖的男子和女子奖项。同一报道里轮椅组决赛当时尚未举行，不能写成已经完赛的冠军结果。

发布：上海时间2026-11-12 15:31｜[ABC News](https://www.abc.net.au/news/2026-11-12/kalyn-ponga-stacey-waaka-win-rugby-league-golden-boot-awards/107379252)  
[单篇档案](2026/11/12/体育/ponga-waaka-golden-boot-2026.md)

---

<a id="shehui"></a>

## 社会

<a id="ofs-university-ai-assessment-credibility"></a>

### 英格兰高等教育监管机构警告：不少大学作业可在几分钟内用 AI 完成

BBC 报道，英格兰高等教育监管机构 Office for Students（OfS）警告，过大比例的大学考核处于无人监考状态，其中许多可以在学生有限参与的情况下，用 AI 做到较高水准，有的只需几分钟，这对考核的可信度构成「重大风险」。OfS 认为，闭卷和实践考试是目前最有效的考核形式。

这项研究由 OfS 与教学发展机构 Advance HE 完成，基于至少 127 所大学的 244 名高校人员和 91 名学生的看法。研究认为，学生常常能以「无法被可靠检出」的方式使用 AI。Universities UK 回应称，许多高校已对考核做出实质调整，包括更多面考、答辩，以及在受控条件下整合 AI。这是监管机构根据师生调查提出的风险警告，不是已经测得的全系统作弊率。

发布：上海时间2026-11-11 08:21｜[BBC News](https://www.bbc.com/news/articles/cw0k0klz2x37o)  
[单篇档案](2026/11/12/社会/ofs-university-ai-assessment-credibility.md)

<a id="england-consultants-call-off-november-strike"></a>

### 英格兰顾问医生取消原定 11 月 25 日至 26 日的两日罢工，以便与政府正式谈判

《卫报》报道，英格兰医院的顾问医生（consultant）取消了原定于 11 月 25 日和 26 日举行的 48 小时罢工，因为卫生大臣同意就其诉求展开谈判。英国医学会（BMA）此前在历时 18 个月的谈判未达成关键协议后宣布行动，顾问医生已于 7 月投票支持劳工行动。

顾问医生方面关注的问题包括：自 2009–10 年度以来薪酬实际价值下降 25%，以及希望减少 10% 工时。卫生与社会保健部则明确，谈判不会让顾问医生在已获得的 2026/27 年度 3.5% 加薪之外再提高薪酬。BMA 顾问委员会联合主席表示，已得到「讨论范围没有限制」的保证，谈判计划于次周开始；同时也再次表示，若得不到认可其价值的协议，仍可能重新组织罢工。这是取消既定罢工、转入谈判，不是已经完成的加薪协议，也不是罢工已经举行。

发布：上海时间2026-11-11 22:33｜[The Guardian](https://www.theguardian.com/society/2026/nov/11/consultant-doctors-in-england-call-off-nhs-strike)  
[单篇档案](2026/11/12/社会/england-consultants-call-off-november-strike.md)

<a id="england-rivers-pfos-pfoa-drop"></a>

### 英格兰河流中两种主要“永久化学物”十年间浓度下降近三成

BBC 报道，过去十年英格兰河流中 PFOS 和 PFOA 浓度分别下降 30% 和 29%。这并不等于所有永久化学物问题已经解决。

发布：上海时间2026-11-12 08:12｜[BBC News](https://www.bbc.com/news/articles/cmze75r55g3jo)  
[单篇档案](2026/11/12/社会/england-rivers-pfos-pfoa-drop.md)

<a id="tasmania-rock-lobster-fishery-closure"></a>

### 为规避抗生素贸易风险，塔斯马尼亚部分海域将暂停商业龙虾捕捞三个月

ABC News 报道，塔斯马尼亚部分海域的商业岩龙虾捕捞将于本年 11 月 15 日至次年 2 月 14 日关闭三个月。关闭决定已经宣布，生效日期是 11 月 15 日。

发布：上海时间2026-11-12 12:18｜[ABC News](https://www.abc.net.au/news/2026-11-12/rock-lobster-closure-trade-risk-antibiotic-salmon-tasmania/107377846)  
[单篇档案](2026/11/12/社会/tasmania-rock-lobster-fishery-closure.md)

---

<a id="jiankang"></a>

## 健康

<a id="nature-clinical-preclinical-obesity-definition"></a>

### 研究称结合腰围和器官功能判断肥胖，或减少仅靠 BMI 造成的误判

《卫报》报道，医生在《自然》发表的研究认为，把体重指数（BMI）与其他身体测量和器官功能检查结合起来识别肥胖，可能在全球范围内减少数百万人被误判。研究团队利用英国、美国、中国和西班牙超过 80 万人的健康记录，对去年《柳叶刀》委员会提出的诊断思路做了检验，并追踪健康状况最长 15 年。

按这一方法，BMI 超过 40 即视为肥胖；BMI 较低者则需结合腰围或腰围身高比来判断是否有有害的过量体脂，并再区分已经损害器官功能的「临床肥胖」，以及尚无这类损害、但构成健康风险的「临床前肥胖」。研究估计，仅靠 BMI 会漏诊 5% 到 9% 的成年肥胖者，同时可能把最多约 3% 的人误判为肥胖。新定义下整体肥胖率只略升；在已属肥胖的人中，约四分之一到三分之一（相当于更广泛人群的 5% 到 10%）为临床肥胖，死亡风险明显更高。研究还称，80% 到 90% 的临床前肥胖者在随后 10 年没有进展为临床肥胖。

这是对已提出诊断框架的大样本验证，不是新的法定诊断标准，也不是某种治疗方法已经改变。通讯作者、伦敦国王学院的弗朗西斯科·鲁比诺认为，它应被用于临床，以便更准确地选择生活方式建议、GLP-1 类药物或手术等干预。

发布：上海时间2026-11-12 00:00｜[The Guardian](https://www.theguardian.com/society/2026/nov/11/bmi-alternative-obesity-diagnosis-body-mass-index)  
[单篇档案](2026/11/12/健康/nature-clinical-preclinical-obesity-definition.md)

<a id="nature-medicine-tu-stroma-ovarian-precancer"></a>

### 研究称血液中的一种 RNA 信号或有助于发现卵巢癌前病变，仍属早期研究

《卫报》援引路透社报道，研究人员在《自然-医学》发表的研究称，血液中一种名为 Tu-Stroma 的 RNA 分子，有助于识别卵巢癌发生前的微小变化。卵巢癌常始于输卵管衬里的镜下改变，这类癌前病变称为浆液性输卵管内上皮癌（STIC）。

研究称，患有该癌前病变的女性血液中 Tu-Stroma 水平升高；测量后，在受影响女性中检出了 92.3% 的 STIC，并正确识别了 98.2% 的健康女性。在有遗传风险的女性中，约 72% 的阳性结果是准确的，阴性结果则几乎全部正确。共同作者认为，这或可为高风险女性在考虑预防性手术时，提供是否已经出现癌前病变的生物学信息。

这是发表于学术期刊的研究结论，不是已经获批的筛查或诊断产品，也还不能替代现有临床决策。原文没有把它写成已经可以普遍用于常规体检。

发布：上海时间2026-11-11 21:05｜[The Guardian](https://www.theguardian.com/society/2026/nov/11/ovarian-cancer-study-early-detection-blood)  
[单篇档案](2026/11/12/健康/nature-medicine-tu-stroma-ovarian-precancer.md)

<a id="uk-sunbed-advertising-enforcement-notice"></a>

### 英国广告监管机构向日光浴床行业发出执行通知，禁止淡化致癌风险

BBC 报道，英国广告实践委员会已发出执行通知，要求日光浴床企业不得在广告中声称设备安全，也不得宣传其可以治疗疾病。这是广告监管上的执行行动，不是新的药品或诊断标准获批。

发布：上海时间2026-11-12 08:13｜[BBC News](https://www.bbc.com/news/articles/c98r7xyjx8g4o)  
[单篇档案](2026/11/12/健康/uk-sunbed-advertising-enforcement-notice.md)

---

<a id="qita"></a>

## 其他

<a id="tasmania-dft-field-swab-test"></a>

### 澳大利亚研究团队试验可在野外快速检测袋獾面部肿瘤病的口腔拭子

澳大利亚广播公司报道，塔斯马尼亚大学 Menzies 医学研究所的研究人员开发出一种便携式野外检测方法，用口腔拭子检测袋獾面部肿瘤病（DFTD）。这种疾病通过直接接触在袋獾之间传播，已使该州部分地区的袋獾数量下降约 80%。现有检测方法通常依赖可见肿瘤，结果往往需要数天。

在这次试验中，研究人员对 10 只袋獾和 3 只斑尾袋鼬做了 33 次检测；一半袋獾呈阳性，袋鼬均未呈阳性。研究负责人希望测试能在肿瘤可见之前发现疾病，为后续免疫研究和口服疫苗开发提供信息。疫苗试验仍在进行中，目前检出疾病后通常仍会把动物放归野外。这是仍在试验中的野外检测工具，不是已经全面推广的防治方案，也还没有可用的成熟疫苗。

发布：上海时间2026-11-12 03:01｜[ABC News](https://www.abc.net.au/news/2026-11-12/new-early-detection-test-for-devil-facial-tumour-disease/107371830)  
[单篇档案](2026/11/12/其他/tasmania-dft-field-swab-test.md)

<a id="ss-united-states-sunk-as-artificial-reef"></a>

### 曾创跨大西洋纪录的邮轮“美国号”在佛罗里达近海沉放，拟成世界最大人工鱼礁

NPR 报道，邮轮“美国号”已于周三在佛罗里达近海沉放，地方希望把它变成预计将是全球最大的人工鱼礁。这是已经完成的沉放作业，不是尚未举行的计划。

发布：上海时间2026-11-12 11:10｜[NPR](https://www.npr.org/2026/11/11/nx-s1-6030853/ss-united-states-artificial-reef-sinking)  
[单篇档案](2026/11/12/其他/ss-united-states-sunk-as-artificial-reef.md)

<a id="koonibba-indigenous-observatory-opens"></a>

### 南澳大利亚偏远原住民社区开设自有观星台，用于讲述星空中的传统故事

ABC News 报道，南澳大利亚库尼巴社区已开设一座由社区所有并运营的观星台。旅游项目在报道中仍被写成未来计划，需要与已经完成的开幕和培训报名区分开。

发布：上海时间2026-11-12 12:31｜[ABC News](https://www.abc.net.au/news/2026-11-12/koonibba-star-observatory-paves-way-for-indigenous-storytelling/107372096)  
[单篇档案](2026/11/12/其他/koonibba-indigenous-observatory-opens.md)

---

## 阅读说明

本期独立新闻 43 条，15 个来源，其中 AI 17 条。首页按独立事件计数。重点区和栏目里出现两次的，仍然是一条。

来源给出钟点时，这里只写上海时间；原时区与时间依据写在单篇档案里。只有日期、没有钟点的，不补时分。页面未标明时区的钟点，不换算成已确认的上海时间。JSON-LD 若明显是午夜或正午整点占位，不当作真实钟点。

本期 15 个来源的计法：谷歌官方博客、DeepMind 博客与 Google Developers Blog 计为一家「谷歌」；OpenAI 早间两条与晚间帮助中心稿计为一家；GitHub Blog 的安全公告与 Changelog 计为一家；BBC News 与 BBC Sport 计为一家；The Guardian 各条计为一家；微软 Visual Studio Blog 与 Foundry 博客计为一家「微软」。WTA、NBA.com、ABC News 延续早间已计入。晚间新计入 Anthropic、Databricks、Amazon Web Services（两条计为一家）、The Verge（两条计为一家）、IBM Newsroom、NPR。

厂商基准和内部测试成绩写成公司陈述，不是独立复核结论。健康条目保留研究或试验阶段和原文里的限制。

稳定版块是：AI、科技、搞笑、财经、娱乐、体育、社会、健康、其他。AI 单独成栏，不并入科技。这一栏看热门产品与工具，尤其是 ChatGPT、Codex、Claude Code（CC）、Cursor、Grok Bot、DeepSeek，以及同级别的助手和编程工具。单篇放在 `YYYY/MM/DD/AI/`。

仅展示审核通过内容。

本页是 GitHub 上的 Markdown，不是独立网站。更新时间：上海时间 2026-11-12 18:34。
