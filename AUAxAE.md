# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/036
- 文化讲座服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/mci
- 公共文化活动的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/Sa0
- 家庭食品保存的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/514=aor
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/oac=654
- 药品使用科普的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/cc7=q8V
- 图书馆数字服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/962
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/zix
- 社区学习活动的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/y02
- 数字创意课程的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/617=cgi
- 乡村生态观察的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/wmt=151
- 志愿者培训交流的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/crC=mOB
- 城市公共艺术的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/081
- 社区艺术活动的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/tjl
- 城市运动公园的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/Asn
- 街道综合服务的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/668=bfw
- 社区便民服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/etd=036
- 社区交通安全的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/4VJ=uZh
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/040
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/jum
- 公共服务数字化的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/DjC
- 社区体育组织的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/989=msx
- 社区环保活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/cye=996
- 城市水环境观察的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/vGC=Uak
- 城市微更新实践的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/804
- 运动安全知识的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/ltz
- 智能家居应用的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/frm
- 科学观察活动的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/258=ebz
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/zju=128
- 绿色办公实践的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/hsp=t6C
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/168
- 小区停车协商的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/jim
- 城市空气科普的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/w4f
- 青少年户外教育的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/598=mhy
- 生活垃圾回收的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/zwc=022
- 网络信息辨识的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%9A%E5%AE%A2?/TNI=2b0
- 社区志愿服务的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/111
- 公共健身器材的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/lvr
- 骑行路线规划的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/vpF
- 城市步行友好的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/888=mjd
- 城市公共厕所的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/sny=764
- 社区儿童活动的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/6js=AyY
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/358
- 非遗课堂体验的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/mdh
- 全民健身活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/PrZ
- 公共文化活动中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/893=aep
- 绿色出行服务的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/nno=370
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/9BJ=YGJ
- 便民维修服务的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/982
- 创业经验分享的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/ska
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/2OX
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/704=yfl
- 青年就业服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/tuu=656
- 乡村生态观察的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/kb5=qCw
- 社区活动策划的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/902
- 家庭环保习惯的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/snf
- 户外活动组织的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/eq5
- 学校体育活动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/941=gqj
- 社区防暑服务的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/cdi=988
- 数字档案服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/IAp=i8g
- 青年志愿活动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/742
- 开放数据应用的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/dnl
- 周末休闲规划的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/9HW
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/923=nft
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/plg=491
- 城市步行友好的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/G69=ll6
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/350
- 生成式工具使用的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ddc
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/nRO
- 社区共享书架的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/612=tcr
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/xnf=655
- 城市文明实践中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/CXD=yoB
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/996
- 城市文化路线的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/gbr
- 儿童户外活动的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/3ZA
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/623=oxy
- 绿色出行服务的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/plt=071
- 社区活动空间的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/iNi=vuP
- 通勤路线规划的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/333
- 家庭运动计划的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/lft
- 生活服务数字化的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/66x
- 数字艺术创作的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/978=inr
- 周末休闲规划的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/vli=916
- 老年运动活动的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/RLz=KbV
- 社区文化传播的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/386
- 智能家居应用的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/xtj
- 户外活动组织的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/21t
- 新能源出行的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/206=yra
- 数字地图应用的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/hgf=293
- 亲子阅读活动的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/23F=D75
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/166
- 社区便民集市的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/svy
- 低碳社区实践的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/gqG
- 科学信息获取的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/872=tkr
- 智慧城市体验的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/inq=008
- 社区慢性病防控的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/B2a=EAH
- 环境监测科普的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/560
- 文明养宠科普的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/pvh
- 公园亲子设施的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/Tz8
- 文化讲座服务的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/409=yko
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/qyd=252
- 科学运动指导的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/o5K=wc6
- 校园节能行动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/758
- 绿色办公实践的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/jow
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/w0p
- 社区活动空间的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/116=ywc
- 校园安全教育的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/rde=607
- 科学健身方法中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/f4g=ORA
- 传统节日科普的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/419
- 网络安全教育的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/sbb
- 公交无障碍服务的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/Wck
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/770=syu
- 校园安全教育的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/qeh=683
- 青年就业服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%89%8B%E8%AE%B0?/91N=i76
- 城市生活服务的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/569
- 校园节能行动的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/pas
- 城市生活服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/u7A
- 数字设备回收的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/876=fil
- 绿色办公实践的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/dwe=218
- 城市展览体验的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/b00=mmN
- 基层健康档案的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/303
- 本地消费场景的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/jbt
- 数字便民地图的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/BI7
- 社区设施共享的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/498=kbb
- 社区读书角建设的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/llx=961
- 线上阅读资源的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/5rP=Aut
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/728
- 公共空间导览的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/dix
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/eYz
- 个人信息保护的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/995=iob
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/jxu=060
- 基层健康档案的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/kvu=iKh
- 电子商务服务的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/805
- 新能源出行的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/zbz
- 社区便民服务的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/Oer
- 节日文化体验的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/399=iiu
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/aaq=830
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/clY=Xns
- 城乡交流活动的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/135
- 医院导诊服务的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/jps
- 城乡公共服务的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/NGu
- 城市适老服务的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/617=etm
- 社区家校合作的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/vny=634
- 公园休闲体验的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/FO4=bAa
- 地方民俗记录的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/990
- 家庭阅读计划的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/vfk
- 老年友好服务的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/Cm1
- 学校体育活动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/779=sgt
- 非遗课堂体验的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/ngm=187
- 地方文化传播的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/zYx=CoT
- 家庭急救准备的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/283
- 课后服务体验的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/tfu
- 公共交通信息服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/fmh
- 基层健康档案的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/712=gvj
- 个人信息保护的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/rav=726
- 城市公共自行车的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/oEr=dwu
- 网络安全教育的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/949
- 乡村公共文化的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/qmf
- 城市运动公园的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/44J
- 乡村生活观察的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/767=czw
- 城市雨天出行的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/kik=060
- 社区公共卫生的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/LPd=o2x
- 家庭健康科普的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/289
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/bbq
- 小区公共照明的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/D2P
- 开放式学习空间中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/619=vev
- 市民热线服务的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/iua=293
- 农村环境治理的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/fCp=WdN
- 乡村公共文化的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/866
- 社区宠物管理的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/rbt
- 社区健康讲座的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/Php
- 开源技术交流的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/654=uvm
- 节日文化体验的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/vea=587
- 地方文化传播的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%BA%8C%E5%8F%B7%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/VDz=4wC
- 学校食育活动的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/400
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/nwf
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/jUC
- 生活垃圾回收的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/198=dgf
- 市民热线服务的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/xkp=541
- 数据分析入门的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/kbd=m2A
- 便民信息查询的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/760
- 智能手机助老的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/ohq
- 社区读书角建设的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/Xds
- 科学教育活动的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/039=mok
- 城市步行环境的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/ikb=290
- 社区手工活动的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/4XD=uQc
- 便民服务窗口的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/708
- 公共场所导视的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/zrq
- 开源技术交流的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/ltw
- 无障碍出行的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/107=mfu
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/abb=094
- 旧物循环利用的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/3tJ=rbp
- 儿童阅读角的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/548
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/hjk
- 消防知识宣传的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/25E
- 社区菜市场服务的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/763=vts
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/ohm=379
- 食品配送体验中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/JBy=y1R
- 社区修缮行动的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/306
- 公共健身器材的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/aut
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/u4d
- 社区手工活动的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/997=nbe
- 运动安全知识的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/iao=749
- 本地旅行体验的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/fRT=NNU
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/999
- 绿色生活实践的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/nvs
- 老年人出行服务的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/t2M
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/592=paf
- 公共空间照明的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/fxe=396
- 科学教育活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/CvS=pUk
- 社区活动策划的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/069
- 地方文化传播的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/xbt
- 数字设备回收的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/ltw
- 社区互助网络的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/380=oup
- 数字阅读服务的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/djc=530
- 社区便利生活的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/drz=KqZ
- 数字艺术创作的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/375
- 乡村休闲旅游的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/pzn
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/0ww
- 城市农夫市集的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/004=eng
- 地方戏曲体验的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/bny=547
- 图书馆数字服务的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%8F%91%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/jjm=XNV
- 本地消费场景的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/170
- 邻里共享空间的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/czn
- 城市慢行系统的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/3c4
- 社区知识分享的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/622=sew
- 乡村文化活动的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/usd=616
- 地方旅游导览的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%8F%91%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/Ajf=dww
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/684
- 机器人科普活动的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/bic
- 无障碍出行的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/aXj
- 便民维修服务的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/918=ngx
- 社区交通安全的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/rfb=171
- 亲子科普活动的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/itL=V3N
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/220
- 职业技能学习的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/tes
- 日常摄影记录的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/98N
- 城市适老服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/796=gmq
- 图书馆数字服务的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/tia=193
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/2Oe=0zO
- 户外活动组织的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/122
- 小区电梯维护的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/tlt
- 社区文化传播的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/fGG
- 节能家电使用的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/207=nzi
- 乡村产业科普的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/vbe=922
- 骑行路线规划的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%8F%91%E5%BD%A9-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/S3B=lIK
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/089
- 老年人文化生活的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/fum
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/582
- 科普展览体验的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%8F%91%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/111=ipb

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
