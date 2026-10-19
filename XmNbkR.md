# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 城市博物馆活动的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E5%8A%A9%E6%89%8B_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/gak=476
- 儿童阅读角的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E5%8A%A9%E6%89%8B_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/1KF=WQE
- 文明养宠科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/701
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/nld
- 儿童阅读角的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/gRa
- 公共设施使用的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/406=bus
- 老年人日常照护的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/tsq=872
- 社区宠物管理的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E6%9C%BA%E9%80%89%E5%8F%B7%E5%87%86%E7%A1%AE%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/jji=IFb
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/505
- 数字艺术创作的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/xxe
- 社区信息发布的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/jom
- 家庭网络使用的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/311=jvl
- 家庭运动计划的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/brl=672
- 城市公共空间的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/hp4=okG
- 劳动教育实践的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/447
- 城市绿道建设的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/jaa
- 城市夜间生活的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/2ka
- 公共文化活动的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/144=jcr
- 城市基础设施的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/hiv=828
- 口袋公园建设的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/VLg=Sxe
- 绿色办公实践的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/396
- 社区家政服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/rgq
- 传统节日科普的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/niE
- 节气饮食文化的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/128=hqz
- 城市文明实践的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/fbp=822
- 街头绿植养护的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A5%97%E8%B7%AF%E7%9A%84%E5%90%8E%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/1sv=54I
- 小区停车协商中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/753
- 数字资源检索的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/nrf
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/Fc7
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/319=pdx
- 社区环保活动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/wjg=511
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%80%8E%E6%A0%B7%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A4%A7%E5%A5%96%E5%8F%91%E6%A8%AA%E8%B4%A2_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/f8S=JO6
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/311
- 社区老年食堂的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/sjp
- 城市建设科普的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/zsS
- 日常摄影记录的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/933=iou
- 安全出行教育的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/qdp=963
- 数字创意课程的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E8%80%81%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/sUK=Z9v
- 城市住房服务的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/506
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/prd
- 城市空气科普的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/fG1
- 老旧小区改造的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/940=nxc
- 公共服务数字化的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/teh=952
- 节约用水实践的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BDapp_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/8Bi=CbZ
- 社区艺术活动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/467
- 公共服务评价的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/ccz
- 线上阅读资源的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/Hop
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/599=tsh
- 社区共享书架的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/foo=998
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/Ww9=AGT
- 乡村公共服务的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/738
- 小区停车协商的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/hib
- 社区艺术活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/rBq
- 城市公共空间的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/890=vda
- 城市骑行环境的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/zhe=661
- 基层医疗预约的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/pHN=oqp
- 社区心理支持的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/565
- 线上阅读资源的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/qdb
- 数字地图应用的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/33E
- 乡村生活观察的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/924=acn
- 乡村文化活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/wab=660
- 青年职业探索的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92v_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/QLU=w5u
- 青年志愿活动的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/274
- 公共空间休憩的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/xjm
- 全民健身活动的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/use
- 基层健康服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/074=rzx
- 家庭食品保存的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/xnw=720
- 志愿者培训交流的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E6%96%B0%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/xX9=xcQ
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/554
- 城市水环境观察中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/pcy
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/Imw
- 小微企业服务的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/433=uat
- 公共服务评价的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/mno=853
- 家庭节能实践的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/GhU=4qW
- 社区公共议事的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/637
- 数字创意课程的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/ojp
- 社区停车服务的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/a7q
- 公共服务数字化的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/101=rmg
- 旧物循环利用的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/mho=387
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%B6%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/Bwk=646
- 家庭照护支持的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/992
- 骑行路线规划的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/uuz
- 智能手机助老的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/unO
- 社区活动策划的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/606=eai
- 市民热线服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/eyp=584
- 社区修缮行动的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/kAh=DTM
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/644
- 社区邻里服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/dtc
- 社区安全巡查的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/CCO
- 社区协商议事的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/814=tjv
- 食品配送体验的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/eqz=279
- 节日文化体验的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%BB%91%E9%A9%AC%E4%BA%BA%E5%B7%A5%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/3Jf=Nmz
- 个人信息保护的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/960
- 社区邻里服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/qlk
- 社区科普课堂的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/U2e
- 乡村阅读活动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/844=jpo
- 网络信息辨识的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/qex=950
- 传统节日科普的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E8%B0%81%E6%9C%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/wQr=s5v
- 低碳社区实践的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/899
- 日常摄影记录的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/ipz
- 儿童友好空间的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/FDi
- 乡村文化空间的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/445=mmb
- 城市基础设施的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/moj=000
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_1000%E5%A4%9A%E5%A5%97%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/Jdy=Ie9
- 创业经验分享的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/997
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/wmt
- 生成式工具使用的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/HIF
- 家庭急救准备的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/174=xxq
- 社区花园共建的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/fya=591
- 老年智能设备的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%BA%94%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/Sug=Wy1
- 城乡公共服务的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/672
- 家庭照护支持的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/kwd
- 城市步行友好的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/v7B
- 社区教育资源的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/514=ihg
- 环境监测科普的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/mgt=301
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/DeI=gp2
- 数字政务体验的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/814
- 城市文明实践的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/zvk
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/pov
- 生活垃圾回收的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/322=mlq
- 社区垃圾回收的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/vra=116
- 城市绿道建设的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%AE%98_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/Qth=Het
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/416
- 城市公共厕所的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/dmt
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/Yz5
- 城市文化路线的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/556=lto
- 社区故事采集的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/kon=533
- 图书馆活动策划的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/yVg=JBH
- 城市空气科普的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/774
- 节气饮食文化的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/jtr
- 城市便民驿站的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/jqe
- 数字创意课程的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/467=zqo
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/txn=114
- 城市共享单车的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/mIq=0V3
- 生活服务数字化的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/007
- 城市噪声观察的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/ofj
- 城市便民驿站的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/JD8
- 社区手工活动的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/112=pfl
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/rme=560
- 家庭养老规划的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/22Z=oZ3
- 消防知识宣传的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/493
- 通勤路线规划的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/prt
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/vRr
- 生活服务数字化中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/165=umj
- 创业经验分享中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/dkk=938
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8app%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/bek=N92
- 智慧城市体验的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/790
- 城市游园体验的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/gbz
- 社区知识分享的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/MR7
- 校园安全教育的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/076=wfx
- 小区公共照明的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/fvl=727
- 数字课堂应用的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/jz8=I9s
- 乡村文化活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/471
- 数字档案服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/mbr
- 学校体育活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/f2I
- 城市休闲步道的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/187=nxg
- 社区快递服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/mbl=802
- 城市公共座椅的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%BE%B3%E9%97%A8%E6%AD%A3%E8%A7%84%E9%98%B3%E4%BD%93%E5%BD%A9%E4%B9%8B%E5%AE%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/QXW=QTC
- 青少年科普实践的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/394
- 电动汽车充电的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/tcx
- 社区公共议事的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/d7R
- 亲子科普活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/576=ciy
- 农产品消费体验的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/xau=327
- 数字学习资源的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E4%BC%97%E6%B5%8B?/dLm=TMy
- 社区垃圾回收的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/367
- 生活服务数字化的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/kix
- 家庭志愿活动的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/9qh
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/079=ptd
- 数字支付体验的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/hpf=539
- 街道综合服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%8D%81%E5%88%86%E5%BF%AB%E4%B9%90_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/6KP=Phy
- 家庭园艺实践的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/283
- 在线教育体验的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/uiy
- 城市夜间照明的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/vjJ
- 乡村公共阅读的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/328=fvj
- 社区家政服务的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/gzi=266
- 儿童户外活动的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E4%B8%8B%E8%BD%BD_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ghH=ELj
- 骑行路线规划的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/397
- 公共卫生设施的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/cmv
- 学校食育活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/8LE
- 消防知识宣传的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/546=iwx
- 日常摄影记录的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/kyt=330
- 公共空间照明的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E7%99%BE%E4%B8%87%E7%94%A8%E6%88%B7%E9%A6%96_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/2Oe=Y5z
- 家庭阅读计划的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/284
- 应急物资管理的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/lfw
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/ja9
- 志愿服务平台的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/655=znb
- 个人数据管理的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/xoj=625
- 社区便利生活的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%B8%89%E5%88%86%E5%BD%A9%E6%89%8B%E6%9C%BAapp_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/M8B=MND
- 日常摄影记录的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/272
- 校园安全教育的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/kjx
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/r5i
- 城市步行友好中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/282=bhb
- 社区教育资源的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/qwv=645
- 健康步道使用的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A833.cop_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/NrH=Liv
- 社区防暑服务的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/257
- 社区宠物管理的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/nnw
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/Xsj
- 小区停车协商的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/018=hnj
- 公共文化活动的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/byd=573
- 线上办事服务的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%A5%BD%E7%94%A8_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/QFm=R2y
- 社区健康讲座的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/346
- 乡村生态观察的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/ywy
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/6Us
- 读书会组织的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/378=zcm
- 线上阅读资源的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/cmk=480
- 数字便民地图的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/ZGX=PHY
- 社区文化节活动的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/807
- 数字创意课程的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/vug
- 家庭用电安全的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/5Q4
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/913=wfw
- 城市公共饮水的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/ozv=700
- 青少年科普实践的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/fFj=gJY
- 社区花园共建的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/284
- 城市噪声观察的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/iof
- 儿童阅读角的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/6CE
- 社区便民集市的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/856=ntk
- 数字创意课程的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/aik=528
- 开源技术交流的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0APP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/MGT=q6M
- 居民健康教育的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/207
- 个人信息保护的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/btf
- 公共服务指南的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/CLU
- 数字生活课堂的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/256=uaw
- 个人数据管理的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/dss=785
- 无障碍信息设计的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/MMy=IEg
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/062
- 农业科普体验的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/rlu
- 城市展览体验的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/4GV
- 线上办事服务的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/690=qkm
- 数据分析入门的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/ilq=666
- 社区文化节活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E5%AE%98%E6%96%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/yug=Own
- 数字学习资源的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/810
- 社区活动策划的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/yms
- 社区慢性病防控的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/vzh
- 开放式学习空间中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/797=fep
- 运动安全知识的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/cpp=996
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/O1z=v1B
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/162
- 信息无障碍体验的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/gif
- 社区公共议事的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/Fpi
- 社区快递服务的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/337=foz
- 租房信息服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/qmq=511
- 周末休闲规划的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%B0%8F%E7%82%AE_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/YLe=n3u
- 青少年户外教育的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/975
- 城市绿道建设的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/avq
- 乡村教育资源的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/smd
- 公共空间照明的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/908=kpz
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/njc=160
- 社区活动策划的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/1pX=zga
- 健康饮水科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9Aapp%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/494
- 城市文化路线的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9Aapp%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dgg

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
