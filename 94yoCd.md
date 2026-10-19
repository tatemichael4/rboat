# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 开放式学习空间的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_633%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/pic=759
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_633%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/dDE=1i8
- 数字支付体验的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/775
- 社区科普课堂的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/fsl
- 社区便民服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/zDM
- 基层健康档案的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/119=lpu
- 居家防滑改造中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/bpk=299
- 城市体育设施的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/dB6=Zt2
- 城市运动公园的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/613
- 小区公共照明的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/mjh
- 数字地图应用中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/SYM
- 开放式学习空间的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/838=gfz
- 儿童友好空间的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/lmh=174
- 城市建设科普的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/rni=qI9
- 校园节能行动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/053
- 智能手机助老的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/xon
- 社区活动报名的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/tEB
- 节能生活方式的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/150=kgj
- 居家适老化改造的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/sik=503
- 环境教育课程的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/OoB=9ks
- 全民阅读推广的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/621
- 基层服务创新的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/lfy
- 本地历史资料的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/THj
- 青少年科普实践的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/767=nbz
- 公园亲子设施的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/frs=463
- 城市游园体验的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85._%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/knM=22u
- 乡村阅读空间的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/346
- 社区环保活动的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/qtf
- 城市博物馆服务的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/6cN
- 乡村阅读活动的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/319=spt
- 社区活动报名的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/hso=922
- 社区交通安全的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E6%B3%A8%E5%86%8C_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/SpB=5op
- 乡村生活观察的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/089
- 社区文化传播的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/szr
- 社区环保活动的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/OhB
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/305=riy
- 节日文化体验的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/snx=037
- 儿童安全出行的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B~welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/eXs=arr
- 新能源出行的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/725
- 社区读书角建设的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/tnm
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/1Dc
- 社区手工活动的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/989=cua
- 休闲运动入门的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/kjz=567
- 机器学习入门的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E8%B4%AD%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%81%A5%E5%BA%B7?/h4h=0p2
- 便民服务地图的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/430
- 社区公共卫生的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/qpl
- 图书馆数字服务的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/fWp
- 城市绿道建设的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/800=gmk
- 公共场馆服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/jaa=256
- 电子商务服务的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/3Au=Zhm
- 节日文化体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/179
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/cbj
- 健康饮水科普的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/3RP
- 科学教育活动的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/677=zyg
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/koq=527
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Jsc=Cu0
- 老年人日常照护的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/319
- 绿色办公实践的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/cot
- 节约用水实践的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/DDE
- 数字档案服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/795=tvu
- 社区公共议事的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/eay=838
- 健康步道使用的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/P5B=Nhc
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/321
- 节能家电使用的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gdu
- 骑行路线规划的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/85Y
- 就业技能培训的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/067=rjm
- 公共服务数字化的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dhb=234
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%88%B1%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/c5U=T8h
- 便民服务窗口的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/432
- 乡村生活观察的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/ziu
- 通勤路线规划的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/Cmf
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/651=typ
- 市民意见收集的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/knz=733
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/tot=r77
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/202
- 家庭养老规划的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/gkm
- 健康步道使用的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/PzA
- 基层健康服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/487=lsy
- 小微企业服务的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/aea=451
- 公共图书馆服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/6gg=Sm6
- 城市应急科普的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/067
- 城市雨天出行的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/hon
- 校园安全教育的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/PMj
- 节假日出行安排的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/568=urk
- 就业技能培训的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/xkx=498
- 城乡交流活动的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/xi2=5SO
- 城市适老服务的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/221
- 城市展览体验的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/bso
- 志愿服务平台的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/wjF
- 儿童友好街区的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/779=itr
- 青少年心理健康的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/xir=617
- 校园社团活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E8%B4%AD_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/t0s=LXD
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/458
- 邻里共享空间的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/uls
- 校园阅读活动的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/fsL
- 城市公共厕所的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/200=exc
- 城市农夫市集的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/kgq=523
- 社区读书角建设的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/yzB=ywH
- 城市适老服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/008
- 地方文化传播的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/wax
- 家庭节能设备的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/qZE
- 家庭用电安全的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/668=nlm
- 城市便民驿站的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/bhh=971
- 灵活就业交流的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/0Hq=z70
- 骑行路线规划的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/183
- 公共卫生设施的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/qnk
- 数字公共文化的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/6wC
- 城市文明实践的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/786=pue
- 城市公共自行车的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/moi=415
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/yvn=WGR
- 社区信息发布的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/597
- 市民意见收集的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/bit
- 网络信息辨识的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/DXu
- 骑行路线规划的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/761=rpb
- 社区安全巡查的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/bfv=989
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/g6I=cPa
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/266
- 数字阅读服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/mfh
- 城市水环境观察的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/88e
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/711=hnj
- 社区宠物管理的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/ltt=810
- 基层医疗预约的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/V1M=ljH
- 社区活动报名的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/599
- 社区文化传播的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/rsp
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/YMm
- 科学观察活动的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/798=rlc
- 科学信息获取的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/mzy=173
- 环境监测科普的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/yzq=Zc0
- 城市公共空间的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/651
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/dla
- 数字政务体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/YdR
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/973=ogk
- 农贸市场环境的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/wjv=460
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/n3O=JKU
- 数字支付体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/656
- 公交站点体验中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/jta
- 社区志愿服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/A4Z
- 便民信息查询中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/365=fkr
- 社区便利生活的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/mbl=577
- 城市公共饮水的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/oCM=z1l
- 健康信息获取的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/920
- 社区协商议事的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/grb
- 社区花园共建的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/bM7
- 公共服务咨询的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/229=yao
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/cle=952
- 城市绿道建设的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/G7S=jLF
- 青少年心理健康的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/153
- 低碳社区实践的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/lpd
- 家庭急救准备的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/x2U
- 家庭节能设备的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/565=lqd
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/rbv=373
- 学校食育活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/2O8=tI1
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/076
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/ecj
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/LKK
- 社区故事采集的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/513=xff
- 就业技能培训的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/uvg=771
- 邻里共享空间的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/NQ6=hCC
- 绿色快递包装的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/512
- 食品安全科普的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/cro
- 旧物循环利用的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/VkM
- 乡村公共服务的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/141=epd
- 乡村文化活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/xxx=293
- 社区设施共享的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/S77=5PQ
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/085
- 老年人日常照护的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/ean
- 儿童友好空间的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/Klr
- 城市文化路线的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/648=zui
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/bkc=290
- 数字艺术创作的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/Juq=SEn
- 数字学习资源的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/371
- 科技馆参观体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/itp
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/69v
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/644=hza
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/iqi=543
- 公共服务评价的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/HPG=7tv
- 远程协作工具的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/865
- 公共空间照明中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/krc
- 绿色建筑理念的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/GsN
- 乡村公共服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/328=asg
- 城市社区治理的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/zzo=956
- 智能家居应用的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/i31=hQa
- 老年人文化生活的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/588
- 城市文化路线的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/qbw
- 线上阅读资源的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/slB
- 基层健康服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/226=bkl
- 就业技能培训的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/sqm=148
- 学校食育活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_360%E5%88%9B%E6%8A%95?/9Rx=pfC
- 乡村公共文化的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/783
- 文化讲座服务的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/huo
- 家庭健康管理的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/Lzv
- 非遗体验活动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/171=krv
- 绿色快递包装的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/zjh=757
- 青年就业服务的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/QYr=cHF
- 新能源知识普及的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/686
- 本地消费场景的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/bbv
- 乡村生态观察的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/r6D
- 节约用水实践的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/632=ejz
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/wjx=904
- 老年智能设备的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%9B%86?/ho6=pPr
- 软件开发学习的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/041
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/pji
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/rhs
- 乡村文化空间的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/407=dzo
- 无障碍出行的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/eux=425
- 社区活动报名的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/GOh=dwJ
- 公共设施使用的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/528
- 社区环保活动的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ehy
- 软件开发学习的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/Wsb
- 节气饮食文化的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/631=bty
- 公共场所导视的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ard=864
- 社区商业活力的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ltg=2qm
- 生活垃圾回收的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/238
- 社区休闲设施的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/zpn
- 绿色办公实践的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/8BW
- 公共设施维护的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/968=ulj
- 基层健康档案的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/vop=608
- 老年人文化生活的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/8zw=SA2
- 基层服务创新的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/808
- 家庭理财科普的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/mjw
- 在线学习体验的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/yMj
- 城市树木认养的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/110=edh
- 学校体育活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/rrl=120
- 社区科普课堂的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/Irq=pJf
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/108
- 公共设施使用的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/xwm
- 绿色办公实践的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/bDp
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/662=csd
- 社区读书角建设的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/fwe=232
- 家庭教育交流的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/f6M=5gl
- 数字艺术创作的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/211
- 公共卫生设施的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/qjn
- 街区道路维护的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/m6N
- 公共空间照明的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/600=zzz
- 公交站点体验的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/lmo=073
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/Zvn=Qnt
- 邻里互助活动的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/062
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/gik
- 休闲运动入门的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/rL4
- 通勤路线规划的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/540=itf
- 公共场所导视的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/qft=215
- 读书会组织的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/Wlv=v6k
- 基层健康服务的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/975
- 邻里共享空间的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/jyb
- 安全出行教育的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/Rb8
- 城市绿道建设的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/708=whr
- 环境监测科普的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/lpg=353
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/aTU=QMX
- 乡村文化空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/331
- 个人时间管理的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mpm

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
