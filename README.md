# 2026年11月13日 · 海外资讯日报

上海时间 **2026-11-13 10:03** 更新。独立新闻 **22** 条，**14** 个来源，其中 AI **10** 条。仅展示审核通过内容。

这是 11 月 13 日的早间日报，是新的一天，不是 11 月 12 日晚间那一版的增量。本窗口内，Cursor 官方博客仍停在 11 月 10 日的 Projects 多人协作，changelog 仍停在 11 月 6 日的 Voice Chat；DeepSeek 与 xAI / Grok Bot 官方新闻室没有新的产品稿。OpenAI 新闻室当时没有挂出带日期的 Daybreak 专稿，相关一条以 The Register 的见报时间为准，并对照了官方产品页。

来源按不重复出口计算，共 14 家。谷歌官方博客的 Gemini 4 Hydrogen 与 Google Developers Blog 的 Agent Anomaly Detection 计为一家「谷歌」。Amazon Web Services 的 AgentCore 下一代运行时与 SGLang-Neuron 两条计为一家。BBC News 与 BBC Sport 计为一家。其余各计一家：The Register、Anthropic（Claude Code GitHub Releases）、Databricks、The Verge、IBM（Hugging Face 上的 Granite/LLMON 博文）、Salesforce（Hugging Face 上的 SOV-Transcribe-1 博文）、The Guardian、美国全国房地产经纪人协会（NAR）、WTA、NBA.com、美国癌症协会（ACS）。

[当日完整版](2026/11/13/日报.md) · [往期索引](ARCHIVE.md)

---

## 今日重点

五条展开。下面各栏是短读，重点条目在栏里只留一句。

<a id="hl-hydrogen"></a>

### 1. Google 发布 Gemini 4 Hydrogen，面向日常编程与智能体工作流

Google DeepMind 于 11 月 12 日宣布推出 Gemini 4 Hydrogen，把它定位成面向日常编程和多种智能体工作流的快速执行模型，与更侧重长程推理的 Gemini 4 Carbon、Gemini 4 Argon 搭配使用。

官方称，该模型即日起向 Google AI Studio 与 Gemini API 的各档用户、Gemini for business、Gemini 应用、Google Search，以及付费的 Google AI Pro 和 Ultra 在 Google Antigravity 中的用户滚动推出。Gemini 应用里的免费用户，不是都能在模型列表中手动点选 Hydrogen，而是在自动选模、任务适合时用到它。

API 价格按整个 100 万 token 上下文窗口统一计算，不随窗口长度分段改价：每百万输入 token 1.50 美元，输出 7.50 美元。思考深度有 low、medium、默认的 high，以及新增的 xhigh 四档。同一时期，Antigravity 加入 Orchestrator，可以在同一次会话里于 Carbon 与 Hydrogen 等模型之间动态切换。

文中的速度、基准和安全数字，都是 Google 自己或合作伙伴的测试，不是独立审计。

为何关注：这是 Gemini 4 家族面向更广用户群的中坚型号，也关系到 Search 与 Antigravity 的默认体验；若日常编码或智能体任务从 3.8 Flash 迁移，需要自行核对其宣称的速度与可靠性。

发布：上海时间2026-11-13 02:00｜[Google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)  
[单篇档案](2026/11/13/AI/google-gemini-4-hydrogen.md)

---

<a id="hl-ms365"></a>

### 2. 微软365全球故障，Outlook与Teams等服务持续受阻

英国广播公司报道，微软正在全力修复一场影响 Microsoft 365 在线办公套件的全球故障，Outlook、Teams 以及 Copilot 等服务出现连接问题。截至这篇稿件可见的更新，故障仍在处置，不是已经完全恢复。

微软在社交媒体上表示，部分服务器“意外不可用”，导致其余系统承压，并称正在“积极寻找各种途径以减轻影响”。发言人感谢用户耐心，同时警告一些已经恢复的服务“可能再次无响应”，任何地区的客户都可能受影响。

监测网站 Downdetector 的数据显示，Outlook 故障报告在周四约 18:00 GMT 前后达到全球峰值，接近 14 万条，美国、日本和新加坡等地都有用户反映中断。BBC 称，目前没有迹象表明故障由网络攻击引起。

文章还写明，Anthropic 与 OpenAI 都在排查与微软系统相关的连接问题。电动卡车制造商 Workhorse Group 表示，因业务中断，把原定 11 月 12 日公布的三季度业绩推迟到 16 日。业绩推迟是该公司自己的说明。

为何关注：微软 365 是许多企业与机构日常通信和协作的基础设施，此次故障范围广、持续时间长，并可能反复出现中断。

