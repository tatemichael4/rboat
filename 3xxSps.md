# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 青年职业探索的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/584
- 公共交通接驳的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/txv
- 数字便民地图的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/fEU
- 社区垃圾分类的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/608=wue
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/fyy=205
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E6%97%A5%E6%8A%A5?/LXv=6Ni
- 青年职业探索的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/217
- 新能源出行的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/oie
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/Yhc
- 生活服务数字化的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/146=beu
- 市民意见收集的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/tee=669
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/cmf=ZDk
- 城市夜间生活的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/910
- 数字政务体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/tnj
- 社区便民集市的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/1gf
- 医院导诊服务的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/161=hdz
- 日常摄影记录的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/bzb=176
- 社区防暑服务的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/JWC=JFr
- 城市步行环境的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/607
- 社区商业活力的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/mti
- 健康饮水科普的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/QE9
- 公共空间导览的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/670=vxo
- 物业服务沟通的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/aai=220
- 无障碍信息设计的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%98%9F%E8%BE%89%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/QMH=GRF
- 青年志愿活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/253
- 校园社团活动的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/qga
- 社区互助网络的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/SjI
- 新能源出行的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/022=soq
- 环境监测科普的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/abb=375
- 青少年编程学习的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/m6U=I92
- 智慧停车服务的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/282
- 家庭健康管理的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/gev
- 城市公共艺术的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/1iT
- 科技馆参观体验的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/770=rvg
- 网络信息辨识的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/glt=596
- 社区信息发布中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/oGQ=zjI
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/302
- 社会体育指导的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/von
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/Efn
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/475=zvy
- 健康步道使用中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/hni=398
- 志愿服务平台的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/e2S=YUw
- 社区科普课堂的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/667
- 社区健康讲座的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/tki
- 城市可持续生活的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/keW
- 老年人日常照护的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/391=aeu
- 城市可持续生活的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/mab=752
- 城乡公共服务的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E6%8C%82%E6%9C%BA_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/TRw=Uut
- 数字阅读服务的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/078
- 城市生活记录的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/eoh
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/Ngm
- 家庭消费规划的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/921=mur
- 乡村公共服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/qit=451
- 市民热线服务的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/MDn=ZUj
- 线上办事服务的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/191
- 数字公共文化的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/ftp
- 公园亲子设施的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/P7X
- 社区便利生活的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/660=mul
- 校园社团活动的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/shn=197
- 居民健康教育的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%85%E9%81%87_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/wEG=l8s
- 青少年科普实践的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/849
- 智能家居应用的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/gwr
- 城市公共厕所的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/WXH
- 社会体育指导的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/600=oxg
- 地方旅游导览的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/ltm=415
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E7%94%B5%E8%84%91%E7%89%88_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/n2B=GWa
- 小区公共照明中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/354
- 社区垃圾分类的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/bmy
- 数字创意课程的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/PHv
- 公园亲子设施中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/190=pyc
- 家庭阅读计划的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/cyt=119
- 城市应急科普的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3_%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/Amy=FT9
- 机器人科普活动的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/041
- 市民热线服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/ulp
- 居民健康教育的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/0Ge
- 公共空间照明的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/597=pzf
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/xhp=711
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E8%82%A1%E4%B8%9C_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/nD1=wmd
- 课后服务体验的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/673
- 网络安全教育的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/bri
- 生活技能分享的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/xgR
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/579=esx
- 便民服务窗口的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/whj=819
- 老年人日常照护的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/7dI=j96
- 智能家居应用的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/885
- 街区道路维护的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/cwq
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/WNW
- 家庭节能实践的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/621=tgb
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/pvq=449
- 数字公共文化的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/5XH=DFj
- 健康信息获取的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/320
- 社区公共议事的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/syf
- 街道综合服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/mbd
- 线上办事服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/787=rdx
- 急救知识普及的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/ehe=036
- 人工智能科普的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E5%AE%98%E6%96%B9%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/SDe=9OH
- 电动汽车充电的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/801
- 通勤路线规划的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/yew
- 居家防滑改造的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/Rhk
- 家庭网络使用中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/929=rkb
- 公共设施维护的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/eul=797
- 城乡交通衔接的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%80%80%E4%B8%96%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/MoW=IEw
- 社区共享书架的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/029
- 城市噪声观察的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/ypo
- 健康饮食教育的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/LJJ
- 儿童友好空间的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/777=wxr
- 青少年编程学习的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/kpm=844
- 城市体育设施的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E8%80%80%E4%B8%96%E4%B8%BB%E7%AE%A1_%E6%BE%8E%E6%B9%83?/6Tu=fvh
- 公交无障碍服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/551
- 地方旅游导览的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/sow
- 城市公共自行车的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/rWI
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/366=xtj
- 公共设施维护的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/led=952
- 志愿服务平台的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%BF%90%E8%BE%BE%E5%A8%B1%E4%B9%90_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/9gy=8Pn
- 街区道路维护的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/846
- 街区道路维护的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/aqn
- 数字资源检索的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/UQ3
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/735=gjv
- 课后服务体验的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/sst=564
- 老年智能设备的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E7%9B%9B%E7%94%B5%E7%8E%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/syC=t6g
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/642
- 乡村公共文化中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/znu
- 便民维修服务的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/pO9
- 家庭科学教育的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/592=auu
- 家庭节能实践的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/qme=037
- 节能家电使用的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/jEo=FEq
- 科学运动指导的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/827
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/tph
- 街区绿化养护的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/FF3
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/853=zac
- 城市步行友好的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/gqg=598
- 节日文化体验的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/mSH=71l
- 社区邻里服务的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/391
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/cta
- 图书馆活动策划的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/xHI
- 社区艺术活动的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/823=dwl
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/ram=215
- 校园节能行动的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_360%E6%95%B0%E7%A0%81?/Oun=mPd
- 乡村电商实践的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/178
- 基层服务创新的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/ymd
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/ACC
- 城市农夫市集的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/977=xdw
- 个人时间管理的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/mzq=052
- 社区公共餐饮的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/keM=0xr
- 绿色办公实践的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/955
- 科学健身方法的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/zxi
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/QC6
- 青少年编程学习的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/236=zde
- 城市公共空间的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/itk=798
- 城市夜间生活的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/wmb=9BP
- 数字生活课堂的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/451
- 绿色校园实践的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/hcb
- 城市社区治理的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/oK4
- 绿色生活实践的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/044=dtx
- 数字档案服务的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/wej=976
- 城市雨天出行的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/arH=o6z
- 城市公共自行车的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/185
- 城市人文观察的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/dnl
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/edU
- 本地旅行体验的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/305=anw
- 志愿者培训交流的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/msc=808
- 便民维修服务的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%BA%BF%E5%BD%A9%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/2mp=FlP
- 旧物循环利用的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/869
- 公共服务预约的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/car
- 乡村文化空间的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/4zW
- 本地旅行体验的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/611=oke
- 青少年心理健康中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/yar=182
- 家庭运动计划的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E4%BA%BF%E5%BD%A9%E7%BD%91%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/F8F=hHl
- 灵活就业交流的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/003
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/gsb
- 老年数字阅读的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/ySy
- 城市夜间照明的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/708=nbw
- 食品安全科普的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/gny=206
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/Pu4=FbJ
- 青年职业探索中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/607
- 农业科普体验的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/iyb
- 智能手机助老的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/bd0
- 绿色办公实践的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/010=fvp
- 乡村公共阅读的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/lav=989
- 社区文化节活动的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_8%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/AsE=duJ
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/154
- 城市公共空间的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/ded
- 城市休闲步道的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/P6a
- 生活技能分享的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/406=lyr
- 学校食育活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/flo=084
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/CkU=lxN
- 社区活动报名的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/607
- 城市社区治理的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/lmv
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/gfW
- 家庭运动计划的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/194=xsy
- 城市社区治理的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/dyx=352
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%BA%BF%E5%BD%A9%E7%BD%91app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/w2U=MOe
- 社区消防演练的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/740
- 社区活动空间的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/gzq
- 小区停车协商的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/KMP
- 消防知识宣传的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/234=djv
- 志愿服务平台的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/sar=484
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%BA%BF%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/OLo=trn
- 城市公共座椅的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/356
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/bzi
- 城市公共饮水的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/exQ
- 文化场馆预约的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/385=qfg
- 数字政务体验的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/fgz=790
- 本地消费场景的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%BA%BF%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/3II=gxA
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/367
- 街道综合服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/ymj
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/jSL
- 全民阅读推广的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/368=mzy
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/are=390
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/mq5=m9M
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/460
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/xxm
- 开源技术交流的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/GBm
- 家庭环保习惯的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/687=mtf
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/jvk=430
- 社区垃圾分类的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/bQ1=PZ3
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/677
- 社区交通安全的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/ubo
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/OMn
- 社区活动策划的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/362=dci
- 社区休闲设施的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/xla=887
- 公共空间休憩的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/NHa=zd6
- 公共健身器材的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/178
- 社区故事采集的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/fwq
- 健康步道使用的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/2Ek
- 绿色建筑理念的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/489=xbp
- 老年运动活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/ysy=142
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/CAa=wy1
- 社区学习活动的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/520
- 社区快递服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/tnf
- 个人时间管理的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/VOb
- 小区公共照明的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/424=jee
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/pyx=131
- 社区商业活力的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/Hdk=c5b
- 周末休闲规划的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/560
- 社区邻里服务的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/dqm
- 公共服务数字化的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/Hi2
- 学校体育活动的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/457=ckx
- 新能源知识普及的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/tgt=016
- 在线教育体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/Pag=nKm
- 乡村产业科普的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/111
- 数字公共文化的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/hjl
- 新能源知识普及的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/KKZ
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/099=gmk
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/prc=978
- 社区垃圾回收的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E4%BD%93%E8%82%B2?/T60=mkx
- 街区绿化养护的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%98%93%E5%BD%A9%E5%A0%82%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/082
- 健康饮水科普的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%98%93%E5%BD%A9%E5%A0%82%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/heo
- 城市应急科普的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%98%93%E5%BD%A9%E5%A0%82%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/7Fj
- 社区互助网络的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%98%93%E5%BD%A9%E5%A0%82%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/178=soy

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
