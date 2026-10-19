# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 社区阅读服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%85%8D%E8%B4%B9_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/ATS
- 社区托育服务的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%85%8D%E8%B4%B9_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/714=yoz
- 节假日出行安排的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%85%8D%E8%B4%B9_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/pxs=490
- 家庭急救准备的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%85%8D%E8%B4%B9_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/vaW=VRK
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/064
- 青少年编程学习的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/loi
- 周末休闲规划的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/i7K
- 家庭用电安全的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/729=mnq
- 环境监测科普的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/law=982
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/vDC=BOv
- 数字档案服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/681
- 小区电梯维护的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/ogk
- 公共场馆服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/DLf
- 社区设施共享的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/282=kuv
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/dee=396
- 智能手机助老的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/0z4=nwP
- 街区更新实践的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/903
- 科学观察活动的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/pdm
- 小区电梯维护的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/jZF
- 物业服务沟通的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/709=csd
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/tto=564
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/rEC=w5s
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/923
- 社区交通安全的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/imu
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/Dpn
- 数字设备回收的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/460=mpt
- 老年人日常照护的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/xun=799
- 读书会组织的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/lwc=0a8
- 数字公共文化的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/482
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/gfs
- 城市应急科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/ylS
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/820=gjx
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/bvs=918
- 公交站点体验的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/Nyx=06j
- 城市应急科普的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/676
- 居家防滑改造的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/vnp
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/V4b
- 乡村公共服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/020=hda
- 家庭环保习惯的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/qgm=524
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/7VP=iYb
- 街区更新实践的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/352
- 数据分析入门的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/ibf
- 市民意见收集的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/MAl
- 家庭饮食安排的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/670=guh
- 社区活动空间的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/aza=893
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/tMY=hXF
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/842
- 城市体育设施的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/low
- 公共服务沟通的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/xxX
- 生活垃圾减量的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/084=wyx
- 青年就业服务的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/arp=731
- 城市建设科普的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/O1K=AZm
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/629
- 校园社团活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/pir
- 城市文明出行的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/srv
- 城市社区治理的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/571=mdl
- 城市可持续生活的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/hyv=803
- 食品安全科普的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/ufa=Qn9
- 居家适老化改造的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/615
- 农产品消费体验的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/pgj
- 文化场馆预约的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/LcS
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/201=kxb
- 社区安全巡查的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/btr=206
- 公共场馆服务的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E7%9A%84%E5%90%97_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/SCS=qGC
- 本地消费场景的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/868
- 社区快递服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/gwd
- 城市文明出行的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/HWJ
- 本地消费场景的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/402=oro
- 城市公共自行车的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/jyf=332
- 光伏知识科普中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/3oy=VwI
- 家庭养老规划的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/375
- 劳动教育实践的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ont
- 全民阅读推广的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/1Kg
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/049=rms
- 环境监测科普的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ngn=288
- 公共场馆服务的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/4Nc=iDO
- 乡村生活观察的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/483
- 街区小店体验的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/pea
- 城市步行友好的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/SA9
- 城市绿道建设的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/793=vfp
- 城市公共空间的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/rph=679
- 机器人科普活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%AD%E5%A5%96%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/TEm=jzE
- 家庭健康科普的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/280
- 绿色生活实践的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/zew
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/2Un
- 家庭消费规划的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/469=xzz
- 数字生活课堂的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/frq=568
- 城市可持续生活的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/VGy=fCs
- 科普展览体验的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/365
- 老年学习活动的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/qnj
- 街区绿化养护的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/8fh
- 街道综合服务的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/196=zdi
- 城市公共饮水的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/fdl=527
- 智慧城市体验的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/N4R=feM
- 青少年科技社团的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/892
- 城市生活记录的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/hta
- 社区健康讲座的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/94h
- 学校食育活动的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/338=jzk
- 家庭教育交流的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/lvn=014
- 社区儿童活动中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/mOH=knQ
- 小区公共照明的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/987
- 城乡交通衔接的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/ntb
- 公共空间安全的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/nFq
- 城市公共饮水的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/163=oni
- 社区艺术活动的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/frb=786
- 数字便民地图的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/GkD=X9x
- 非遗体验活动的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/685
- 社区活动报名的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/ekw
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/tUh
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/031=ddd
- 公共空间休憩的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/bkf=109
- 食品安全科普的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/2RJ=Sen
- 环境监测科普的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/745
- 老年运动活动的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/kgh
- 数字创作工具的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/Fdw
- 青年职业探索的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/553=mmn
- 数字支付体验的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/blc=717
- 科学观察活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/lMC=ov9
- 文明养宠科普的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/329
- 休闲运动入门的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tlz
- 口袋公园建设的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dzm
- 数字阅读服务的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/254=its
- 数字档案服务的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ake=027
- 街区道路维护的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/aLN=qKU
- 乡村生活观察的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/104
- 市民热线服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/flv
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/DBy
- 城市建设科普的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/142=dsq
- 安全出行教育的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/uth=868
- 绿色消费选择的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/N56=OyU
- 本地消费场景的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/241
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/zof
- 健康饮水科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/UbC
- 骑行路线规划中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/012=ywt
- 邻里互助活动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/wrf=498
- 居民健康教育的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/7MD=Skx
- 人工智能科普的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/465
- 开源技术交流的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/tlh
- 城市住房服务的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/QJL
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/401=rix
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/wiz=608
- 数字设备回收的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F?/QOi=0y3
- 公共服务预约的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/553
- 公园休闲体验的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/wrs
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/oxH
- 社区交通安全的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/517=ovv
- 社区艺术活动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xcf=796
- 城市休闲步道的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/QbB=IOZ
- 家庭健康科普的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/800
- 线上阅读资源的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/zhq
- 节假日出行安排的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/iXw
- 校园社团活动中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/132=cda
- 数据分析入门中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/sgo=622
- 城市文明实践的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/i28=XUx
- 社区活动空间的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/417
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/nbw
- 乡村电商实践的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/VZS
- 社区养老服务的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/054=oej
- 城市休闲步道的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/tnj=847
- 社区互助网络的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/tNA=UY3
- 公共场所导视的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/185
- 绿色出行服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/sjz
- 亲子科普活动中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/z1g
- 公共服务咨询的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/614=pjr
- 急救知识普及的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/sxm=512
- 儿童运动体验的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%91%E4%B8%8B%E8%BD%BD_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/TO4=cMP
- 家庭安全提示的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/687
- 青少年户外教育的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/rtv
- 社区健康讲座的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/eIq
- 科学健身方法的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/145=dsu
- 地方戏曲体验的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/eag=879
- 本地消费场景的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/tLq=60z
- 社区慢性病防控的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/227
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/jvs
- 青年志愿活动的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/c2x
- 城市农夫市集的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/420=jya
- 老年人文化生活的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/bev=480
- 街道综合服务的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91app%E5%AE%89%E5%85%A8%E5%90%97_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/Rh9=LPL
- 健康信息获取的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/540
- 节日文化体验的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/mtd
- 绿色快递包装中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/lZf
- 公交站点体验的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/844=cxa
- 运动安全知识的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/xct=976
- 个人时间管理的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/idl=OYO
- 食品配送体验的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/360
- 家庭急救准备的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/ihh
- 信息无障碍体验的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/0AE
- 城市博物馆服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/883=qdy
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/wnc=650
- 数字艺术创作的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/bzi=JAE
- 社区慢性病防控的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/981
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/tnr
- 老年人文化生活的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/Znm
- 社区便民服务的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/213=rri
- 社区教育资源的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/tvi=714
- 社区文化节活动的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/D76=9SV
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/859
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/uue
- 社区家校合作的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/zV1
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/240=pkd
- 图书馆数字服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/zfb=202
- 开源技术交流的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/a20=qGC
- 绿色办公实践的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/069
- 城市应急广播的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/eor
- 社区家校合作的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/C3A
- 家庭照护支持的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/846=xrk
- 劳动教育实践的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/uku=344
- 社区慢性病防控的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E7%94%A8_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/Rfo=iA4
- 生活垃圾回收的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/862
- 乡村教育资源的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/ebl
- 乡村文化活动的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/2N6
- 软件开发学习的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/662=azp
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/cjm=860
- 老旧小区改造的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/Piz=8kM
- 生成式工具使用的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/110
- 城乡交流活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/juo
- 软件开发学习的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/RUc
- 社区艺术活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/008=cwu
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/mfw=717
- 社区养老服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/PTY=uT8
- 全民健身活动的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/890
- 非遗体验活动的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/oko
- 社区读书角建设的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/CZy
- 社区信息发布的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/912=hte
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gvj=273
- 社区快递服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/37i=UQL
- 青少年户外教育的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/412
- 急救知识普及的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/ioy
- 城市共享单车的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/rns
- 城市水环境观察的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/296=xof
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/opd=597
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/GRm=puf
- 乡村文化空间的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/416
- 公共空间导览的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/txy
- 社区绿色空间的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/KvR
- 城市可持续生活的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/410=agr
- 机器人科普活动的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/sdv=592
- 家庭健康管理的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/Nh4=IwU
- 节约用水实践的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/715
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/tka
- 城市步行环境的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/w8W
- 社区休闲设施的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/576=fkj
- 社区应急准备的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/tmk=548
- 社区设施共享的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/Zlp=jmZ
- 老年人出行服务的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/295
- 青少年科普实践中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/vre
- 数字素养提升的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/rSL
- 社区故事采集的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/581=exh
- 数字创意课程的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/ymz=135
- 个人数据管理的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E5%85%A8%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/A9R=iwM

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
