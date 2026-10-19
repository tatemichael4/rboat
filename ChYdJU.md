# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 城市游园体验的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/AmB
- 城市步行友好中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/752=vgh
- 公共服务评价的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/eoq=990
- 公共设施维护的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/Mmc=Fgh
- 社区养老服务的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/152
- 公共设施维护的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/xey
- 城市水环境观察的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/Yy4
- 节假日出行安排的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/485=xro
- 城市步行环境的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/vbm=513
- 科学信息获取的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/nbU=kbj
- 社区志愿服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/229
- 医院导诊服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/jfv
- 城市农夫市集的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/gIC
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/609=dly
- 开源技术交流的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/ijn=692
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/8Bc=yl0
- 城市公共自行车的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/239
- 居家防滑改造的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ltz
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/Lo3
- 地方文化传播的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/834=bzw
- 校园社团活动的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/lpl=674
- 社区邻里服务的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/wN5=Mz0
- 社区共享书架的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/016
- 城市应急广播的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/rha
- 家庭急救准备的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/6Ep
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/089=twc
- 远程协作工具的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/ubx=970
- 科学教育活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/WHx=xbS
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/199
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/pew
- 城市公共标识的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/BsC
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/217=mee
- 科普展览体验的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/tgk=682
- 公共服务沟通的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/G4u=6C6
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/855
- 文明养宠科普的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/nvp
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/SfT
- 农业科普体验的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/724=quy
- 新能源出行从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/iwy=974
- 公共交通接驳的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/pcx=14V
- 开放式学习空间的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/696
- 城市共享单车的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ehn
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/Fzc
- 公共服务预约的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/453=dmc
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/rrh=275
- 青年职业探索的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/1Li=keg
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/647
- 城市应急科普的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/kiz
- 街道综合服务的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/Txw
- 社区环保活动的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/964=tll
- 社区托育服务的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/qlg=520
- 个人信息保护的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/vEO=OSv
- 劳动教育实践的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/601
- 租房信息服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/zsp
- 城市运动公园的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/vWy
- 儿童友好空间的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/761=ktc
- 城市应急科普的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/ocp=910
- 在线教育体验的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/ZQZ=oWQ
- 无障碍信息设计的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/825
- 便民服务窗口的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/ala
- 公共场所导视的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/IR1
- 应急物资管理的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/054=xxw
- 图书馆活动策划的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/knt=294
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/ITP=SfF
- 社区志愿服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/068
- 城市公共座椅的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/irq
- 城市游园体验的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/vsX
- 城市骑行环境的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/412=jvd
- 街区道路维护的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/wts=042
- 城市适老服务的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/Tpb=TWH
- 城市社区治理的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/015
- 农产品消费体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/wpj
- 街区更新实践的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/1mf
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/167=lsj
- 家庭节能设备中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/lzh=925
- 便民服务窗口的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/Ybq=ioU
- 公共空间照明的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/968
- 老年友好服务的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/bmb
- 智慧城市体验的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/1HC
- 社区宠物管理的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/968=eyx
- 乡村文化空间的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/nzd=591
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/9rY=iD1
- 城市生活记录的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/491
- 科学观察活动的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/kzy
- 城市运动公园的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/1Sl
- 乡村文化活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/579=ehj
- 家庭节能实践的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/dcv=635
- 公共服务沟通的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/Clc=e9j
- 学校食育活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/548
- 非遗体验活动的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/mii
- 基层健康档案的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/avh
- 绿色消费选择的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/818=vwt
- 社区安全巡查的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/yzr=715
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/RsP=oBR
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/700
- 老年友好服务的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/gpg
- 城市社区治理的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/mwo
- 家庭节能设备的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/605=hho
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/wyb=022
- 城市微更新实践中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/6GN=ZLV
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/555
- 运动安全知识的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/qzs
- 城市公共饮水的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/28a
- 骑行路线规划的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/935=imn
- 基层健康档案的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/jyx=360
- 应急物资管理的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/N3a=DcM
- 软件开发学习的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/191
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/wgk
- 社区老年食堂的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/Dw9
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/824=pgx
- 开放数据应用的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/dkr=601
- 数字生活课堂的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/pqz=vWq
- 食品配送体验的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/472
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/rtv
- 社区教育资源的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/pJv
- 城市公共自行车的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/560=vhy
- 居家防滑改造的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/ozh=740
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%88%8A%E7%99%BB?/6xc=Iuo
- 公共场馆服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/169
- 社区公共餐饮的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/akd
- 地方文化传播的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/mHc
- 社区花园共建的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/621=gqb
- 城市文明实践的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/pzq=062
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/UBt=l24
- 数字便民地图的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/758
- 基层健康档案的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/ifx
- 公交站点体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/OIE
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/807=bhg
- 街区绿化养护的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/yrb=849
- 家庭饮食安排的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/tGO=LhD
- 家庭安全提示的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/842
- 社区共享书架的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/fgd
- 数字创意课程的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/4fI
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/775=yes
- 光伏知识科普的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/mwr=181
- 社会体育指导的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/sVM=VDo
- 生活垃圾减量的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/936
- 应急物资管理的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/cll
- 租房信息服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/wGt
- 家庭环保习惯的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/853=daa
- 急救知识普及的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/krg=812
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/CGV=J12
- 数据分析入门的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/494
- 城市夜间照明的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/ych
- 家庭阅读计划的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/RRg
- 青少年科技社团的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/708=gik
- 数字创意课程的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/bsw=444
- 社区学习活动的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/DQP=D4T
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/843
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/pez
- 社区健康讲座中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/Hoc
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/917=hyx
- 日常摄影记录的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/owi=002
- 公益活动组织的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/0V3=vKz
- 科学观察活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/736
- 乡村公共文化的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/cyv
- 机器学习入门的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/MY7
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/582=vgl
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/jxe=332
- 社区邻里服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%B3%A8%E5%86%8C_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/I9C=mRM
- 城市人文观察的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/243
- 社区邻里服务中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/opp
- 街区小店体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/Y1I
- 绿色办公实践的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/241=fiq
- 家庭消费规划的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/aub=567
- 药品使用科普的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/NWL=QSr
- 社区信息发布的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/784
- 老年数字阅读的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/pun
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/TUr
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/338=nud
- 便民信息查询的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/lkn=444
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/uEW=74D
- 居家防滑改造的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/135
- 社区环保活动的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/rei
- 社区设施共享的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/EaZ
- 家庭教育交流的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/847=khr
- 邻里共享空间的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/ctf=209
- 基层服务创新的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/Lsn=kZs
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/651
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/zqe
- 城市文明出行中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/0yB
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/378=kje
- 小区电梯维护的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/yro=328
- 图书借阅体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/t0I=K1n
- 社区便民集市的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/730
- 校园安全教育的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/qzy
- 城市文明出行的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/k8n
- 节日文化体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/195=wsu
- 社区庭院绿化的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/ulu=513
- 消防知识宣传的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/ZLc=KoF
- 周末休闲规划的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/762
- 乡村公共文化的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/peb
- 社区健康讲座的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/kqq
- 社区便民集市的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/694=hyi
- 基层健康服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/jxw=963
- 城市展览体验的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/pBI=05K
- 志愿者培训交流的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/201
- 便民维修服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/kmo
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/525
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/241=hhl
- 城市文明出行的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/zhe=324
- 气象科普传播的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/R1E=Nw6
- 社区学习活动的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/417
- 公共场所导视的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/iou
- 无障碍出行的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/gIF
- 图书借阅体验的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/782=bur
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/qfb=992
- 小微企业服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/6QG=WYZ
- 儿童安全出行的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/768
- 社区活动空间的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/kqm
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/vL1
- 家庭用电安全的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/010=coi
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/tsk=089
- 家庭食品保存的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/jBU=xHn
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/983
- 校园社团活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/jwm
- 老年智能设备的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/wvj
- 开放式学习空间的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/501=jln
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/omp=180
- 社区活动空间的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/srm=a32
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/145
- 本地历史资料的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/gve
- 环境监测科普的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/9me
- 基层健康档案的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/931=qzm
- 家庭防灾准备的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/qne=806
- 社区体育组织中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B1%BD%E8%BD%A6?/di6=J7i
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/615
- 乡村产业科普的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/uel
- 公共场所导视的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/FIf
- 就业技能培训的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/319=wqs
- 家庭教育交流的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/jwn=866
- 公共空间导览的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E7%99%BB%E5%BD%95welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/K2Z=VNT
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/759
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/wqa
- 社区商业活力的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/zJ7
- 邻里互助活动的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/218=fkq
- 公交站点体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/jds=602
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/Oav=3PH
- 远程协作工具的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/186
- 数字素养提升的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/hmq
- 生成式工具使用的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/Rkc
- 城市共享单车的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/280=jjj
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/ski=401
- 全民健身活动的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/9CX=Bj5
- 城市博物馆活动的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/233
- 线上办事服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/bqu
- 社区法律科普的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/0iN
- 社区文化传播的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/739=vkc
- 社区邻里服务的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/vaa=060
- 社区文化传播的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/BPy=XOy

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
