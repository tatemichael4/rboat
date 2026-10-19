# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 租房信息服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/594
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/yhe
- 社区科普课堂的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/dCO
- 软件开发学习的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/358=oht
- 志愿者培训交流的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/aix=928
- 在线教育体验的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/dkP=emO
- 青少年科技社团的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/608
- 机器人科普活动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/vaj
- 绿色办公实践的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/zAP
- 老旧小区改造的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/179=elr
- 志愿服务平台的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/fpb=325
- 社区志愿服务的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%9C%9F%E8%B4%A7?/BfG=4Im
- 城乡公共服务的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/834
- 小微企业服务的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/tfy
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/K6Y
- 数字档案服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/130=dbh
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/hyn=384
- 数字政务体验的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/9ys=8mb
- 绿色消费选择的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/614
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/ihd
- 志愿者培训交流的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/Tqq
- 公益活动组织的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/987=auc
- 科技馆参观体验的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/abz=495
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/4Py=1dZ
- 数字生活课堂的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/010
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sgs
- 社区便民集市的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5SM
- 社区慢性病防控的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/426=pbd
- 生成式工具使用的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nkw=746
- 社区活动报名的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dqr=Hlq
- 家庭节能设备的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/783
- 城市公共饮水的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/phe
- 电子商务服务的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/KII
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/501=qro
- 市民热线服务的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/rqz=537
- 家庭饮食安排的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/U0A=sMz
- 城市公共标识的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/044
- 节气饮食文化的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/lsa
- 街头绿植养护的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/Fao
- 城市博物馆活动的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/531=lef
- 公交站点体验的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/tkn=376
- 家庭环保习惯的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/l30=P5F
- 城市生活服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/263
- 老年友好服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/bqn
- 城市绿色交通的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/tZq
- 文明养宠科普的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/152=tsx
- 生成式工具使用的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/ayv=251
- 家庭健康管理的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/eAT=S3A
- 志愿者培训交流的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/554
- 小区公共照明的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/mfq
- 街区绿化养护的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/0FZ
- 社区学习活动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/757=eze
- 开放数据应用的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/ppa=133
- 地方民俗记录的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/FOv=kvf
- 旧物循环利用的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/268
- 社区快递服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/rlm
- 绿色出行服务的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/lTo
- 老年友好服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/264=ywa
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/emb=096
- 老年运动活动的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/4xh=6aS
- 低碳社区实践的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/361
- 街道综合服务的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/lof
- 智慧停车服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/7on
- 公共空间导览的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/864=fmv
- 社区家政服务的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/emr=287
- 口袋公园建设的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/9ia=y6V
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/606
- 传统节日科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/dwr
- 社会体育指导的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/Gln
- 非遗体验活动的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/955=bhw
- 城市生活服务的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/nbz=996
- 城市运动公园的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/K58=Sia
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/534
- 街区道路维护的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/gbp
- 文化讲座服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/pG4
- 低碳社区实践的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/335=kwr
- 儿童友好空间的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/uuf=707
- 数字政务体验的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/NJH=gAL
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/807
- 社区快递服务的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/xxr
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/Evp
- 街区更新实践的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/426=fkw
- 网络安全教育的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/gzf=791
- 青年职业探索的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/Nq6=vQG
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/215
- 传统节日科普的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/ucz
- 社会体育指导的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/3LP
- 食品配送体验中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/777=bkv
- 城市文化路线的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/ecs=956
- 城市应急广播中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/22K=R6B
- 终身学习资源的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/934
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/pfh
- 绿色消费选择的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/98D
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/935=igw
- 数字课堂应用的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/vyt=947
- 家庭安全提示的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/DUp=SR7
- 城市树木认养的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/825
- 居家防滑改造的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/ekf
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/bxZ
- 公交站点体验的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/364=bpr
- 机器学习入门的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/rcs=806
- 社区科普课堂的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/sRo=8jF
- 智能手机助老的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/743
- 数字便民地图的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/piy
- 图书馆活动策划的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/yC2
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/326=wfz
- 社区商业活力的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/mgm=186
- 家庭收纳实践的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8A%A1?/OtF=of8
- 开放式学习空间的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/658
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/imf
- 个人时间管理的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/2Ba
- 数字艺术创作的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/571=baf
- 家庭安全提示的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/itv=160
- 城市公共自行车的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/wsQ=w3Q
- 乡村公共文化中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/278
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/hux
- 校园阅读活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/hgf
- 租房信息服务中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/549=czv
- 开放式学习空间的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/sgc=423
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/gUL=9YB
- 乡村生活观察的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/600
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/bby
- 乡村公共文化的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/N34
- 公共图书馆服务的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/390=ifd
- 线上办事服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/aps=786
- 节日文化体验的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/TEv=JJ2
- 本地历史资料的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/138
- 城市博物馆活动的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/zlr
- 终身学习资源的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/Njh
- 科学教育活动的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/025=zbg
- 农村环境治理的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/gqy=275
- 社区垃圾回收的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/j8Z=pyK
- 城市地名文化的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/601
- 就业技能培训的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/wvf
- 社区老年食堂的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/fb5
- 节约用水实践的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/951=hmn
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/szr=843
- 社区便利生活的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/D9W=tJM
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/820
- 社区便利生活的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/cry
- 口袋公园建设的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/2dU
- 数字档案服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/695=ght
- 青少年户外教育的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/zvj=679
- 城市噪声观察的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/2Kw=0U5
- 社区互助网络的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/382
- 绿色生活实践的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/bsn
- 社区家校合作的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/SUn
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/260=bqc
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/uzl=875
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/Z3a=Vvp
- 地方美食文化的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/076
- 垃圾分类指导的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/mkh
- 家庭环保行动的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/IuO
- 公共空间导览的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/983=uoa
- 电动汽车充电的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/pub=853
- 城市文化路线的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/Rjl=idZ
- 城市适老服务的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/974
- 城市人文观察的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lts
- 城乡公共服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/WcB
- 城市文化路线的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/529=vdp
- 生活技能分享的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/dhp=001
- 老年智能设备的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/433=NvA
- 社区文化节活动的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/860
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/snc
- 青年职业探索的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/wXC
- 街区更新实践的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/996=ugx
- 乡村文化活动的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/ksb=104
- 传统节日科普的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/d7S=JkE
- 社区菜市场服务的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/131
- 传统节日科普的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/tui
- 小区公共照明的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/ShS
- 城市文明实践的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/799=cia
- 运动安全知识的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/zcx=747
- 本地历史资料的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/UAA=QVk
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/153
- 社区休闲设施的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/qoz
- 老年友好服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/bGp
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/289=vaq
- 校园阅读活动的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/ixh=764
- 社区安全巡查的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/rKU=XDI
- 小区电梯维护的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/479
- 城市应急广播的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/jup
- 城市雨天出行的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/MkT
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/033=tyo
- 社区科普课堂的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/edb=595
- 青少年心理健康的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/Lfs=5F6
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/055
- 家庭急救准备的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/xwf
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/Qu9
- 社区庭院绿化的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/958=thp
- 邻里互助活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/xjb=866
- 生活服务数字化的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/kD3=20K
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/470
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/kdk
- 传统手工艺体验的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/Fu6
- 城市人文观察的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/756=wli
- 城市文明实践的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/koo=721
- 社区读书角建设的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/JHp=V1E
- 居民健康教育的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/916
- 个人时间管理的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/mcn
- 公共交通接驳的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/tFY
- 邻里共享空间的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/461=gbb
- 城市便民驿站的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/ygd=951
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%88%8A%E7%99%BB?/pWl=9v8
- 儿童安全出行的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/763
- 绿色办公实践的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/vot
- 社区设施共享的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/qpF
- 家庭节能实践的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/295=uuh
- 开放式学习空间的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/gkg=410
- 家庭运动计划的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/Kp8=x0e
- 社区儿童活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/968
- 生活垃圾减量的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/rdq
- 街区更新实践的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/FJi
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/050=yus
- 城市便民驿站的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/wtx=207
- 老年人日常照护的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/eku=Ks5
- 绿色校园实践的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/678
- 城市文明出行的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/sqr
- 在线教育体验的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/m6R
- 城市夜间照明的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/943=rii
- 家庭饮食安排的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/xzb=783
- 开放式学习空间的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/W14=pK5
- 节约用水实践的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/275
- 在线学习体验的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/qsq
- 人工智能科普的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/OjN
- 健康饮食教育的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/812=urc
- 数字艺术创作的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/tdy=521
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/m5s=pRk
- 科技馆参观体验的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/845
- 市民热线服务的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/ria
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/OFE
- 城市公共空间的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/614=khl
- 科学健身方法的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/foj=930
- 城市人文观察中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/CQA=8gN
- 创业经验分享的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/984
- 社区阅读服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/sni
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/Ftg
- 社区托育服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/362=ops
- 新能源知识普及的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/qad=869
- 科学信息获取的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/UcU=oz8
- 城市夜间生活的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/905
- 数据分析入门中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/cxt
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/0Hj
- 数字地图应用中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/277=xff
- 青少年户外教育的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/vsi=757
- 劳动教育实践的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/yDJ=xkv
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/894
- 青少年户外教育的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/goq
- 城市文明实践的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/fZG
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/730=bol

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