发布：上海时间2026-11-13 04:25（首次发表；页面修改时间对应上海时间 09:39）｜[BBC News](https://www.bbc.com/news/articles/c5gm3g9ldz8xo)  
[单篇档案](2026/11/13/科技/microsoft-365-outlook-teams-outage.md)

---

<a id="hl-cc-codemode"></a>

### 3. Claude Code 2.1.323 增加实验性 Code Mode，可用 JavaScript 调用工具

Anthropic 于 11 月 12 日发布 Claude Code 正式版 v2.1.323。发布说明称，新增的 Code Mode 是实验性功能，需要主动打开：Claude 会编写 JavaScript 来调用它的工具。个人可以打开或关闭，组织也可以统一关掉。

同一版本还在 plugin.json 中加入 engines["claude-code"] 的版本范围约束。超出范围的插件不会被安装、更新或加载。claude plugin validate 也增加了 TypeScript hooks 的类型检查等插件校验。

其余大量条目是权限、沙箱、后台会话登录和终端显示方面的修复，不在这里逐条展开。Code Mode 的专门文档页返回 404，细节只以这条 GitHub 发布说明为准。

为何关注：这是本窗口内 Claude Code 的实际产品更新，但 Code Mode 仍是实验性选择加入功能，组织可以关闭；不宜理解成默认工作方式已改变。

发布：上海时间2026-11-13 06:12｜[GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.323)  
[单篇档案](2026/11/13/AI/claude-code-2-1-323-code-mode.md)

---

<a id="hl-daybreak"></a>

### 4. OpenAI 推出 Daybreak Red Team 与 Defense Factory 两款安全产品

据 The Register 对 OpenAI 周四主题演讲的报道，公司推出 Daybreak 安全平台下的两款产品：Daybreak Red Team 与 Daybreak Defense Factory。

Red Team 处于 early access。它用一组智能体，结合源代码和应用上下文，对网页应用做持续渗透测试，并帮助核对扫描器、漏洞赏金和披露报告里的漏洞，再检验补丁是否有效。Defense Factory 把“发现、验证并修复漏洞”的循环自动化：智能体扫描代码库并起草补丁，由工程师审阅批准后才进入生产。报道称，工程师会拿到带测试、可以合并的 pull request。

OpenAI 官方产品页与上述能力描述一致，并写到 Defense Factory 可以结合 Codex 审阅补丁，Red Team 用隔离环境，以及用 Guardian 审查来限制智能体能够到达的范围。这些产品页没有发布日期。OpenAI 新闻室截至核验也没有刊登带日期的专稿，所以本条以 The Register 的见报时间为准。这不是 2026 年 8 月关于 Daybreak 访问层级的旧公告，目前也还没有对所有人开放。

为何关注：这是 OpenAI 把网络安全模型做成面向企业的渗透测试与自动修复产品，和此前已报道的 Control Room、Daybreak 访问层级不是同一件事；目前仍须经批准使用，且 Red Team 尚为 early access。

发布：上海时间2026-11-13 04:48｜[The Register](https://www.theregister.com/security/2026/11/12/openai-launches-security-products-tells-orgs-theyre-doomed-if-they-dont-use-them/5309500)  
[单篇档案](2026/11/13/AI/openai-daybreak-red-team-defense-factory.md)

---

<a id="hl-homesales"></a>

### 5. 美国10月成屋销售降至2010年8月以来最低

美国全国房地产经纪人协会（NAR）11 月 12 日发布的成屋销售报告显示，10 月成屋销售按季调年率计算为 375 万套，较 9 月下降 5.5%，较 2025 年 10 月下降 8.8%。

NAR 首席经济学家 Lawrence Yun 表示，30 年期抵押贷款利率已升至 2000 年以来的最高水平，只有 2023 年有一个月更高，“因此房屋销售降至 2010 年 8 月以来最低”。10 月成屋销售中位价为 41.67 万美元，同比上升 0.4%，为连续第 40 个月同比上涨。待售库存增至 159 万套，相当于 5.1 个月的供应量。

分地区看，中西部、南部和西部销售环比下降，东北部环比持平，四个地区同比都下降。报告引用房地美的数据称，10 月 30 年期固定抵押贷款平均利率为 7.33%，高于 9 月的 6.86% 和一年前的 6.25%。Yun 同时指出，目前困境类交易只约占全部成交的 2%；若抵押贷款利率回落，可能释放被压抑的需求。

为何关注：成屋约占美国住房交易的九成以上，这份官方月报直接反映高利率环境下的成交量、房价和可负担性。

发布：上海时间2026-11-12 23:00｜[NAR](https://www.nar.realtor/newsroom/existing-home-sales-decreased-5-5-percent-october-nar-report)  
[单篇档案](2026/11/13/财经/us-existing-home-sales-october-2026.md)

---

## 栏目

[AI](#ai) · [科技](#keji) · [搞笑](#gaoxiao) · [财经](#caijing) · [娱乐](#yule) · [体育](#tiyu) · [社会](#shehui) · [健康](#jiankang) · [其他](#qita)

<a id="ai"></a>

## AI

<a id="cat-google-gemini-4-hydrogen"></a>

### Google 发布 Gemini 4 Hydrogen，面向日常编程与智能体工作流

已在[今日重点](#hl-hydrogen)展开。Gemini 4 Hydrogen 即日起滚动推出，免费应用用户靠自动选模在适合时用到，API 对整个 100 万 token 窗口统一计价。

发布：上海时间2026-11-13 02:00｜[Google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)  
[单篇档案](2026/11/13/AI/google-gemini-4-hydrogen.md)

<a id="cat-openai-daybreak-red-team-defense-factory"></a>

### OpenAI 推出 Daybreak Red Team 与 Defense Factory 两款安全产品

已在[今日重点](#hl-daybreak)展开。Red Team 仍是 early access，Defense Factory 的补丁要先经工程师审阅才会进入生产，并不是已经对所有人开放。

发布：上海时间2026-11-13 04:48｜[The Register](https://www.theregister.com/security/2026/11/12/openai-launches-security-products-tells-orgs-theyre-doomed-if-they-dont-use-them/5309500)  
[单篇档案](2026/11/13/AI/openai-daybreak-red-team-defense-factory.md)

<a id="cat-claude-code-2-1-323-code-mode"></a>

### Claude Code 2.1.323 增加实验性 Code Mode，可用 JavaScript 调用工具

已在[今日重点](#hl-cc-codemode)展开。Code Mode 是实验性、需要主动开启的功能，组织可以关闭；同版本还明确了插件引擎的版本约束和校验。

发布：上海时间2026-11-13 06:12｜[GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.323)  
[单篇档案](2026/11/13/AI/claude-code-2-1-323-code-mode.md)

<a id="databricks-genie-in-slack-ga"></a>

### Databricks 宣布 Slack 中的 Genie 应用正式商用

Databricks 宣布，Databricks Genie 的 Slack 应用即日起正式商用。用户可以在 Slack 里直接私信 Genie，或在已经加入的频道里 @ 提及它；回复出现在对应线程或私信中，并引用所依据的来源。

每次提问都以提问者的身份运行，沿用 Unity Catalog 以及已连接数据源的权限。频道可以选择把回答公开给整个频道，或只私发给提问者，工作区管理员可以设定默认值。通过 MCP 连接器，Genie 可以在用户批准后创建或更新文档、在工单上评论或修改记录，也可以按日程重复跑分析、在线程里分享图表，并处理上传的文件。频道默认可以走 Genie One，在数据资产之间路由问题，也可以固定到某一个 Genie Agent。基于上下文的入站策略可用于 Private Link 工作区。

Slack 里的 Genie 应用这次宣布正式商用，与 11 月 12 日已刊、仍待预览的第二代常开 Genie 不是同一件事。

为何关注：这是把已有的受治理问答能力放到 Slack 里并宣布正式商用，和企业日常提问直接相关；不要与此前仍处预览的常开、第二代 Genie 混为一谈。

发布：上海时间2026-11-12 23:00｜[Databricks](https://www.databricks.com/blog/genie-slack-now-generally-available-governed-ai-cowork-right-where-work-happens)  
[单篇档案](2026/11/13/AI/databricks-genie-in-slack-ga.md)

<a id="aws-agentcore-runtime-next-gen"></a>

### Amazon Bedrock AgentCore 下一代运行时成为新建运行时的默认选项

AWS 宣布更新 Amazon Bedrock AgentCore 的运行时。每个会话仍在独立的 Firecracker 微虚拟机里运行。官方称，新版会话启动最快可以到大约 15 倍，计算规格最高扩大到 4 倍（8 个 vCPU、32 GB 内存），并支持最大 10 GB 的容器镜像。What’s New 还给出公司自己的测试：在 2 GB 镜像上，P75 启动时间从 29.7 秒降到 2 秒以内。

运行时会在智能体空闲后缩到零，并在内存释放后的数分钟内回收。官方称，多轮会话最多可以减少大约 68% 的内存用量。会话还可以动态挂载文件系统，例如带 FUSE 的 S3，把数据留在同一信任边界内。What’s New 写明：自即日起，所列多个区域里新建的 runtime 默认使用这一代；已经存在的 runtime 仍留在旧版本，直到把 platformVersion 设为 V2。

上述性能和用量数字都是 AWS 或其客户的表述，不是独立审计。这也不是此前已经报道的 AgentCore Web Search API 正式商用。

为何关注：智能体要在生产里长时间跑代码、浏览器或本地模型，隔离、冷启动和按实际使用计费往往比模型本身更先成为瓶颈；现有工作负载不会自动升级，需要主动切到 V2。

发布：上海时间2026-11-13 01:59｜[Amazon Web Services](https://aws.amazon.com/blogs/machine-learning/run-agents-securely-and-efficiently-with-the-next-generation-agentcore-runtime/)  
[单篇档案](2026/11/13/AI/aws-agentcore-runtime-next-gen.md)

<a id="aws-sglang-neuron-trainium"></a>

### AWS 与 RadixArk 推出 SGLang-Neuron，可在 Trainium 上按 SGLang 接口提供模型服务

Amazon 宣布 SGLang-Neuron 已公开发布，可以通过 AWS Deep Learning Container 获取，由 RadixArk 与 Annapurna Labs 合作推出。开发者可以在 AWS Trainium 上沿用现有的 SGLang 服务接口来提供模型，并生成强化学习的 rollout。

服务启动后仍使用同样的生成 API。底层走原生 PyTorch，并用仓库外插件把 Trainium 支持与 SGLang 核心拆开。设置 SGLANG_PLATFORM=neuron 即可选用这一平台。插件负责模型、注意力、MoE 和计算图运行，也支持预填充与解码分离，通过 NIXL 经 Elastic Fabric Adapter 传递 KV cache。

文章给出了在 Trainium3 的 EC2 实例上，用 pytorch-inference-sglang-neuronx 容器启动并调用 openai/gpt-oss-120b 的示例，并指向入门指南和代码库文档。

为何关注：如果团队已经在用 SGLang 做推理或强化学习，这提供了一条不必重写服务栈、把工作放到 Trainium 上的官方路径。

发布：上海时间2026-11-13 06:03｜[Amazon Web Services](https://aws.amazon.com/blogs/machine-learning/deploy-frontier-ai-models-on-aws-trainium-with-sglang-neuron/)  
[单篇档案](2026/11/13/AI/aws-sglang-neuron-trainium.md)

<a id="google-agent-anomaly-detection-benchmarks"></a>

### Google 公布 Agent Anomaly Detection 在外部安全基准上的测试结果

Google 工程师在开发者博客介绍 Agent Anomaly Detection（AAD）。这项功能今年 9 月已在 Gemini Enterprise Agent Platform 以 Private Preview 推出。这次用五份不是谷歌编写的公开智能体安全基准做了测试。AAD 异步读取 OpenTelemetry 追踪和日志，不给运行时增加延迟，用来标出智能体偏离预期边界的会话。

官方称，模型本身大约一半的有害指令没有被执行；在已经执行的有害指令里，AAD 标出了 87%。误报率随工具而不同，大约落在良性会话的 2% 到 16%。对写进长期记忆的攻击最弱：18 次造成实际行为的案例里只抓住 4 次。基准包括 AgentDojo、InjecAgent、Agent Security Bench、AgentDyn 和 AgentHarm，一共 1,774 个会话。

作者也写出限制：只用了一种智能体模型，任务是模拟应用，大约 6% 的会话没有返回结果。该功能仍是 Private Preview。文中数字是 Google 自己复现公开基准的结果，不是独立审计。

为何关注：智能体目标劫持已被列为主要风险之一；这份测试刻意不用自家题目，但功能尚未正式商用，且对投毒记忆一类攻击仍然薄弱。

发布：上海时间2026-11-12（页面仅有日期，钟点未核验）｜[Google Developers Blog](https://developers.googleblog.com/how-agent-anomaly-detection-scores-on-benchmarks-we-didnt-write/)  
[单篇档案](2026/11/13/AI/google-agent-anomaly-detection-benchmarks.md)

<a id="verge-chatbots-risky-shopping-sites"></a>

### 测试称 Gemini、ChatGPT、Perplexity 购物回答会链到风险网站

The Verge 独家报道了知识产权保护公司 Podqi 的一项测试。9 月的两个测试周期里，Podqi 用自拟的购物问题询问 Gemini、ChatGPT 和 Perplexity，涉及 151 个品牌、共 6,795 条回答。它把风险网站定义为仿冒或售假站点、被他人重新注册的过期品牌域名，以及已经失效、但可能被抢注的死链。

结果是，Gemini 有 4% 的回答出现风险网站，ChatGPT 为 8%，Perplexity 为 15%。ChatGPT 在给出风险链接时提出警告的比例最高，为 24%。与较大品牌相关的查询，出现风险站点的频率大约是较小品牌的一半。Google、OpenAI 和 Perplexity 都回应称，重视信息质量，或正在改进防护。

这是一家商业公司用自己编写的提示做的测试，并由它独家提供给 The Verge，不是独立的学术审计。

为何关注：节日购物季前后，用聊天机器人找店、比价时仍应核对官方域名，不宜把模型给出的购买链接直接当作可信来源。

发布：上海时间2026-11-13 01:00｜[The Verge](https://www.theverge.com/ai-artificial-intelligence/1032020/gemini-chatgpt-perplexity-shopping-test-risky-fake-websites-citations)  
[单篇档案](2026/11/13/AI/verge-chatbots-risky-shopping-sites.md)

<a id="ibm-granite-llmon-preview"></a>

### IBM 发布实验性 LLMON 标记语言及 Granite 4.1 预览模型

IBM Granite 团队在 Hugging Face 博客宣布 LLMON（LLM Object Notation）。这是一种面向语言模型的标记格式，用保留的特殊 token 把指令、数据、约束和执行块分开，想把上下文里的结构说清楚。同时发布的两款实验性预览模型，从 Granite 4.1 基座衍生而来：granite-4.1-3b-LLMON-preview 与 granite-4.1-8b-LLMON-preview，工具库和示例开源。

官方称，在 OPI 等针对静态间接提示注入的基准上，LLMON 模型大多会忽略藏在用户数据里的指令，攻击成功率可以降到接近零，通用能力则与 Granite 4.1 Instruct 大致持平。这些抗注入和能力数字都是 IBM 自己的评估。文章写明，这是 experimental preview，可供探索和评测，不适合生产环境。

为何关注：把指令和数据在格式上分开，是应对间接提示注入的一条技术路线；但目前仍是预览，且主要针对静态注入，作者也提到自适应、多轮攻击仍在研究。

发布：上海时间2026-11-13 03:07｜[IBM（Hugging Face）](https://huggingface.co/blog/ibm-granite/llmon-an-llm-native-markup-language-now-in-granite)  
[单篇档案](2026/11/13/AI/ibm-granite-llmon-preview.md)

<a id="salesforce-sov-transcribe-1"></a>

### Salesforce 开源发布 SOV-Transcribe-1 语音转写模型

Salesforce 的 Missionforce Sovereign AI 团队宣布开源 SOV-Transcribe-1。这是一款非流式自动语音识别的开权模型，采用 Apache 2.0 许可，总参数约 260 亿，激活约 40 亿。官方介绍，它面向电话号码、邮箱等实体，也面向口音和噪声环境，并支持用自然语言指令控制转写风格，以及用关键词做上下文偏置。权重已在 Hugging Face 发布。

文章给出的排名和误差率，包括截至 2026 年 11 月 12 日在 Artificial Analysis 的开权非流式语音转写中列第一、整体第七，以及 VoiceCodeBench 等结果，都是该公司引用的基准或自己的评测，不是独立审计。

为何关注：对企业想在自有基础设施上做通话转写或语音智能体的团队，这是又一个可自行部署的开权选项；具体质量仍需用自己的音频复查厂商榜单。

发布：上海时间2026-11-13 00:43｜[Salesforce（Hugging Face）](https://huggingface.co/blog/salesforce-sovereign-intelligence/sov-transcribe-1)  
[单篇档案](2026/11/13/AI/salesforce-sov-transcribe-1.md)

---

<a id="keji"></a>

## 科技

<a id="cat-microsoft-365-outlook-teams-outage"></a>

### 微软365全球故障，Outlook与Teams等服务持续受阻

已在[今日重点](#hl-ms365)展开。截至 BBC 这篇稿的更新，微软仍在修复 365 故障，部分已恢复的服务可能再次无响应，Anthropic 与 OpenAI 都在排查相关连接问题。

发布：上海时间2026-11-13 04:25（首次发表；页面修改时间对应上海时间 09:39）｜[BBC News](https://www.bbc.com/news/articles/c5gm3g9ldz8xo)  
[单篇档案](2026/11/13/科技/microsoft-365-outlook-teams-outage.md)

---

<a id="gaoxiao"></a>

## 搞笑

本期暂无通过审核的稿件。

---

<a id="caijing"></a>

## 财经

<a id="poundland-creditor-protection-extended"></a>

### Poundland获高院延长债权人保护两周，以求达成救援交易

《卫报》报道，英国廉价连锁超市 Poundland 的管理层周四上午获得高等法院批准，把已经申请的债权人保护再延长 10 个工作日。这不是第一次申请。公司表示，门店在此期间照常营业，救援交易尚未谈成。

Poundland 约有 1.2 万名员工，在英国和爱尔兰经营约 600 家门店。美国业主 Gordon Brothers 声明，支持再延长 10 个工作日，并确认会拨出资金，保证本月员工工资足额发放，同时继续为日常经营提供资金。该股东称，正在与三方谈判整体出售，也收到多家成熟高街零售商收购部分业务的报价。它仍倾向整体出售，但会核验买方是否有足够资金完成收购，并恢复可持续的现金流。

Gordon Brothers 还称，已提供约 8500 万英镑融资，据报是只动用了部分额度的资产抵押贷款。此外还有它去年以名义 1 英镑接手这项业务时基本承担下来的 3000 万英镑股东贷款。

为何关注：保护期延长关系到员工、供应商和门店能否在救援谈判的窗口内维持经营，但交易能否谈成仍不确定。

发布：上海时间2026-11-12 21:45｜[The Guardian](https://www.theguardian.com/business/2026/nov/12/poundland-owner-secures-two-extra-weeks-ensure-retail-chains-survival)  
[单篇档案](2026/11/13/财经/poundland-creditor-protection-extended.md)

<a id="burberry-returns-to-profit-h1-2026"></a>

### Burberry半年扭亏为盈，中国与美洲销售带动增长

英国奢侈品牌 Burberry 公布，截至 2026 年 9 月 26 日的六个月，税前利润为 1900 万英镑，上年同期为亏损 4800 万英镑。同期销售额升至 11 亿英镑，同比增长 6%。

首席执行官 Joshua Schulman 称，公司在“充满挑战的奢侈品市场”中实现增长。线上与批发在中国和美国表现较好：中国销售增长 15%，美洲增长 14%，欧洲、中东和非洲下降 1%。他把策略概括为覆盖不同价位的“定价金字塔”，从约 85 英镑的棉羊绒袜、195 英镑起的围巾，到可能超过 9000 英镑的皮革大衣。轻便外套、热带华达呢雨衣，以及 Cotswold 系列格纹皮包较受欢迎。

他还表示，全球旅游业走弱影响了折扣店销售，但各地本地顾客在旗舰店的支出仍有支撑。公司也加大了针对中国情人节和农历新年等本地节点的投入。这些是公司公布的中期业绩和管理层说法。

为何关注：这是一家代表性英国奢侈品牌在行业需求偏弱时的中期业绩，显示其转向经典单品与分层定价后的最新经营结果。

发布：上海时间2026-11-12 19:03｜[The Guardian](https://www.theguardian.com/business/2026/nov/12/burberry-profit-sales-socks-bags-china-us)  
[单篇档案](2026/11/13/财经/burberry-returns-to-profit-h1-2026.md)

<a id="cat-us-existing-home-sales-october-2026"></a>

### 美国10月成屋销售降至2010年8月以来最低

已在[今日重点](#hl-homesales)展开。NAR 称 10 月成屋销售按季调年率为 375 万套，降到 2010 年 8 月以来最低。

发布：上海时间2026-11-12 23:00｜[NAR](https://www.nar.realtor/newsroom/existing-home-sales-decreased-5-5-percent-october-nar-report)  
[单篇档案](2026/11/13/财经/us-existing-home-sales-october-2026.md)

---

<a id="yule"></a>

## 娱乐

<a id="duran-duran-roger-taylor-leaves-tinnitus"></a>

### 杜兰杜兰鼓手罗杰·泰勒因耳鸣加重宣布离队

BBC 报道，英国乐队 Duran Duran（杜兰杜兰）鼓手罗杰·泰勒宣布，因耳鸣持续加重而离队。现年 66 岁的泰勒自 1978 年乐队在伯明翰组建起担任鼓手。他说，在这支乐队打鼓是“我一生的喜悦”，但已经“到了必须听从自己的身体和医生的时候”。

乐队其他成员西蒙·勒·邦、尼克·罗兹和约翰·泰勒说，这一决定是在审慎考虑和医疗建议之后作出的，保护听力和长期健康现在必须放在首位。泰勒曾于 1985 年离队，2001 年回归。他表示，乐队刚结束一轮非常成功的英国和欧洲巡演，此前还第二次在 BST 海德公园担任头条、进入摇滚名人堂，并与尼罗·罗杰斯回到录音室，自己是“在真正的高点离开”。乐队声明称完全支持他的决定，并说他“将永远是这个大家庭的一部分”。

为何关注：泰勒是这支国际知名乐队的创始鼓手之一，因健康原因结束与乐队的现阶段合作，是流行音乐界的一条明确人事新闻。

发布：上海时间2026-11-13 03:00｜[BBC News](https://www.bbc.com/news/articles/crwy499k504do)  
[单篇档案](2026/11/13/娱乐/duran-duran-roger-taylor-leaves-tinnitus.md)

<a id="golden-joystick-awards-2026-resident-evil-requiem"></a>

### 《生化危机：安魂曲》获金摇杆奖最佳游戏等多项大奖

BBC 报道，卡普空今年 2 月发行的《生化危机：安魂曲》（Resident Evil Requiem）在周三的金摇杆奖上成为获奖最多的作品。颁奖典礼是 11 月 11 日，BBC 这篇报道刊于周四。

该作获得年度最佳游戏、年度最佳主机游戏、最佳游戏预告片，以及最佳主角表演，由安吉拉·桑塔阿尔巴诺饰演格蕾丝·阿什克罗夫特。卡普空同时获评年度最佳工作室，《鬼武者：剑之道》和《Pragmata》等作品也获得认可。年度最佳游戏由公众投票产生，该作得票率约 17%，高于《Phantom Blade Zero》《Crimson Desert》等提名。

独立游戏《Meccha Chameleon》获得最佳多人、最佳自制独立游戏，以及由专业评选的主播选择奖和开发者选择奖。评论选择奖颁给澳大利亚工作室 House House 的《Big Walk》。观众票选的“最期待游戏”是《巫师 4》。

为何关注：金摇杆奖是以玩家票选为主的年度游戏奖，结果反映了今年相对受欢迎的作品和制作公司。

发布：上海时间2026-11-12 20:35｜[BBC News](https://www.bbc.com/news/articles/cmg46y76kz5no)  
[单篇档案](2026/11/13/娱乐/golden-joystick-awards-2026-resident-evil-requiem.md)

---

<a id="tiyu"></a>

## 体育

<a id="wta-finals-gauff-pegula-noskova-semifinals"></a>

### 高芙击败科斯秋克仍出局，佩古拉与诺斯科娃晋级WTA总决赛四强

WTA 官网报道，在印第安维尔斯举行的 FAGE WTA 年终总决赛第一小组最后一轮中，两场比赛都已经结束。科科·高芙以 6-4、7-5 逆转战胜玛尔塔·科斯秋克，小组赛战绩为 2 胜 1 负。随后杰西卡·佩古拉以 7-6（2）、4-6、7-5 击败琳达·诺斯科娃，高芙仍然无缘半决赛。

三人同为 2 胜 1 负，最后按盘分计算：诺斯科娃 5-2，排小组第一；佩古拉 5-3，拿到第二个四强名额；高芙为 4-3。高芙在第二盘一度 0-3 落后，并因下背部紧张接受医疗暂停，随后又落到 1-5，但连赢六局完成逆转。她在赛后说，第二盘一度进入心流，本来准备打满三盘。官文还指出，高芙首轮对佩古拉时曾有机会直落两盘结束，佩古拉逼出第三盘并拿下该盘，这是她在盘分上占优的关键。

这是第一小组出线结果的最终确定，不是前两日已经刊出的安德烈耶娃或斯维托丽娜那场比赛。

为何关注：这是年终总决赛小组出线名额的最终确定，两场已经结束的比赛改写了第一小组的半决赛名单。

发布：上海时间2026-11-13 04:48（首次发表；页面修改时间对应上海时间 09:13）｜[WTA](https://www.wtatennis.com/news/4608404/gauff-kostyuk)  
[单篇档案](2026/11/13/体育/wta-finals-gauff-pegula-noskova-semifinals.md)

<a id="nba-starting-5-november-12-2026"></a>

### NBA综述：马刺十连胜，骑士客场击败尼克斯

NBA 官网 11 月 12 日的 Starting 5 综述了周三已经结束的 10 场比赛。圣安东尼奥马刺在第二节一度落后 22 分，最终 124-119 逆转芝加哥公牛，连胜扩大到 10 场。维克托·文班亚马得到 32 分、9 个篮板、5 次盖帽。洛杉矶湖人 123-112 战胜密尔沃基雄鹿，取得七连胜；奥斯汀·里夫斯在第三节一次扣篮尝试后，疑似左脚跟受伤离场。

休斯敦火箭 115-108 击败金州勇士，中断对方的八连胜。斯蒂芬·库里在第一节因腹部酸痛退赛，没有回到场上。波特兰开拓者 118-108 再胜俄克拉荷马城雷霆，官方写明这是连续两晚的第二次击败对手。波士顿凯尔特人 98-93 逆转多伦多猛龙，取得五连胜。克利夫兰骑士 115-107 在客场击败纽约尼克斯，中断其四连胜，詹姆斯·哈登得到 32 分。

同夜还有掘金 123-118 胜灰熊、魔术 123-108 胜爵士、篮网 145-111 胜鹈鹕、步行者 114-101 胜奇才。文中对周四和周五比赛的预告不记为赛果。这也是 11 月 11 日那篇已刊 Starting 5 之后的新一轮已完成比赛。

为何关注：这是相对 11 月 11 日那篇已刊 Starting 5 之后的新一轮已完成赛果。

发布：上海时间2026-11-12 23:10｜[NBA.com](https://www.nba.com/news/starting-5-november-12-2026)  
[单篇档案](2026/11/13/体育/nba-starting-5-november-12-2026.md)

<a id="italy-3-1-france-nations-league"></a>

### 意大利3-1逆转法国，齐达内首尝国家队败绩

BBC 体育确认，意大利在米兰圣西罗球场的欧洲国家联赛 A 级第一组比赛中，以 3-1 逆转法国。这场比赛已经结束，也是齐达内执教法国队后的第一场失利。

法国第 10 分钟先由迈克尔·奥利斯破门，他抓住了吉安路易吉·唐纳鲁马的传球失误。皮奥·埃斯波西托第 26 分钟近门扳平，达维德·弗拉泰西第 63 分钟打进第二球，皮奥·埃斯波西托又在第 75 分钟罚入点球，完成梅开二度。塞巴斯蒂亚诺·埃斯波西托此前罚失过一粒点球。BBC 写明，这是意大利自 1962 年以来第一次在主场击败法国。皮奥·埃斯波西托前 14 次代表国家队已经打入 9 球。

两队目前同为 10 分，意大利因相互交锋占优排在小组第一。周日末轮他们将分别对阵比利时和土耳其，那是尚未进行的赛程，小组前两名晋级四分之一决赛。同组的比利时当晚以 2-1 逆转土耳其，积 9 分，排在第三。比利时这场也已经结束。

为何关注：这是欧洲国家联赛小组出线形势里一场已经踢完的关键战，也是齐达内上任后法国队的第一场失利。

发布：上海时间2026-11-13 06:41｜[BBC Sport](https://www.bbc.com/sport/football/live/c3rrygq0z2y2t)  
[单篇档案](2026/11/13/体育/italy-3-1-france-nations-league.md)

---

<a id="shehui"></a>

## 社会

<a id="roman-emperor-statue-scottish-borders"></a>

### 研究认为苏格兰曾竖立镀金罗马皇帝骑马巨像

BBC 报道，苏格兰国家博物馆的新研究认为，1820 年在霍伊克附近米尔辛顿沼泽发现的青铜小腿，并不像此前推测的那样，是从约克等更南方地点掠来的战利品，而更可能来自一尊竖立在今天苏格兰南部、纪念安东尼·庇护征服该地的镀金骑马巨像。这是研究者的看法，不是已经定案的结论。出土是 1820 年的事，这篇报道说的是现在这项研究。

博物馆史前与罗马考古首席策展人弗雷泽·亨特表示，这“彻底扭转了我们对罗马第二次尝试征服苏格兰的理解”。研究者指出，残件大约可追溯到公元 140 年。腿部顶端没有砍切痕迹，保持铸造时的样子；镀金在膝部附近缺失，显示原来被长袍或斗篷盖住。这更像罗马撤离时对贵重雕像的谨慎拆卸和掩埋，而不是战后泄愤式的砸毁。

这是目前已知苏格兰境内唯一的此类雕像残件，将按残存的腿部进行复原，并列入 11 月 14 日至 4 月 18 日在爱丁堡举办的“Roman Scotland: Life on the Edge of Empire”展览。展览尚未开幕。亨特也提出仍然没有答案的问题：雕像的其余部分在哪里。

为何关注：若这一解读成立，将改变对罗马不列颠北部纪念性雕像分布及其撤离方式的既有认识，并有新展览向公众展示复原成果。

发布：上海时间2026-11-12 14:02｜[BBC News](https://www.bbc.com/news/articles/cx5y139gyqzmo)  
[单篇档案](2026/11/13/社会/roman-emperor-statue-scottish-borders.md)

---

<a id="jiankang"></a>

## 健康

<a id="acs-prostate-cancer-screening-guideline-2026"></a>

### 美国癌症协会更新前列腺癌筛查指南，建议平均风险男性定期做PSA检测

美国癌症协会（ACS）11 月 12 日发布更新版前列腺癌筛查指南。新闻稿页面上能看见的时间只有日期。核心变化是：平均风险、50 至 69 岁的男性，建议每两年做一次基于前列腺特异抗原（PSA）的筛查，并在开始前由临床人员说明潜在益处、局限和危害。

黑人男性，以及有强烈家族史的男性，建议从 45 岁到 69 岁每年筛查。非黑人、只有一名一度亲属在 65 岁或以后确诊的人，建议在 45 至 69 岁每两年筛查一次。70 至 74 岁是否继续筛查，需要个体化讨论，因为益处和危害的平衡仍不确定。一般不建议 75 岁及以上的人筛查；80 岁以上，或预期寿命不足十年的人，不建议筛查。

指南还提出，PSA 升高的人应在两周到三个月内复查。确认仍然升高后，再考虑磁共振成像和/或经验证的生物标志物，以决定是否活检。对低风险、进展或转移可能较小的前列腺癌，应把主动监测作为初始管理选项。ACS 称，自 2010 年版指南以来，更多证据显示 PSA 筛查可以降低前列腺癌死亡和晚期诊断的风险，同时现有处理方式有助于减少不必要的活检和治疗。这次更新基于系统的证据评价和一项受委托的建模研究，全文发表在《CA: A Cancer Journal for Clinicians》，并会作为活指南，按新证据继续修订。

这是临床指南更新，不是新的随机试验最终结果。筛查有益处，也有危害，不能消除漏诊或过度诊断。

为何关注：这是美国主要癌症防治机构对常规筛查建议的方向性调整，直接关系到谁应检测、隔多久检测，以及如何避免对低风险病变过度治疗。

发布：上海时间2026-11-12（可见文本仅有日期；时区与钟点未在页面显著展示）｜[American Cancer Society](https://pressroom.cancer.org/prostate-cancer-screening-guideline-update-2026)  
[单篇档案](2026/11/13/健康/acs-prostate-cancer-screening-guideline-2026.md)

---

<a id="qita"></a>

## 其他

<a id="himalayan-miniature-horned-frog-species"></a>

### 喜马拉雅东部发现五种微型角蛙新种

BBC 于 11 月 12 日报道，德里大学与哈佛大学的研究团队在印度东喜马拉雅的阿鲁纳恰尔邦，经过大约五年野外工作，发现五种微型角蛙新种。论文则是 11 月 11 日发表在《Royal Society Open Science》。五种都归入 Jingophrys 类群，使该类群已知物种数增加一倍以上。

它们分别被命名为 Jingophrys taniitatii（Tanii 角蛙）、Jingophrys tanogogo（食螺角蛙）、Jingophrys siangensis（西亚昂角蛙）、Jingophrys hrdy（Hrdy 角蛙）和 Jingophrys wularsoni（Wu-Larson 角蛙）。其中食螺角蛙是印度境内首个已知以蜗牛为食的蛙类，也是该科里第一次记录到这种食性。

研究人员认为，随着喜马拉雅隆起和亚洲季风形成，该类群在东部山区迅速分化，说明这一区域在蛙类演化中的作用可能被低估。带领研究的哈佛大学比较动物学博物馆的索纳利·加尔格说，一些演化变化可能发生在此前较少被研究的类群中。合作者 SD·比朱指出，部分新种非常隐秘，只在偏远森林的短暂繁殖期出现，还需要更多研究来了解它们的生物学和保护需求。

为何关注：这是经过同行评议的分类学发现，既补充了东喜马拉雅的物种记录，也说明该区域仍有大量没有被充分调查的生物多样性。

发布：上海时间2026-11-12 19:07｜[BBC News](https://www.bbc.com/news/articles/c8kgkw7dr5rko)  
[单篇档案](2026/11/13/其他/himalayan-miniature-horned-frog-species.md)

---

## 阅读说明

本期独立新闻 22 条，14 个来源，其中 AI 10 条。首页按独立事件计数。重点区和栏目里出现两次的，仍然是一条。

来源给出钟点时，这里只写上海时间；原时区与时间依据写在单篇档案里。只有日期、没有钟点的，不补时分。页面未标明时区的钟点，不换算成已确认的上海时间。JSON-LD 若明显是午夜或正午整点占位，不当作真实钟点。Agent Anomaly Detection 的页面只有 2026-11-12 这个日期，不记为已经证实的 24 小时时刻。美国癌症协会指南的读者可见时间只写日期；页面 HTML 注释里的钟点，不写成页面已经展示的正式发布时间。

本期 14 个来源的计法：谷歌官方博客与 Google Developers Blog 计为一家「谷歌」；Amazon Web Services 的两条计为一家；BBC News 与 BBC Sport 计为一家。The Register、Anthropic（Claude Code GitHub Releases）、Databricks、The Verge、IBM（Hugging Face 上的 Granite/LLMON 博文）、Salesforce（Hugging Face 上的 SOV-Transcribe-1 博文）、The Guardian、美国全国房地产经纪人协会（NAR）、WTA、NBA.com、美国癌症协会（ACS）各计一家。

厂商基准、内部测试和商业公司自拟的测试写成公司或测试方的陈述，不是独立复核结论。健康条目保留指南阶段，以及筛查同时存在益处和危害。参赛、完赛、预告和已经发生的事分开写；文章发表时间与事件时间也不混在一起。

稳定版块是：AI、科技、搞笑、财经、娱乐、体育、社会、健康、其他。AI 单独成栏，不并入科技。这一栏看热门产品与工具，尤其是 ChatGPT、Codex、Claude Code（CC）、Cursor、Grok Bot、DeepSeek，以及同级别的助手和编程工具。单篇放在 `YYYY/MM/DD/AI/`。搞笑栏本期暂无通过审核的稿件。

仅展示审核通过内容。

本页是 GitHub 上的 Markdown，不是独立网站。更新时间：上海时间 2026-11-13 10:03。
