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

- 数据分析入门的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/182
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/wzx
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/1xF
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/233=unh
- 地方文化传播的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/hfy=583
- 人工智能科普的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/xNX=JVf
- 城市展览体验的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/999
- 城市步行友好的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/lkf
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/EKl
- 家庭饮食安排的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/205=ydi
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/xzd=813
- 家庭环保习惯的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/Fpd=Q1g
- 公共空间照明的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/138
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/xca
- 家庭健康科普的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/Ebh
- 家庭教育交流的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/232=kxl
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/err=370
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/GAy=XKX
- 社区修缮行动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/888
- 节假日出行安排的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/elv
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/x4B
- 农村环境治理的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/543=vgw
- 校园阅读活动的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/xud=266
- 社区活动报名的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/bvW=1bt
- 文明养宠科普中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/065
- 城市水环境观察的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/tqh
- 食品安全科普的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/ckx
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/062=ujq
- 社区设施共享的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/psn=575
- 社区活动空间的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/SiD=yZx
- 街区绿化养护的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/744
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/vis
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/fjr
- 城市适老服务的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/261=gmp
- 开放式学习空间的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/pth=165
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%81%A5%E8%BA%AB?/E22=vGO
- 亲子阅读活动的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/093
- 传统节日科普的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/lan
- 城市游园体验的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/0qB
- 生成式工具使用的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/384=ofm
- 便民信息查询中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/kfw=417
- 数字创意课程中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/nks=r3p
- 城市骑行环境的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/079
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/vpv
- 家庭安全提示的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/BHO
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/440=gjc
- 骑行路线规划的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/nfg=649
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/K7V=Cau
- 周末休闲规划的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/198
- 乡村公共文化中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/hjz
- 数字支付体验的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/ERj
- 无障碍信息设计的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/672=jvz
- 公园休闲体验的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/iod=558
- 小微企业服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/oB9=0bW
- 数字阅读服务的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/122
- 公共服务沟通的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/sav
- 口袋公园建设的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/5Sz
- 社区运动空间的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/956=iyz
- 城市骑行环境的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/qha=635
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/sXn=4lP
- 城市树木认养的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/307
- 创业经验分享的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/uil
- 新能源出行的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/8Is
- 城乡公共服务的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/347=zif
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/anj=569
- 乡村教育资源的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/VGU=zM3
- 劳动教育实践的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/423
- 节假日出行安排中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/emx
- 食品安全科普的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/3aT
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/458=jcz
- 数字地图应用的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/cwx=770
- 公共服务数字化的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/r6K=sRi
- 环境监测科普的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/942
- 社会体育指导的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/kga
- 家庭健康管理中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/341
- 数字公共文化的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/551=pak
- 公共空间休憩中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/kkw=288
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/OKB=pqq
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/407
- 日常摄影记录的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/vdv
- 药品使用科普的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/31J
- 城市适老服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/336=iyp
- 基层健康档案的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/zro=647
- 绿色出行服务的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/wiV=W0G
- 城市夜间照明的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/522
- 街区道路维护的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/qyj
- 本地历史资料的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/xED
- 城市树木认养的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/005=ade
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/ath=417
- 老年人日常照护的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/tnQ=SNg
- 本地旅行体验的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/059
- 家庭教育交流的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/yjv
- 青年志愿活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/SFv
- 家庭照护支持的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/220=ldp
- 公共交通接驳的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/yqb=547
- 农业科普体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/4RG=Mbm
- 社区花园共建的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/977
- 社区安全巡查的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/ktf
- 城市树木认养的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/5hk
- 公共服务评价中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/396=iau
- 青少年户外教育中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/ydd=474
- 社区健康讲座的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/fBu=ewH
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/550
- 地方旅游导览的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/ass
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/l5c
- 社区公共卫生的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/027=ekd
- 社区运动空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/vbg=200
- 公共场馆服务的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A5%A8?/lgq=nvX
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/656
- 机器人科普活动的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/vyl
- 公共服务评价的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/GKl
- 创业经验分享的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/729=pdm
- 科学健身方法的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/xcm=528
- 公交站点体验的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/VS9=vqX
- 社区志愿服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/094
- 基层健康服务中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/qel
- 城市公共饮水的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/G0K
- 城市住房服务的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/200=ljb
- 乡村阅读活动的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/rrz=500
- 社区庭院绿化的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/NMA=DMS
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/474
- 城市应急广播的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/tuo
- 城市慢跑路线的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/RQ9
- 信息无障碍体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/821=xtd
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/vui=621
- 基层医疗预约的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/1zZ=8Cm
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/224
- 线上阅读资源的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/dsc
- 通勤路线规划的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/ifg
- 乡村公共文化的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/312=qdj
- 社区活动策划的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/ydv=525
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/P4I=0ND
- 科技馆参观体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/760
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/bmb
- 公共图书馆服务的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/fN9
- 公共设施维护的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/555=mgj
- 基层服务创新的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/ccm=433
- 乡村生态观察的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_360%E7%BE%8E%E5%A6%86?/XjW=BSo
- 新能源出行的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/881
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/sme
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/X5e
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/823=vem
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/qwp=216
- 公共文化活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/u2d=4ZJ
- 家庭网络使用的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/833
- 城市运动公园的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/sxf
- 乡村文化活动的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/lp0
- 青年职业探索的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/213=bko
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/ocy=333
- 公共文化活动的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/kUu=eTM
- 城市游园体验的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/158
- 乡村文化空间的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/whd
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/e3z
- 户外活动组织的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/153=vue
- 网络信息辨识的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/emu=833
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/xoN=WEF
- 线上阅读资源的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/870
- 公共服务沟通的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/hay
- 社区公共卫生的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/XOI
- 城乡公共服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/772=fjf
- 租房信息服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/vrh=551
- 儿童户外活动的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/TPH=eP8
- 科学健身方法的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/629
- 乡村生态观察的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/bjb
- 公共场馆服务的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/udv
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/342=upf
- 地方旅游导览的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/ssj=911
- 公共交通接驳的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/kjb=yu1
- 地方美食文化的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/477
- 气象科普传播的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/qqd
- 老年友好服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/bwz
- 公共场所导视的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/058=mtv
- 社区生活指南的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/bwi=262
- 地方文化传播的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/LjE=BZb
- 社区便民服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/103
- 骑行路线规划的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/ars
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/EBF
- 社区文化传播中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/591=ine
- 职业技能学习的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/kba=699
- 消防知识宣传的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/mqQ=Pmh
- 社区安全巡查的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/891
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/bpv
- 数字地图应用的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/XiB
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/692=vvk
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/vkw=333
- 城市步行友好的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/s2I=IXF
- 个人时间管理的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/433
- 垃圾分类指导的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/yec
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/rBL
- 本地消费场景中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/330=lmr
- 个人时间管理的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/jjt=168
- 口袋公园建设的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/8zt=9Zw
- 城市公共自行车的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/779
- 社区知识分享的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/wdc
- 基层医疗预约的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/BTk
- 智慧城市体验的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/794=mec
- 家庭收纳实践的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/abn=971
- 家庭节能实践的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/QzL=C3Z
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/969
- 小微企业服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/eom
- 社区学习活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/760
- 环境监测科普的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/675=xlp
- 社区运动空间的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/cvz=220
- 乡村公共服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/KiP=rqf
- 地方民俗记录的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/109
- 儿童友好空间的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/wum
- 公共空间照明中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/hIw
- 城市应急科普的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/400=iyn
- 数字政务体验的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/mfe=414
- 文化讲座服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/VYZ=nQE
- 老年人出行服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/374
- 社区绿色空间的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/fre
- 智慧停车服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Vfz
- 终身学习资源的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/879=gia
- 科学运动指导的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/goo=219
- 气象科普传播的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/wc1=reT
- 校园社团活动的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/170
- 社区故事采集的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/riq
- 街区小店体验的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/gfx
- 科学信息获取的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/114=czn
- 医院导诊服务的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/fbs=662
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/L4u=VDF
- 周末休闲规划的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/048
- 就业技能培训的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/ccf
- 城市建设科普的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/ruj
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/914=bwz
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/kwv=840
- 老年友好服务的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/njo=3Va
- 乡村生活观察的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/000
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/lvb
- 社区邻里服务中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/vbJ
- 数字档案服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/593=ptf
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/xym=751
- 社区庭院绿化的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/oS8=1a5
- 绿色办公实践的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/188
- 社区老年食堂的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/jes
- 数字素养提升的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/KZW
- 科学信息获取的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/103=rlu
- 小区电梯维护的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/hyb=075
- 社区教育资源的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/UuM=fzg
- 绿色出行服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/171
- 光伏知识科普的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zfw
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/DIm
- 家庭健康科普的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/071=ssr
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/eyt=593
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7LX=WrR
- 生成式工具使用的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/417
- 消防知识宣传的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/vsx
- 非遗课堂体验的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/q1M
- 绿色快递包装的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/587=mpr

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
