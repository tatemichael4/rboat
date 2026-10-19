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

- 社区设施共享的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/V30
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/852=hph
- 居民健康教育的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/qjh=719
- 校园社团活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/G9r=dAj
- 远程协作工具的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/378
- 休闲运动入门的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/lva
- 邻里互助活动的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/dxg
- 光伏知识科普的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/289=tjp
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/xgs=459
- 个人信息保护的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/MZN=ckL
- 社区公共餐饮的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/696
- 开放式学习空间的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/fkr
- 基层服务创新的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/zuB
- 校园阅读活动的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/749=nhj
- 社区体育组织的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/rqo=061
- 青年职业探索中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/ep1=VsB
- 绿色校园实践的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/246
- 城市展览体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/xfw
- 城市住房服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/AQp
- 校园社团活动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/141=gft
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/bup=612
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/bRD=Xti
- 城市适老服务的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/084
- 社区公共议事的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/ebf
- 城市农夫市集的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/Tia
- 数字便民地图的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/349=gcr
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/ync=570
- 家庭健康科普的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/2MM=R7G
- 数字支付体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/067
- 城市便民驿站中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/gje
- 公共图书馆服务的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/R9W
- 节气饮食文化的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/799=bzv
- 社区公共卫生的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/mcs=492
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_500%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/MNm=cWu
- 节能家电使用的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/619
- 城市休闲步道的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/zlv
- 社区故事采集的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/uaF
- 乡村文化空间的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/834=hvk
- 休闲运动入门的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/bfu=918
- 食品配送体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/oJP=KYh
- 城市地名文化的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/715
- 城市雨天出行的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/tld
- 市民意见收集的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/gN6
- 社区志愿服务的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/663=rsi
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/leh=820
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/mO2=Szc
- 数字艺术创作中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/225
- 科学观察活动的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/cvd
- 租房信息服务的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/q7B
- 运动安全知识的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/382=dna
- 社区消防演练的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/jgo=877
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/IYL=ic9
- 社区文化节活动的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/103
- 休闲运动入门的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/pbt
- 数据分析入门的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/9Z4
- 社区读书角建设的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/030=wlx
- 物业服务沟通的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/rwf=571
- 社会体育指导的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/cnw=Nbc
- 儿童运动体验的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/224
- 公共设施维护的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/srb
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/afn
- 网络信息辨识的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/639=pdt
- 社区防暑服务的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/knx=907
- 社区消防演练的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/j4J=rVG
- 环境教育课程的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/128
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/ijw
- 家庭教育交流的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/sIc
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/119=sag
- 城市博物馆服务的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/gke=267
- 社区公共卫生的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/Ity=eGE
- 数字创意课程的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/624
- 电子商务服务的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/lve
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/6B1
- 数字创意课程中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/554=dgm
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/jkf=438
- 街头绿植养护的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/W0D=s68
- 数字设备回收的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/234
- 老年学习活动的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/ila
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/1ou
- 社区设施共享的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/922=nwy
- 开源技术交流的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/srt=206
- 城市农夫市集的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%9D%E9%99%A9?/U0T=nae
- 公益活动组织的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/736
- 乡村阅读空间的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/dkm
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/75d
- 城市骑行环境的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/863=yiq
- 全民健身活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/tsy=121
- 城乡交流活动的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/hxl=ngr
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/622
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/rup
- 城市基础设施的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/EYG
- 小区公共照明的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/728=zjq
- 城市慢跑路线的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/piq=089
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/N94=2Gw
- 城乡交流活动的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/459
- 节约用水实践的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/rtn
- 城市博物馆服务的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/I3H
- 文化讲座服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/589=vwt
- 城市建设科普的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/wki=514
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/NDb=nUL
- 社区儿童活动的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/239
- 地方旅游导览中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pqw
- 乡村公共服务的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mI8
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/754=ifz
- 社区共享书架的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ssg=575
- 乡村文化活动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Fio=KJL
- 急救知识普及的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/764
- 城市噪声观察的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/kll
- 青少年户外教育的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/3Pd
- 无障碍信息设计的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/624=lnz
- 社区慢性病防控的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/vmd=081
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/qNW=ecS
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/872
- 公共设施维护的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/naq
- 校园社团活动的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/QXq
- 环境监测科普的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/386=ydc
- 本地历史资料的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/ycl=256
- 公共服务咨询的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/1LL=ras
- 食品配送体验的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/387
- 街头绿植养护的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/kig
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/oNO
- 社区公共议事的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/482=nbm
- 智慧城市体验的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/gzi=919
- 地方旅游导览的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/Cwx=qiq
- 数字支付体验的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/302
- 通勤路线规划的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/cgu
- 社区消防演练的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/XTy
- 科学信息获取的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/624=ium
- 家庭安全提示的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/yyp=518
- 社区阅读服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/Rdm=1et
- 运动安全知识的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/273
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/zsh
- 社区便民服务的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/EYO
- 家庭环保习惯的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/483=oxk
- 校园节能行动的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/zar=943
- 乡村文化空间的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/T49=BfE
- 智慧停车服务的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/690
- 城市绿色交通中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/flm
- 数字公共文化的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/NLS
- 乡村公共服务的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/532=agk
- 社区手工活动的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/lwk=953
- 终身学习资源的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/rgt=Qik
- 社区法律科普的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/707
- 数字艺术创作的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/vzy
- 社区信息发布的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/xtZ
- 社区停车服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/017=svc
- 社区菜市场服务的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/hew=565
- 家庭运动计划的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/vlo=Kw6
- 创业经验分享的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/962
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/hbh
- 市民热线服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/zRg
- 绿色校园实践的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/821=ukq
- 乡村公共文化的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/tsy=964
- 网络安全教育的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/FvZ=XnJ
- 城市公共空间的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/954
- 老年人日常照护的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/mol
- 公共服务沟通的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/MDI
- 医院导诊服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/336=ibl
- 城市绿色交通的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/fwd=829
- 亲子科普活动的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/qb0=TPD
- 健康饮水科普的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/621
- 城乡交流活动的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/tzx
- 本地消费场景的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/3PA
- 公共设施使用的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/828=dpm
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/gnu=776
- 科普展览体验的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/DE1=Trb
- 全民健身活动的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/625
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/ags
- 便民维修服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/N9S
- 全民阅读推广的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/407=lpu
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/mch=478
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/s78=Wpg
- 节能家电使用的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/662
- 农村环境治理的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/yqw
- 社区阅读服务的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/Rja
- 小区电梯维护的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/297=ghz
- 科学教育活动的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/cjh=832
- 公共空间安全的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/teU=4tp
- 城市树木认养的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/699
- 绿色校园实践的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/hkt
- 乡村教育资源的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/Ofi
- 节能生活方式的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/271=ngc
- 基层健康档案的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/lbb=350
- 城市运动公园的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/8Mg=FK7
- 数字档案服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/019
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/yqd
- 灵活就业交流的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/Bik
- 公共空间休憩的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/062=duh
- 线上办事服务的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/kpd=827
- 社区快递服务的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/jSa=OKa
- 本地消费场景的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/557
- 数字支付体验的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/ckf
- 城市地名文化的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/i8F
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/368=jfw
- 社区活动空间的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/occ=960
- 休闲运动入门的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/V3Z=riY
- 急救知识普及的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/607
- 社区修缮行动的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/lng
- 青少年心理健康的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/cjU
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/034=djm
- 城市共享单车的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/vrx=375
- 公园亲子设施的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/Ex1=Tfv
- 智能家居应用的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/162
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/dsb
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/UQA
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/054=bea
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/lcx=536
- 儿童安全出行的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/1ua=OzW
- 社区协商议事的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/501
- 社区文化节活动的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/zjz
- 儿童阅读角的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/IZy
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/285=tcb
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/cyj=072
- 老年人出行服务的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/YHh=pBg
- 社区交通安全的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/662
- 城市博物馆服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/hsj
- 社区便利生活的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/Cxi
- 个人数据管理的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/698=kjn
- 绿色快递包装的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/jep=404
- 城市生活服务的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/Fvh=SHk
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/355
- 科学观察活动的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/kzo
- 志愿者培训交流的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/Kfj
- 社区设施共享的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/511=jbo
- 社区手工活动的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/lox=945
- 基层服务创新的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/Tf0=Yac
- 农业科普体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/273
- 地方戏曲体验的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/ofb
- 社区家校合作的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/YWL
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/820=onv
- 城市文明出行中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/fjc=499
- 城市应急广播的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/L5F=bJi
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/791
- 小区停车协商的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/mai
- 老年学习活动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/r4q
- 气象科普传播的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/555=tco
- 儿童运动体验的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/xov=476
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/UvS=ozf
- 终身学习资源的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/197
- 社区家校合作的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/vgp
- 家庭照护支持的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/CYk
- 亲子阅读活动的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/969=euk
- 文明养宠科普的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/gma=936
- 青年志愿活动的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/NPW=lI4
- 城市应急科普的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/488
- 社区便民服务的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/gxn
- 基层医疗预约的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/Hb4
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/697=xec
- 社区科普课堂中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/ppj=598
- 公园休闲体验的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/cqv=xyW

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
