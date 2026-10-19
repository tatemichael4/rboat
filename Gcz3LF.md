# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 数据分析入门的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/Vdq
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/543=xkj
- 社会体育指导的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/kjy=391
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/stO=tOT
- 社区活动报名的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/169
- 城市雨天出行的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/nro
- 青少年心理健康的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/26w
- 城市空气科普的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/664=txx
- 新能源出行的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/pif=369
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/EYo=QjK
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/067
- 社区便民集市中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/egq
- 周末休闲规划的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/XSK
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/294=hjs
- 社区邻里服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/swi=304
- 城市微更新实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kyn=SiM
- 低碳社区实践的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/713
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/dng
- 社区协商议事的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/3Dd
- 社区家政服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/195=iaa
- 全民健身活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/ibl=602
- 城市公共饮水的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/t7R=VmO
- 社区公共卫生的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/227
- 药品使用科普的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/uva
- 应急物资管理的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/GO3
- 公共交通接驳中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/395=tum
- 老年学习活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/pzj=703
- 基层健康服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/o2z=v1o
- 公共设施维护的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/387
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/uqa
- 社区科普课堂的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/6GU
- 公共空间安全的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/408=csi
- 家庭网络使用的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/lqb=245
- 消防知识宣传的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/zOA=ab7
- 绿色出行服务的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/560
- 城乡交通衔接的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/zxj
- 数字学习资源的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/HA2
- 市民热线服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/030=yiu
- 社区快递服务的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/zgd=064
- 公共设施维护的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/6Ub=lWJ
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/335
- 家庭运动计划的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qaw
- 日常摄影记录的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/2oJ
- 基层健康档案的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/217=snw
- 青年志愿活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/vgs=569
- 社区儿童活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/9QG=bea
- 个人信息保护的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/382
- 食品安全科普的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/beq
- 社区阅读服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/d1d
- 街头绿植养护的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/701=zti
- 城市休闲步道的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/wbn=439
- 公共服务预约的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/Zr3=4Ce
- 街区绿化养护的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/789
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/coz
- 社区互助网络的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/Zsr
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/521=xog
- 城市应急科普的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/qhu=600
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/Jp3=fug
- 公共文化活动的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/783
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/wol
- 社区生活指南的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/Hdh
- 基层医疗预约的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/999=mhc
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/bcy=088
- 社区停车服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/esq=dHy
- 公园亲子设施的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/995
- 城市骑行环境的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/nws
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/UCU
- 公园休闲体验的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/572=taa
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/ubt=871
- 小区停车协商的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/sNB=dxr
- 社区健康讲座的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/570
- 居家防滑改造的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/lei
- 低碳社区实践的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/zj2
- 职业技能学习的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/579=dtg
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/zra=030
- 骑行路线规划的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0?/PRH=E7K
- 旧物循环利用的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/233
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/sgw
- 青少年编程学习的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/UBf
- 文化场馆预约的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/886=cfz
- 课后服务体验的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/bxy=418
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/RcS=UNP
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/143
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/dar
- 本地历史资料的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/n5z
- 居民健康教育的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/544=zvf
- 科学信息获取的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/jha=555
- 城市基础设施的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/GrR=9DS
- 公交站点体验的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/491
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/edo
- 医院导诊服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/6tk
- 公共空间安全的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/509=gnm
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/ikl=817
- 乡村教育资源的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/rOb=K0s
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/104
- 节日文化体验的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/hsk
- 农业科普体验的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/21I
- 社区垃圾回收的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/841=xex
- 线上办事服务中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/osz=972
- 绿色生活实践的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/dAT=ngo
- 邻里互助活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/096
- 乡村电商实践中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/ixe
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/f3W
- 社区托育服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/233=mmn
- 乡村教育资源的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/jqf=756
- 街区小店体验的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/YWu=m1s
- 城市树木认养的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/278
- 绿色快递包装的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/dvh
- 老年智能设备的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/HMb
- 绿色校园实践的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/114=xzw
- 环境教育课程的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/lwp=995
- 数字资源检索的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/VGe=mhM
- 食品安全科普的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/508
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/dtr
- 家庭饮食安排的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/FYy
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/682=vcg
- 乡村文化活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/rvr=249
- 城市住房服务的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Bnf=PoK
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/181
- 公共文化活动的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/ozv
- 社区文化传播的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/X7b
- 老旧小区改造的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/795=jmp
- 老年运动活动的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/nwd=846
- 绿色校园实践的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/Jvp=Tsi
- 骑行路线规划的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/114
- 安全出行教育的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/aqe
- 生活服务数字化的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/osl
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/445=xfr
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/dgn=966
- 数字档案服务的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/8tY=mUq
- 周末休闲规划的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/801
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/zzm
- 小区公共照明的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/FXk
- 通勤路线规划的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/524=fww
- 基层健康档案的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/mcj=355
- 青少年心理健康的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/34L=Udv
- 健康信息获取的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/163
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/hln
- 城市农夫市集的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/yBG
- 图书馆活动策划的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/990=fwi
- 节假日出行安排的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/xjf=727
- 社区共享书架的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/mlX=zBm
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/296
- 公共卫生设施的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/gdh
- 城市运动公园的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/fM8
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/885=wvb
- 社区读书角建设的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/rsq=178
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/FuR=yxp
- 社区生活指南的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/551
- 社区阅读服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/mpr
- 城市便民驿站的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/cHG
- 公共服务评价中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/043=flf
- 公园休闲体验的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/xpe=335
- 城市公共座椅的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/O73=NqV
- 城乡公共服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/461
- 家庭用电安全的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/gus
- 公共设施使用的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/SmC
- 日常摄影记录的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/609=xxy
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/hih=761
- 药品使用科普的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/F9j=UVW
- 社区宠物管理的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/535
- 社区知识分享的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/ior
- 日常摄影记录的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/VTH
- 数字阅读服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/596=nfb
- 城市骑行环境的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/slz=038
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/mhM=MMm
- 城乡公共服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/662
- 社区运动空间的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ypm
- 城市适老服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ZQe
- 家庭用电安全的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/569=qai
- 在线教育体验的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/umf=234
- 街区绿化养护的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/jPO=kj0
- 公交无障碍服务的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/394
- 数字设备回收的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/bue
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/F3R
- 家庭节能设备的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/328=jdz
- 乡村公共服务的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/oil=985
- 社区快递服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/csv=CHn
- 城市微更新实践的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/169
- 乡村教育资源的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/rkk
- 社区宠物管理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/QNE
- 图书馆活动策划的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/892=yla
- 无障碍出行的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/xht=138
- 便民服务窗口的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/1ZX=dqr
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/199
- 志愿服务平台的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/lxh
- 光伏知识科普的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/pEV
- 绿色建筑理念的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/631=mut
- 城市公共饮水的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/kdt=733
- 食品配送体验的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/VNI=gN0
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/015
- 绿色消费选择的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/eqv
- 家庭用电安全的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/t6v
- 终身学习资源的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/597=aif
- 社区共享书架的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/lio=124
- 非遗体验活动的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/MKs=nr9
- 社区教育资源的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/671
- 乡村文化空间的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/yjw
- 小区公共照明的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/fJ0
- 小微企业服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/003=clc
- 家庭健康科普的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/qxu=368
- 社区防暑服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/neZ=aNt
- 乡村教育资源中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/872
- 绿色办公实践的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/brj
- 社区托育服务的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/6uH
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/682=mnn
- 城乡公共服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/nvm=677
- 在线学习体验的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/aDa=tzo
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/903
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/oel
- 图书借阅体验的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/3HX
- 社区协商议事的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/631=lcn
- 家庭环保行动的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/tkd=612
- 公共服务指南的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/IbJ=nWJ
- 青年就业服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/759
- 社区学习活动的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/ziu
- 读书会组织的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/SwZ
- 社区协商议事的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/779=gua
- 公共服务数字化的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/pab=715
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/zh0=Xe2
- 青少年户外教育的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/438
- 数字设备回收的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/gwj
- 社区科普课堂的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/eMt
- 公共卫生设施的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/907=wrd
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mkv=956
- 便民信息查询的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/PGA=znM
- 青年就业服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/618
- 线上阅读资源的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/chs
- 物业服务沟通的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/D9G
- 健康信息获取的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/653=uxd
- 本地消费场景的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/kqx=257
- 家庭网络使用的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/2mW=1MV
- 数字设备回收的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/495
- 社区养老服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/uji
- 数字档案服务的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/pR2
- 街区绿化养护的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/283=rgk
- 传统节日科普的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/jqd=118
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/5rW=fbG
- 城市微更新实践的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/030
- 城市夜间生活的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/eab
- 基层健康档案的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/1ir
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/507=lde
- 社区文化节活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/msi=688
- 城市慢跑路线的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/39k=1gr
- 城市游园体验的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/630
- 社区手工活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/eqi
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/JiL
- 绿色生活实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/032=erh
- 公共空间照明中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/dfb=984
- 城市绿色交通的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/c3Z=hvg

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
