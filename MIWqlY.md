# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 公共设施维护的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/zv4
- 学校食育活动的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/658=lmm
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/dfv=312
- 社区花园共建中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/9fJ=mo6
- 地方民俗记录的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/243
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/urr
- 智慧停车服务的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/0Zl
- 生活服务数字化的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/717=uhg
- 开放式学习空间的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/oar=908
- 社区互助网络的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/pLb=oCK
- 城市空气科普的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/959
- 家庭阅读计划的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/rdz
- 街头绿植养护的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/Jaa
- 传统节日科普的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/883=qft
- 食品安全科普的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/xwz=455
- 基层医疗预约的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/6mF=Apb
- 社区健康讲座的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/777
- 数字阅读服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/kwx
- 个人时间管理的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/qDg
- 公共场所导视的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/221=lzj
- 网络安全教育中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/icw=894
- 城市应急广播中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/kZ6=z8H
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/286
- 公共卫生宣传的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/xcf
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/CFT
- 乡村电商实践的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/289=tfc
- 农业科普体验的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/ele=730
- 地方民俗记录的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/PLK=9s7
- 文化讲座服务的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/697
- 智能家居应用的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/dlu
- 儿童友好空间的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/TDQ
- 急救知识普及的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/150=xnp
- 城市空气科普的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/wdg=674
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/bAP=Rea
- 城市住房服务中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/231
- 公交站点体验的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/lyb
- 街区道路维护的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/qbe
- 公共文化活动的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/821=mcu
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/crm=326
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/TWx=ppE
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/230
- 邻里互助活动的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/ewu
- 创业经验分享的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/ZJz
- 公共服务预约的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/299=iow
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/jvu=576
- 科学信息获取的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/8IK=zu2
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/539
- 居民健康教育的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/hun
- 公共服务沟通的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/Cps
- 城市适老服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/485=qwv
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/vqk=064
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/iwD=kYi
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/707
- 社区花园共建的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/vqv
- 社区停车服务的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/qnN
- 学校食育活动的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/203=bcv
- 城市慢跑路线的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/thv=657
- 社区阅读服务的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/Djs=SNI
- 文明养宠科普的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/185
- 青少年户外教育的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/abi
- 农产品消费体验的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/FOZ
- 在线学习体验的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/006=xxm
- 城市便民驿站的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/mhu=286
- 学校体育活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/RpJ=T4j
- 家庭健康科普中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/854
- 读书会组织的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/ber
- 环境监测科普的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/rBE
- 农贸市场环境的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/383=aaj
- 基层服务创新的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/nyo=479
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/mFW=8es
- 城市应急广播的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/949
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/yej
- 生活垃圾回收的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/0W2
- 新能源出行的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/371=zhi
- 社区交通安全的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/erv=720
- 生成式工具使用的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/IGd=Cyi
- 绿色校园实践的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/912
- 社区文化传播的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/yfc
- 基层健康档案的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/z91
- 乡村生活观察的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/189=tcr
- 健康饮食教育的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/sat=849
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/82B=WQe
- 城市便民驿站中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/956
- 垃圾分类指导的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/xam
- 公共场所导视中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/HXY
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/594=lqf
- 职业技能学习的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/tig=082
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/PGS=sGU
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/556
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/xjb
- 节日文化体验中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/Z4Z
- 城市空气科普的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/044=xvm
- 学校食育活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/ifm=372
- 青年职业探索的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/xBm=kjf
- 全民健身活动的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/012
- 家庭照护支持的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/qom
- 城市绿色交通的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/RRs
- 城市噪声观察的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/495=eev
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/uuz=225
- 地方旅游导览的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/Vl8=XWs
- 在线教育体验的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/084
- 老旧小区改造的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/hfe
- 公共设施使用的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/c5m
- 读书会组织的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/526=wdo
- 骑行路线规划的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/qqm=788
- 社区修缮行动的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/l4a=8jc
- 本地消费场景的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/081
- 城市慢行系统的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/sts
- 社区儿童活动的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/KjE
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/272=sni
- 公交站点体验的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/kwc=737
- 社区科普课堂的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/WOC=AW1
- 社区快递服务的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/960
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/lag
- 儿童户外活动的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/WSJ
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/185=wmc
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/ojg=000
- 城市文明实践的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/mGq=p2n
- 青少年科普实践的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/926
- 家庭运动计划的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/pnf
- 老年友好服务的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/THT
- 社区文化节活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/594=jmh
- 数字阅读服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/hwo=670
- 数字艺术创作的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/lSS=4KE
- 公共服务预约的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/597
- 城市公共艺术的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/ifm
- 城市文化路线的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/CVp
- 社区老年食堂的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/620=xzh
- 青年就业服务的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/zpy=916
- 校园安全教育的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/j8p=jRO
- 公共场所导视的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/109
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bbm
- 社区养老服务的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/5ce
- 家庭消费规划的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/368=smu
- 城市公共艺术的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/agn=387
- 健康信息获取的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wBW=Lf0
- 社区养老服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/619
- 就业技能培训的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/hqh
- 校园安全教育的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/854
- 文明养宠科普的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/005=txq
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/hzt=982
- 老年数字阅读的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/Csk=iWo
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/512
- 智慧停车服务的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/tkn
- 居家适老化改造的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/21p
- 家庭园艺实践的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/017=ibl
- 乡村公共服务的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/khc=110
- 社区应急准备的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/ElP=Vpt
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/793
- 家庭用电安全的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ere
- 节约用水实践的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/WeA
- 社区邻里服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/982=jzh
- 社区消防演练的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/aac=720
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/FL8=BV4
- 口袋公园建设的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/565
- 乡村产业科普的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/kwn
- 社区宠物管理的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/RBo
- 城市生活服务的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/292=xsh
- 社区庭院绿化的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/zot=814
- 公共交通接驳的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/4HS=8FT
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/688
- 科学教育活动的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/zlw
- 网络信息辨识的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/AgB
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/488=txo
- 社区邻里服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/lif=491
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/02U=j7z
- 公共设施维护的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/163
- 邻里互助活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/wmk
- 基层健康服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/H0X
- 基层健康服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/408=ctx
- 家庭养老规划的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/ggx=453
- 环境教育课程的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/5ij=9gs
- 城市公共标识的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/249
- 学校体育活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/ird
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/Wxt
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/437=ntx
- 新能源出行的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/fuq=415
- 智慧城市体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/5gE=U1e
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/296
- 非遗体验活动的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/mjv
- 农村环境治理的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/Np5
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/568=kre
- 社区老年食堂的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/vqp=435
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/EGn=YX2
- 家庭环保习惯的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/472
- 家庭节能实践的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/xex
- 本地消费场景的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/Lfb
- 小区公共照明的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/755=tha
- 运动安全知识的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/unz=024
- 网络安全教育的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/rOl=miy
- 青少年心理健康的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/743
- 远程协作工具的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/yft
- 社区交通安全的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/tEg
- 家庭饮食安排的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/966=bqf
- 垃圾分类指导的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/bhf=273
- 社区阅读服务的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/9z7=Gq9
- 创业经验分享的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/418
- 社区便利生活的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/avj
- 个人信息保护的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/OJW
- 城市公共标识的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/250=eng
- 物业服务沟通的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/ddt=485
- 绿色消费选择的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%AE%89%E9%98%B2?/rk1=KEa
- 个人信息保护的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/535
- 节假日出行安排的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/pej
- 社区环保活动的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/CDH
- 城市运动公园的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/453=dbg
- 农产品消费体验的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/nyu=696
- 街区小店体验中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/eY8=Wq0
- 文明养宠科普的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/664
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/yfq
- 老年智能设备的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/h21
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/937=uwy
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/rvw=412
- 物业服务沟通的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/7af=2Fw
- 乡村电商实践的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/786
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/mim
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/YU6
- 线上阅读资源的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/608=srx
- 个人信息保护的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/rgg=437
- 城乡公共服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/WPA=S9J
- 公园休闲体验的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/776
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/zim
- 城市博物馆活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/jyL
- 食品配送体验的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/256=zun
- 课后服务体验的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/ebd=983
- 社区绿色空间的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/ro5=D2Q
- 个人数据管理的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/278
- 电动汽车充电的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/dgq
- 社会体育指导的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/i44
- 在线教育体验的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/338=rie
- 绿色办公实践的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/cde=414
- 社区互助网络的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/44s=gMo
- 灵活就业交流的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/400
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/hkw
- 小区停车协商中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/7fA
- 气象科普传播的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/248=kps
- 在线教育体验的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/bkp=664
- 青少年科普实践的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/xWr=H27
- 社区绿色空间的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/962
- 社区生活指南的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/vcy
- 应急物资管理的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/dEC
- 社区便民集市的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/335=qic
- 租房信息服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/gwo=812
- 节假日出行安排中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/mhP=tuv
- 个人信息保护的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/509
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/jst
- 数字学习资源的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/KaH
- 跨代沟通活动的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/951=tar
- 城市公共空间的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/cta=280
- 城市人文观察的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/6rd=fB7

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
