# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 社区体育组织的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/287
- 药品使用科普的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/mtr
- 城市人文观察的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/fCn
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/529=jtv
- 应急物资管理的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/ncw=525
- 乡村公共服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%95%85%E6%B8%B8?/28K=FoF
- 青年志愿活动中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/254
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/pvt
- 乡村公共文化的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/csK
- 社区活动空间的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/743=pqg
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/wwa=533
- 城市公共饮水的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/0lq=tQ9
- 机器学习入门的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/925
- 社区托育服务的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/pup
- 社区便民服务的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/LJO
- 数字便民地图的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/848=sks
- 数据分析入门的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/riy=224
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E7%9F%A5%E4%B9%8E%E8%AE%B2%E5%9D%9B?/o4h=LzK
- 家庭用电安全的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/428
- 健康步道使用的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/ute
- 老年数字阅读的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/vU7
- 社区老年食堂的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/029=spz
- 青年职业探索的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/tdo=364
- 街头绿植养护的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/5hU=s50
- 家庭急救准备的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/596
- 儿童安全出行的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hht
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dEO
- 社区宠物管理的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/590=kur
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rob=632
- 城市农夫市集的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hhg=oUL
- 城市文化路线的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/188
- 科普展览体验的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/fpk
- 城市夜间照明的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/KXH
- 数字创作工具的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/176=nzw
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/zcj=786
- 地方美食文化的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%8E%BF%E5%9F%9F?/u99=4A7
- 社区公共卫生的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/350
- 绿色校园实践的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/qnf
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/ZOa
- 就业技能培训的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/671=zhw
- 街区更新实践的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/wul=153
- 城市绿色交通的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/LhY=Z2G
- 城市社区治理的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/287
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/acu
- 生活垃圾减量的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/tXB
- 租房信息服务的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/527=lhs
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/bpi=908
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%B4%B7?/Kj8=b8z
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/936
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/oao
- 社区健康讲座的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/UF2
- 儿童安全出行的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/722=syp
- 全民健身活动的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/dnz=725
- 街头绿植养护的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/nA5=Eu7
- 社区学习活动的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/558
- 居民健康教育的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/vkq
- 街区小店体验的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/J0Z
- 老年人文化生活的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/461=wxv
- 城市夜间生活的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/exz=572
- 数字便民地图的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/Gz8=brd
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/404
- 城市骑行环境的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/uge
- 社区托育服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/eMC
- 开放式学习空间的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/232=aet
- 公交站点体验的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/nxs=903
- 公共图书馆服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Vk7=TU7
- 乡村产业科普的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/681
- 公共空间安全的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/abs
- 数字生活课堂的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/TgN
- 公共空间照明的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/048=kfv
- 校园社团活动的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/wrr=631
- 居家防滑改造的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/6Hh=3te
- 老年友好服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/045
- 青少年编程学习的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/qsl
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/27F
- 数字档案服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/273=ovs
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/suv=812
- 地方文化传播的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/FBR=fXC
- 公共空间导览的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/429
- 城市慢行系统的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/ywn
- 文明养宠科普的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/QfO
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/546=tof
- 无障碍信息设计的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/aco=933
- 公共空间休憩的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/XiP=zhm
- 公共空间休憩的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/742
- 租房信息服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/nnn
- 终身学习资源的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/3Jb
- 青少年编程学习的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/947=qdo
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/yqu=762
- 社区慢性病防控的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/fWt=Lpy
- 网络安全教育的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/264
- 生活技能分享中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/twu
- 乡村产业科普的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/MvQ
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/218=onn
- 社区协商议事的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/sly=086
- 环境监测科普的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/3EC=J8n
- 小微企业服务的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/201
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/map
- 社区设施共享的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/UCI
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/248=jdl
- 数字生活课堂的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/udr=800
- 个人信息保护的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/45B=8Zr
- 绿色建筑理念的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/259
- 节能家电使用的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/grt
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/oOU
- 城市公共自行车的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/089=equ
- 社区学习活动的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/fxs=326
- 公共健身器材的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/CCj=oj8
- 公共空间休憩的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/863
- 青年志愿活动中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/iny
- 乡村生活观察的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/NPP
- 社区科普课堂的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/817=pxq
- 街区道路维护的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/qzu=731
- 网络安全教育的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/rfr=sRU
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/385
- 个人数据管理的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/xbh
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/om2
- 城市社区治理的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/969=fnc
- 智能家居应用的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/kae=903
- 家庭消费规划的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/QuV=cGK
- 开放式学习空间的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/395
- 校园节能行动的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/jnx
- 家庭教育交流的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/mQB
- 街道综合服务的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/683=rlh
- 数字生活课堂的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/saw=483
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/73o=vOh
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/749
- 基层健康档案的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/exm
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/Npq
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/345=gbo
- 青年志愿活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/lrm=006
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/Xmj=bRl
- 公共服务沟通的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/937
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/qrn
- 社区慢性病防控的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/yNq
- 城市基础设施的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/596=xkt
- 社区生活指南的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/lgb=342
- 生活垃圾回收的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/ty2=BLA
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/919
- 社区互助网络的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/yeh
- 公共文化活动中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/MRK
- 公共服务评价的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/817=ksa
- 城市应急科普的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/gey=661
- 城市雨天出行的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/uR2=4QQ
- 绿色消费选择的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/268
- 读书会组织的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/qno
- 乡村阅读活动的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/uUi
- 城市公共座椅的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/202=ybb
- 网络信息辨识的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/hvz=815
- 社区停车服务的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/EG8=KYX
- 社区养老服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/464
- 家庭环保习惯的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/nob
- 社区读书角建设的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/VYB
- 数据分析入门的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/254=uck
- 城市骑行环境的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/kpi=788
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/uk1=vYj
- 食品安全科普的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/030
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/bhr
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/wPo
- 青年就业服务的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/139=fss
- 公益活动组织的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/ryb=892
- 旧物循环利用的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/oTT=Oyo
- 街区绿化养护的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/186
- 社区运动空间的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/voh
- 城乡交通衔接的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/Ehf
- 社区环保活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/386=nrr
- 公共场馆服务的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/ody=872
- 绿色出行服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/SGN=S47
- 节日文化体验的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/292
- 城市雨天出行的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/nyf
- 城市文化路线的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/2C7
- 城市运动公园的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/449=urb
- 社区科普课堂的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/jmt=551
- 生活服务数字化的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/0fQ=OdM
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/260
- 家庭饮食安排的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/zgc
- 绿色办公实践的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/9Gq
- 农村环境治理的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/611=xor
- 社区协商议事的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/npq=808
- 生活技能分享的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/exi=2SS
- 安全出行教育的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/026
- 社区教育资源的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/isz
- 家庭用电安全的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/91C
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/572=bnm
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/bzm=274
- 新能源知识普及的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/Dgv=gr9
- 社区健康讲座的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/246
- 儿童友好空间的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ctw
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Cqs
- 社区托育服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/860=ntl
- 健康信息获取的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/oeg=922
- 亲子科普活动的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/IPN=HC6
- 城市文明出行的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/912
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/zpd
- 青年志愿活动的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/Lup
- 社区绿色空间的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/821=xks
- 社区活动策划的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/zei=298
- 公共服务数字化的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/Ysk=FIt
- 地方旅游导览的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/954
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/fhv
- 健康步道使用的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/6re
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/175=xol
- 公交站点体验的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/lib=889
- 城乡交流活动的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/tAj=F0D
- 社区养老服务的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/918
- 街区更新实践的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/smi
- 骑行路线规划的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/YyT
- 口袋公园建设的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/986=qgt
- 社区体育组织的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vop=258
- 社区运动空间的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/B43=f0y
- 骑行路线规划的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/709
- 数字创作工具的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/oht
- 老年学习活动的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/wki
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/531=iag
- 乡村文化活动的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/nfw=266
- 青少年户外教育的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_61%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/brh=aNs
- 乡村文化空间的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/442
- 网络信息辨识的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/scy
- 老年人日常照护的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/e4Z
- 运动安全知识的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/341=aff
- 家庭养老规划的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/epf=997
- 公园休闲体验的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_61%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/Pxr=Iqh
- 社区阅读服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/864
- 社区阅读服务的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/tif
- 邻里互助活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/FvB
- 公园休闲体验的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/612=cbo
- 老年友好服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/bnb=807
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_666www-%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/HD6=n3o
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/616
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/eie
- 休闲运动入门的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/6DX
- 机器学习入门的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/793=vrj
- 家庭养老规划的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/fij=951
- 数字档案服务的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8666%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/iFn=MMt
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/730
- 科学信息获取的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/pvm
- 地方民俗记录的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/Nfa
- 节约用水实践的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/339=jog
- 公共服务预约的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/nwr=132
- 公共交通接驳的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8666vip%E5%AE%98%E7%BD%91%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/bd9=pm4
- 城市便民驿站的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/319
- 无障碍出行的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/bqb
- 数字创作工具的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/QQC
- 社区健康讲座的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/919=gtk
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/iro=946
- 社区文化节活动的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_665%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/Zlx=KSK
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/857
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/gik
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/JTd
- 小区电梯维护的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/304=hpo

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
