# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 社区艺术活动的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/258
- 便民维修服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/gtp
- 乡村生态观察的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/uuM
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/845=iaz
- 社区健康讲座的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/fen=266
- 健康饮食教育的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%A5%BD_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/sWG=iOJ
- 户外活动组织的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/416
- 社区公共卫生的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/qet
- 智能手机助老的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/9w1
- 居民健康教育的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/543=oos
- 地方文化传播的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/oml=649
- 药品使用科普的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/TVd=XXh
- 光伏知识科普的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/302
- 本地消费场景的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/pfq
- 数字资源检索的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/Btu
- 读书会组织的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/851=mwq
- 非遗体验活动的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/xzh=086
- 数字创作工具的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/huf=mML
- 社区交通安全的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/269
- 科普展览体验的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/mom
- 家庭运动计划的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/xF1
- 城市博物馆活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/446=kdq
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/unx=866
- 科普展览体验的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/ai0=vYi
- 科普展览体验的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/980
- 日常摄影记录的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/gzx
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/rW3
- 青年就业服务的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/294=jgb
- 城市公共艺术的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/icx=140
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/Hpr=c3N
- 社区设施共享的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/321
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/kfe
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/peA
- 社区生活指南的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/542=wjf
- 社区修缮行动的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/xzd=054
- 城市住房服务的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/AqJ=hY7
- 科学健身方法的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/775
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/clj
- 口袋公园建设的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/wXB
- 软件开发学习的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/773=gbg
- 个人数据管理的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/sem=726
- 家庭用电安全的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/nZe=bqa
- 软件开发学习的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/719
- 家庭节能设备的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/rrb
- 社区应急准备的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/GoK
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/051=exi
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/itq=640
- 社区防暑服务的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/bSa=jh5
- 人工智能科普的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/127
- 社区法律科普的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/lgb
- 公共服务评价的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/aty
- 生活技能分享的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/325=yyp
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/frs=037
- 社区垃圾回收的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%BA%AE%E7%82%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/uLn=Coi
- 图书馆活动策划的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/061
- 社区文化传播的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/kfz
- 街区绿化养护的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/LZl
- 公共场所导视中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/217=nld
- 社区绿色空间的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/qps=591
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%B9%E8%89%B2_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/OEZ=t1F
- 周末休闲规划的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/854
- 社区志愿服务中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/djp
- 社区信息发布的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/Pes
- 药品使用科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/171=ndb
- 志愿者培训交流的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/ack=769
- 绿色生活实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E9%99%85?/iO8=F5k
- 非遗课堂体验的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/037
- 旧物循环利用的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/uyx
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/mjd
- 地方旅游导览的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/497=ojt
- 青少年科普实践的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/ewh=104
- 休闲运动入门的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3iOS%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/V2y=twA
- 急救知识普及的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/350
- 社区环保活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/rxz
- 数字学习资源的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/hnS
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/913=xjw
- 软件开发学习的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/nlf=168
- 社区花园共建的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/YKI=5PB
- 街区更新实践的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/242
- 安全出行教育的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/yui
- 公共服务咨询的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/eCA
- 居家防滑改造中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/596=dvg
- 科学教育活动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/ajj=430
- 社区邻里服务的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/A36=4ur
- 社区活动报名的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/033
- 健康饮食教育的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/muf
- 校园阅读活动的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/TNI
- 城市空气科普的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/085=wma
- 城市展览体验的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/tyc=685
- 图书借阅体验的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E7%9C%8B%E5%88%B0_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/V5f=ka0
- 家庭教育交流的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/143
- 物业服务沟通的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/qjj
- 公共空间照明的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/S6K
- 家庭园艺实践的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/014=lyz
- 社区便民集市的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/ehn=598
- 社区学习活动的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/xlp=NLB
- 城市便民驿站的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/116
- 乡村教育资源的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/pbi
- 城市文化路线的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/Oqs
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/658=ddo
- 老旧小区改造的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/pij=321
- 城市公共空间的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/6rZ=qLi
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/949
- 口袋公园建设的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/qvq
- 城市展览体验的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/U2o
- 街头绿植养护的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/598=txk
- 居家防滑改造的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/yms=895
- 家庭环保行动的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/pFe=EH0
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/483
- 传统节日科普的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/mlq
- 终身学习资源的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/6XR
- 家庭健康管理的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/309=lat
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/osb=871
- 数据分析入门的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%94%90%E8%AF%84?/Shd=a0d
- 绿色生活实践的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/043
- 社区垃圾回收的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/gwb
- 网络安全教育的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/Mgj
- 学校体育活动的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/395=aaf
- 社区安全巡查的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/oiw=096
- 公共图书馆服务的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/c8N=97A
- 社区商业活力的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/890
- 家庭节能实践的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/dbr
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/Zwe
- 小区公共照明的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/891=mto
- 城市建设科普的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/ryz=148
- 家庭教育交流中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/36d=858
- 职业技能学习的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/526
- 公交站点体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/evw
- 社区防暑服务的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/AL3
- 运动安全知识的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/919=kst
- 公共卫生设施的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/puu=823
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/cf5=s4y
- 家庭饮食安排的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/916
- 家庭运动计划的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uhl
- 数字生活课堂的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/9jH
- 骑行路线规划的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/782=yxh
- 老年运动活动的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ele=080
- 公益活动组织的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/o0B=ZJK
- 公益活动组织的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/831
- 城乡公共服务的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/bra
- 家庭消费规划的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Ee7
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/231=kmt
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/deq=950
- 儿童阅读角的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/hft=zP6
- 社区停车服务的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/909
- 数据分析入门的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rjh
- 家庭消费规划的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/0qa
- 城市文明出行的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/662=olh
- 数字创意课程的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fcj=218
- 节日文化体验的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wk1=nOa
- 儿童户外活动的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/093
- 节能生活方式的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/ixy
- 创业经验分享的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/k25
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/472=zrx
- 城市步行友好的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/myp=004
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/WU3=1iy
- 社区活动报名的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/789
- 城市基础设施的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/qev
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/XRd
- 机器人科普活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/453=qft
- 学校食育活动的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/dyr=196
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/Yth=eV3
- 网络安全教育的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/991
- 小区停车协商的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/hcn
- 社会体育指导的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/gbX
- 市民热线服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/764=fvy
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/axe=973
- 城市绿色交通的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/Fd5=0y1
- 社区健康讲座的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/897
- 城市步行友好的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gou
- 乡村阅读空间的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/GeV
- 社区停车服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/355=zuf
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ick=385
- 节能家电使用的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89app%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/veN=4h5
- 居家适老化改造的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/783
- 绿色建筑理念的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/ysu
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/0oi
- 街区更新实践的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/919=htw
- 科学运动指导的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/aej=436
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/mS6=QVY
- 城市夜间生活的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/780
- 城市夜间生活的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ppb
- 城市共享单车的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xdg
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/967=aeo
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/epb=494
- 青年就业服务的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/bcG=RXw
- 校园安全教育的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/829
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/ckh
- 环境教育课程的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/6pA
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/507=ohh
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/wlu=449
- 课后服务体验的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E8%8B%B9%E6%9E%9C_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/TMc=7Jl
- 公共场馆服务的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/819
- 家庭科学教育的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/sip
- 光伏知识科普的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/p8g
- 健康信息获取的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/009=xoy
- 乡村文化活动的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/jtj=298
- 非遗体验活动的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/YA4=Uyz
- 个人数据管理的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/862
- 城市公共座椅的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/idq
- 小区电梯维护的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/AzJ
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/604=hqk
- 公共空间休憩的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/vdp=860
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/TFt=oBb
- 数字课堂应用的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/954
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/mqa
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/Efc
- 乡村文化空间中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/946=cfy
- 科普展览体验的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/hcf=663
- 线上阅读资源的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/c0E=ch6
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/359
- 乡村产业科普的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/hsj
- 科学教育活动的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/U9L
- 社区共享书架的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/411=lqb
- 校园节能行动的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/yrj=855
- 急救知识普及的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97-%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/OJA=J5e
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/883
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/xky
- 青少年户外教育的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/dVV
- 消防知识宣传的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/081=sup
- 社区老年食堂的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/zhm=372
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/ESI=bBv
- 地方民俗记录的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/359
- 儿童安全出行的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/kjv
- 数字创意课程的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/Kwt
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/287=xqr
- 公共服务咨询的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/zuz=719
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/DNu=bjE
- 课后服务体验的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/933
- 城市社区治理的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/ued
- 城市文明出行的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/1uf
- 社区公共议事的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/427=zwu
- 本地消费场景的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/lmp=814
- 生活服务数字化的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/Gi0=HCI
- 儿童友好空间的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/805
- 社区公共议事的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/rks
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/3rf
- 老年友好服务的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/266=xbl
- 城市博物馆服务的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/uuf=558
- 线上办事服务中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/EWu=61t
- 老年学习活动的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/785
- 乡村产业科普的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/lup
- 公共服务预约的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/Wcn
- 家庭阅读计划的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/068=xwp
- 网络安全教育的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/rlc=208
- 数字素养提升的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/U9U=9zN
- 地方戏曲体验的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%9E%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/967
- 居家适老化改造的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%9E%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/hpf
- 周末休闲规划的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%9E%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/fla
- 城市应急科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%9E%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/911=uzr

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
