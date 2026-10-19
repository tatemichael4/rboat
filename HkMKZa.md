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

- 数字公共文化的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/pQq
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/538=myx
- 社区健康讲座的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/gtd=316
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/5fw=dtC
- 公共设施维护的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/680
- 城乡交通衔接的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/jnh
- 文化场馆预约的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/pRu
- 城市文明实践的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/875=bsj
- 城市慢行系统中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/bue=014
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/jqo=a38
- 文化场馆预约的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/715
- 城市体育设施的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/vee
- 绿色快递包装的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/7oU
- 健康饮食教育的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/928=dmw
- 药品使用科普的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/paz=173
- 社区邻里服务的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/Vud=VQR
- 个人时间管理的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/291
- 社区设施共享的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/lrm
- 社区阅读服务的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/PwD
- 课后服务体验的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/172=bak
- 城市便民驿站的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/dsc=066
- 青少年心理健康的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/788=mYR
- 公共场所导视的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/785
- 城市雨天出行的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/rdx
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/EIG
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/292=kfs
- 社区信息发布中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/nbb=674
- 城市空气科普的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/eMi=i4V
- 社区托育服务的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/357
- 机器学习入门的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/qgf
- 公共设施使用的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Ynz
- 小区停车协商的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/487=tkk
- 乡村文化空间的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/zmf=265
- 科学观察活动的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Snk=VpC
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/782
- 数字生活课堂的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/kxl
- 线上阅读资源的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/y2z
- 城市夜间生活的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/395=ohd
- 农产品消费体验的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/ies=813
- 公交站点体验的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/7s3=jwm
- 公园亲子设施中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/819
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/lys
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/A9x
- 乡村生态旅游的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/049=hfs
- 生活垃圾回收的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/xjx=427
- 青少年户外教育的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/wGt=I83
- 农贸市场环境的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/354
- 社区共享书架的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/npj
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/Vgf
- 城市社区治理的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/947=jnv
- 生活服务数字化的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/ldx=623
- 社区手工活动的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/Pkv=ahx
- 节能家电使用的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/589
- 绿色快递包装的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/sul
- 健康步道使用的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/R0s
- 社区环保活动的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/462=gtg
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/pdo=220
- 电子商务服务的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/QcS=rub
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/217
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/gxw
- 本地历史资料的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/kaY
- 社区托育服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/722=sei
- 居家适老化改造的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/ovq=761
- 城市可持续生活的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/4UM=Wmf
- 社区环保活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/687
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/pwi
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/ViV
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/285=kjh
- 小区公共照明的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/kri=313
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/E72=tCv
- 家庭节能实践的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/091
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/vxk
- 劳动教育实践的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/Isy
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/205=jpo
- 社区应急准备的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/nin=046
- 居家防滑改造的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/wZM=UzI
- 城市博物馆服务的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/818
- 城市骑行环境的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/glx
- 社区运动空间的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ibR
- 绿色生活实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/042=buk
- 社区公共餐饮的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/qls=487
- 环境监测科普的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/1xl=LHy
- 城市运动公园的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/268
- 传统节日科普的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/qqr
- 基层服务创新的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/hU5
- 社区商业活力的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/723=jbz
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/pdh=275
- 乡村生态观察的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/wOZ=57k
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/626
- 城市文明实践的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/pzo
- 儿童安全出行的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/NtB
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/736=oof
- 基层健康档案的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/vmg=111
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/aCa=05q
- 城市基础设施的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/209
- 城市应急科普的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/gtt
- 老年人日常照护的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/fxW
- 数字艺术创作中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/759=ldy
- 开源技术交流的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/rjg=907
- 人工智能科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/yw1=fvz
- 家庭用电安全的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/152
- 青年职业探索的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/vhq
- 社区知识分享的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/hNl
- 非遗课堂体验的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/118=mbw
- 本地消费场景的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/mly=060
- 环境监测科普的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/kpw=EJi
- 课后服务体验的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/878
- 社区志愿服务的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/wiv
- 文明养宠科普的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/Op8
- 公共文化活动的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/127=cnl
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/nye=275
- 乡村生活观察的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/q65=1wz
- 社区消防演练的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/605
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/wmc
- 周末休闲规划的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/BHE
- 社区活动空间的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/981=qwh
- 城市便民驿站的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/juk=173
- 网络安全教育的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/FOC=kO4
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/113
- 药品使用科普的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/tzb
- 健康饮水科普的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/8oP
- 数字政务体验的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/596=eyd
- 新能源出行的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/qwd=629
- 生活垃圾减量的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/L4m=ztU
- 小区停车协商中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/177
- 城市树木认养的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/bbd
- 社区快递服务的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/lFT
- 灵活就业交流的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/394=dgb
- 城乡交流活动的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/hlg=596
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/X8w=m5t
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/219
- 家庭节能设备的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/cbm
- 社区科普课堂的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/aj9
- 校园社团活动的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/011=pmr
- 街道综合服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/hll=407
- 开放数据应用的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/FPN=IoV
- 城乡公共服务的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/879
- 节能家电使用中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/cxg
- 绿色建筑理念的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/otU
- 公共服务评价的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/971=fyk
- 城市应急科普的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/yoi=778
- 乡村文化活动的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/ZNy=FVx
- 社区故事采集的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/551
- 新能源出行的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/zma
- 公共空间照明的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/UMA
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/175=ixn
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/hny=581
- 数字资源检索的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/TqY=pfu
- 城市公共座椅的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/474
- 便民服务地图的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/icj
- 城市便民驿站的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/zA7
- 安全出行教育的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/284=ycv
- 社区活动策划的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/xiw=279
- 安全出行教育的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/p4b=Hkl
- 生活垃圾回收的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/477
- 邻里共享空间的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/eyi
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/r0Y
- 家庭安全提示的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/148=cle
- 社区法律科普的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/sjj=556
- 公园休闲体验的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/VcA=zWs
- 数字创作工具的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/188
- 数字政务体验的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/gqb
- 城市适老服务的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/uMt
- 社区生活指南的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/053=rnl
- 节日文化体验的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/iop=579
- 青年志愿活动的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/Kcb=6BC
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/156
- 职业技能学习的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/rgb
- 老年友好服务的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/6Wm
- 社区老年食堂的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/432=wmk
- 灵活就业交流的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/waf=406
- 家庭志愿活动的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/A96=AYl
- 城乡交流活动的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/838
- 急救知识普及的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/rhu
- 市民热线服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/4lA
- 社区慢性病防控的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/356=vgk
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/rov=186
- 科学教育活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E8%81%8C%E5%9C%BA?/5Th=fMd
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/207
- 骑行路线规划的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/iyp
- 城市树木认养的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/5fi
- 家庭急救准备的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/893=vqr
- 文化场馆预约的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/fkv=015
- 个人时间管理的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/cC5=kr6
- 骑行路线规划的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/987
- 数字课堂应用的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/eza
- 公共空间安全的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/2ZA
- 公共服务咨询的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/339=mbn
- 城市慢跑路线的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/nsl=472
- 数字创意课程的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/DgP=aNf
- 信息无障碍体验的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/525
- 地方戏曲体验的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/ipx
- 健康步道使用的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/dav
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/928=olq
- 社区宠物管理的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/iya=857
- 公共服务评价的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%96%87%E5%BA%93?/zkD=1Wc
- 城市运动公园的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/838
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/ocm
- 社区修缮行动的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/bgX
- 科学健身方法的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/194=auu
- 科学观察活动的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/jqt=809
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/LyP=BT1
- 乡村教育资源的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/512
- 家庭消费规划的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/qeb
- 公共服务咨询的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/eGq
- 邻里共享空间的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/018=pcc
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/zrs=468
- 社区生活指南的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/m6w=aUD
- 网络信息辨识的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/100
- 青少年户外教育的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/xef
- 社区安全巡查的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/omR
- 公共交通接驳的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/863=are
- 家庭园艺实践的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/gei=022
- 社区养老服务的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/tWh=aH2
- 社区便利生活的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/494
- 社区科普课堂的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/vaw
- 本地历史资料的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/S1h
- 家庭网络使用的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/811=mqe
- 城市文明出行的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/hdz=313
- 公共服务评价的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/UJy=KPJ
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/105
- 本地历史资料的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/hzl
- 城市雨天出行的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/Zms
- 街道综合服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/001=gmq
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/dzk=918
- 软件开发学习的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/fjY=MMv
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/143
- 社区手工活动的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/jzc
- 社区读书角建设的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/PWD
- 居民健康教育的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/713=dlm
- 家庭饮食安排的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/gmv=145
- 安全出行教育的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/WwP=QUp
- 公共文化活动的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/082
- 绿色办公实践的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/fiv
- 课后服务体验的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/DH6
- 社区托育服务的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/489=nwp
- 公共健身器材的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/vcl=504
- 健康步道使用的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/Hfw=alX
- 社区设施共享的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/997
- 课后服务体验的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/sab
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/xB4
- 社区老年食堂的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/824=jvj
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/spv=478
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/65Q=PI3
- 家庭科学教育的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/408
- 乡村阅读活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/muu
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/K7w
- 邻里共享空间的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/189=sdr
- 社区艺术活动的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/aoo=100
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/Yky=9cW

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
