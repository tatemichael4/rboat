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

- 社区家政服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/831
- 基层健康服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/bfp
- 学校体育活动的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/OGN
- 公交站点体验的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/804=srv
- 智慧停车服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/qbd=287
- 社区生活指南的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/tRZ=w0R
- 城市住房服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/879
- 安全出行教育的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/iwi
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/QIF
- 城市公共艺术的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/341=azv
- 社区安全巡查的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/jtw=462
- 社区便利生活的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/1jz=wxV
- 公共服务指南的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/758
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/lba
- 社区环保活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/MEM
- 城市文明出行的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/592=voh
- 乡村教育资源的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/vmx=706
- 创业经验分享的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/AgR=lks
- 公共文化活动的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/251
- 周末休闲规划的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/blb
- 亲子阅读活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/eBY
- 城市地名文化的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/741=boh
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/ard=292
- 城市生活记录的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/hiH=oNW
- 城市应急广播的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/141
- 城市空气科普的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/gyv
- 家庭照护支持的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/cxV
- 在线教育体验的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/465=rcz
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/vvu=876
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/pyA=87V
- 社区阅读服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/900
- 社区学习活动的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/ciz
- 公园休闲体验的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/xSY
- 公共文化活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/329=ost
- 亲子科普活动的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/pwf=998
- 远程协作工具的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/GhW=SlT
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/475
- 物业服务沟通的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/uif
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/kTC
- 居民健康教育的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/780=vrt
- 社区便民集市的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/dmw=371
- 开源技术交流的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/EfM=kHY
- 儿童友好空间的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/642
- 科技馆参观体验的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/gys
- 城市应急科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/V5Z
- 社区科普课堂的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/881=ktf
- 城市展览体验的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/juh=499
- 社区学习活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/421=iNk
- 家庭照护支持的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/701
- 地方民俗记录的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/lmr
- 数字生活课堂的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/wXd
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/269=ird
- 传统手工艺体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/pec=273
- 老旧小区改造的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/DAI=ETF
- 乡村电商实践中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/358
- 光伏知识科普的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/eof
- 居家防滑改造的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Zw6
- 公共卫生设施的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/631=fhy
- 公园亲子设施的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/hdu=546
- 社区便民服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/qmJ=imz
- 老年友好服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/119
- 科学运动指导的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/jul
- 公园无障碍服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/fXy
- 家庭志愿活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/787=ere
- 公共服务评价的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/ugw=884
- 乡村阅读活动的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/tsx=4LE
- 城市水环境观察的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/126
- 骑行路线规划的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/mke
- 社区科普课堂的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/y2y
- 社区活动策划的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/813=bqm
- 城市水环境观察的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/vag=683
- 农村环境治理的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/Fm5=1Pd
- 节能家电使用的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/955
- 社区养老服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/iii
- 个人时间管理中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/Frt
- 社区活动空间的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/903=lzd
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/gle=681
- 城乡交流活动的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/OwF=gnJ
- 农贸市场环境的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/288
- 城市可持续生活的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/amt
- 开放式学习空间的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/6KZ
- 智慧停车服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/833=yyv
- 基层服务创新的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/vmr=328
- 开源技术交流的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/tDr=sPg
- 骑行路线规划的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/228
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/loi
- 公共服务指南的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/Xp0
- 社区知识分享的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/010=nek
- 城市适老服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/syy=349
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%A7%A3%E5%AF%86?/ZJt=YDX
- 科技馆参观体验的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/703
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/faa
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/dQ1
- 电动汽车充电的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/523=keb
- 远程协作工具的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/nsj=498
- 城市步行友好的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/EyA=Fqh
- 本地消费场景的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/300
- 便民服务窗口的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/khr
- 地方旅游导览的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/wDN
- 绿色出行服务的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/302=fsh
- 健康信息获取的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/vle=227
- 小区公共照明的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/aRS=IV8
- 城市适老服务的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/350
- 灵活就业交流的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/fet
- 小区停车协商的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/Xga
- 农业科普体验的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/799=tnd
- 开放式学习空间的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/los=720
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/gN0=ipU
- 农业科普体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/646
- 读书会组织的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/irb
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/bL9
- 社区修缮行动的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/838=szf
- 城市博物馆服务的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/oqw=926
- 乡村电商实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/Dys=pUg
- 节日文化体验的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/669
- 街区更新实践的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/jci
- 数字资源检索的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/w75
- 低碳社区实践的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/257=prq
- 社区家政服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/obq=864
- 社区应急准备的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_360%E6%96%B0%E9%97%BB?/sks=hUu
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/259
- 城市公共自行车的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/ojn
- 小区公共照明的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/KHQ
- 校园阅读活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/184=aew
- 科技馆参观体验的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/dzq=734
- 家庭急救准备的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/GDh=gdQ
- 社区教育资源的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/720
- 社区活动空间的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/lzb
- 社区活动空间的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/C3X
- 家庭用电安全的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/495=hzl
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/xhl=885
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/xUe=aSz
- 物业服务沟通的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/127
- 城市社区治理的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/eeb
- 家庭消费规划的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/eHX
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/038=aau
- 城市公共饮水的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/rfb=379
- 街道综合服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/MMp=jeZ
- 校园社团活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/620
- 青年志愿活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/ntd
- 社区便民集市的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/vF8
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/666=lyj
- 便民服务窗口的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/zzu=927
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E7%9B%98%E7%82%B9?/S5y=lU0
- 个人信息保护的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/461
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/fwx
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/HQp
- 农村环境治理的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/296=low
- 旧物循环利用的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/lbe=336
- 街道综合服务的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/3ne=SUV
- 城市夜间生活的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/277
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/rin
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/lQE
- 街道综合服务的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/013=pib
- 志愿者培训交流的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/rgd=938
- 公共卫生宣传的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/p5C=jZ9
- 学校体育活动的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/379
- 公共服务评价的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/aex
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/S4y
- 科学观察活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/548=jug
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/ehu=735
- 乡村电商实践的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/sLG=1nL
- 学校食育活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/473
- 公共文化活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/yft
- 社区生活指南的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/DtG
- 读书会组织的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/954=lqn
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/fxx=368
- 乡村文化活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/iq2=EI3
- 城市游园体验的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/150
- 社区艺术活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/bpo
- 图书馆数字服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/MzW
- 线上办事服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/841=luk
- 数字生活课堂的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/lxs=668
- 传统节日科普的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8-%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/3ZX=N5y
- 节假日出行安排的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/799
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/hmv
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/0fk
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/060=pnn
- 数字创作工具的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/ilo=991
- 公共服务沟通的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/w4O=2qC
- 学校食育活动的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/009
- 社区停车服务的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/bba
- 便民维修服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/lcN
- 公共服务评价的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/362=cia
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/mbo=936
- 绿色校园实践的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/uB1=nOs
- 社会体育指导的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/803
- 读书会组织的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/whj
- 城市公共座椅的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/LZT
- 城市公共标识的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/857=nrx
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/hly=537
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/EDN=hNo
- 儿童友好空间的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/056
- 社区法律科普的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/oqa
- 社区花园共建的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/7KG
- 社区消防演练的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/988=wxs
- 亲子阅读活动的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/yob=502
- 电动汽车充电的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%8A%A0%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/6Rg=pFt
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/627
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/qqt
- 非遗体验活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/Pk5
- 职业技能学习的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/642=amm
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ysg=986
- 公共卫生设施的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/GSL=Ak8
- 网络信息辨识的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/891
- 社区养老服务的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/xdz
- 乡村教育资源的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/0HK
- 传统节日科普的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/002=veg
- 智能手机助老的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/viu=677
- 青少年科普实践的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/Kck=G83
- 职业技能学习的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/388
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/eji
- 城市噪声观察的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/afl
- 职业技能学习的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/486=xtm
- 家庭节能实践的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/ous=128
- 儿童友好街区的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88QQ%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/XMo=jUK
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/605
- 个人数据管理的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/cbk
- 城市社区治理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/1kS
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/137=lfz
- 儿童友好空间的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/wvj=055
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8AQQ_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/Yk3=MGT
- 社区互助网络的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/551
- 基层健康服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/wiw
- 城市空气科普的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/LNQ
- 社区协商议事的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/317=zzs
- 传统节日科普的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/laf=166
- 城市骑行环境的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/yDU=chc
- 城市公共饮水的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/268
- 日常摄影记录的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/bxo
- 城市步行环境的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/WqM
- 小微企业服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/136=nac
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/bcq=773
- 城市骑行环境的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/1Uy=GHV
- 开源技术交流的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/561
- 乡村公共阅读的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/une
- 老旧小区改造的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/XSs
- 青年职业探索的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/837=vkd
- 城市夜间照明的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/whp=466
- 就业技能培训的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/8Lt=Zdu
- 地方文化传播的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/186
- 城市应急科普的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/tjm
- 社区商业活力的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/Pu5
- 城市生活服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/915=osl
- 城市文明出行的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/zzt=220
- 无障碍出行的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%865000_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/5dt=IId
- 城乡交流活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/448
- 青少年科技社团的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/zgp
- 地方文化传播的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/Utk
- 社区儿童活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/362=mng

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
