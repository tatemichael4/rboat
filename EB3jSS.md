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

- 乡村生活观察的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/EdQ
- 城市文明出行的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/267=jqk
- 家庭运动计划的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/iiq=668
- 社区健康讲座中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/w4O=hsO
- 城乡交流活动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/633
- 数字创意课程的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/dnr
- 个人信息保护的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/az9
- 地方旅游导览的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/932=dzw
- 网络信息辨识的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/rqe=792
- 城市夜间照明的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_360%E6%B1%87%E5%B8%82?/66t=OZw
- 基层健康服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/582
- 光伏知识科普的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/mhd
- 社区停车服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/vll
- 公共文化活动的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/970=lal
- 社区便利生活的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/nww=014
- 公共文化活动的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/uki=ezd
- 节能家电使用的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/749
- 城市骑行环境的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/occ
- 老年学习活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/3xl
- 校园节能行动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/885=pwx
- 网络信息辨识的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/ksq=798
- 城市公共厕所中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/qwd=HvB
- 城市生活记录的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/607
- 城市农夫市集的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/acu
- 传统手工艺体验的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/RfN
- 城市公共标识的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/772=uev
- 周末休闲规划的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/xnk=347
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/yGv=5IR
- 城市应急科普的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/562
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/beb
- 物业服务沟通中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/zDL
- 人工智能科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/629=gat
- 通勤路线规划的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/cso=321
- 在线学习体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/EQR=1fk
- 应急物资管理的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/475
- 公共场所导视的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/xli
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/luj
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/614=osz
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/cmy=810
- 社区公共卫生的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/6ix=SwM
- 公共图书馆服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/563
- 社区法律科普的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/obr
- 社区便利生活的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/Pgo
- 消防知识宣传中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/668=uoi
- 数字素养提升的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/mbr=884
- 老年智能设备的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/Hd1=zRB
- 城市雨天出行的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/400
- 家庭用电安全的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/qfq
- 城市人文观察的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/Qcw
- 节气饮食文化的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/229=wgz
- 公共文化活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/kdb=756
- 城乡公共服务的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/BP6=yBy
- 家庭养老规划的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/704
- 城市文明出行的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/ydo
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/XVP
- 数字课堂应用的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/920=mdn
- 城市慢行系统的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/cxj=275
- 城市文明出行的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/ck7=hDM
- 社区阅读服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/269
- 城市便民驿站的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/fsa
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/m1V
- 本地历史资料的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/802=zau
- 智慧停车服务的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/nhs=532
- 骑行路线规划的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/fu4=IGF
- 公交站点体验的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/210
- 地方民俗记录的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/krw
- 家庭网络使用的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/SF1
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/316=vod
- 绿色校园实践的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/gdr=043
- 城乡公共服务的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/CjJ=Z9s
- 环境监测科普的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/965
- 数字便民地图的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/wng
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/36X
- 线上阅读资源的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/546=yxe
- 青少年科普实践的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/cvf=357
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/voO=5Oo
- 社区休闲设施的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/426
- 科学运动指导的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/tyd
- 乡村生态旅游的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/Twx
- 社区信息发布的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/303=ujx
- 绿色生活实践的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/yyh=278
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/rrE=lWo
- 节约用水实践的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/878
- 城市夜间生活的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/qmn
- 个人时间管理的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/lKW
- 开源技术交流的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/107=gxq
- 公共空间安全的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/oio=853
- 科学信息获取的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/N6u=hTS
- 城市公共厕所的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/857
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/uld
- 青年就业服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/JqV
- 亲子科普活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/479=esy
- 青少年编程学习的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/wic=290
- 便民服务地图的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/uZs=ypO
- 食品安全科普的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/107
- 公共健身器材的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/kae
- 公共空间休憩的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/4Ys
- 便民维修服务的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/190=pob
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/ccm=559
- 街道综合服务的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/ag4=ij7
- 社区儿童活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/571
- 日常摄影记录的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/nsz
- 城市体育设施的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/iDp
- 全民阅读推广的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/227=yli
- 城市慢行系统的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/jvf=946
- 居家适老化改造的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/sKT=EL5
- 科普展览体验的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/289
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/vlg
- 城市慢跑路线的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/cSZ
- 社区艺术活动的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/895=ncg
- 数据分析入门的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/wvs=684
- 青年就业服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/7AX=f18
- 社区养老服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/554
- 小区电梯维护的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/nih
- 邻里互助活动的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/zc5
- 社区艺术活动的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/095=bou
- 街头绿植养护的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/zvk=896
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/pa6=07f
- 社区托育服务的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/367
- 老旧小区改造的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/rap
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/OOq
- 志愿者培训交流的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/539=ktu
- 市民意见收集的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/fwg=238
- 创业经验分享的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/lUN=Rby
- 家庭环保习惯的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/352
- 社区庭院绿化的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/nhv
- 社区庭院绿化的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/bpc
- 图书借阅体验的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/204=huu
- 城市游园体验的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/wbn=811
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%AE%89%E9%98%B2?/b01=PPz
- 居家防滑改造的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/131
- 图书馆数字服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/nip
- 健康信息获取的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/djQ
- 城市便民驿站的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/879=tmz
- 健康步道使用的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/tei=116
- 城市社区治理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/oGS=xsp
- 社区运动空间中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/175
- 社区故事采集的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/yij
- 课后服务体验的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/e0M
- 文化讲座服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/901=iqm
- 社区商业活力的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/ypv=877
- 乡村生活观察的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/m2P=axw
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/710
- 网络信息辨识的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/tky
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/mTZ
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/622=skh
- 城市公共厕所的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/qxl=675
- 社区菜市场服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/PdJ=ClI
- 户外活动组织的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/213
- 生活技能分享的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/wdt
- 生活服务数字化的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/Gls
- 学校体育活动的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/704=rdy
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/pzy=243
- 地方美食文化的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/Jf6=VkK
- 社区消防演练的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/582
- 城市树木认养的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/mfn
- 社区便民集市的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/q3Z
- 社区活动空间的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/269=shc
- 家庭阅读计划的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/qbm=003
- 数字资源检索的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/qNU=TjR
- 图书馆数字服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/799
- 便民维修服务的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/udc
- 校园社团活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/Wfz
- 职业技能学习的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/152=wrz
- 节能家电使用的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/bxj=245
- 小区停车协商的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/cTy=JJt
- 数字政务体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/906
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/som
- 家庭志愿活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/nFb
- 职业技能学习的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/836=qie
- 社区心理支持的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/hlk=965
- 老年运动活动的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/QT6=H3D
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/257
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/rfx
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/UoD
- 科学信息获取的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/829=tzw
- 环境监测科普的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/eck=231
- 就业技能培训的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/f3e=ZEC
- 城市夜间生活的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/900
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/mou
- 居民健康教育的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/dkq
- 儿童友好空间的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/560=mtj
- 城市运动公园的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/iyp=740
- 城市夜间照明的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B6%85%E7%BA%A7%E9%A3%9E%E8%89%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/xbo=tYQ
- 数字阅读服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/174
- 农贸市场环境的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/udh
- 农产品消费体验的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/ybN
- 城市公共艺术的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/315=pfa
- 开源技术交流的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/tkh=637
- 城市空气科普的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E5%A6%86?/WgV=sgv
- 网络安全教育的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/203
- 城市空气科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/bmg
- 儿童阅读角的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/yw7
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/458=mfv
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/bgu=683
- 家庭网络使用的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/o8U=ayM
- 城市空气科普的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/586
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/hwh
- 口袋公园建设的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/FKY
- 街区更新实践的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/840=wxn
- 家庭用电安全的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/zrt=600
- 公园亲子设施的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/vpD=gGL
- 社区修缮行动的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/195
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/hpu
- 社区花园共建的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/ctx
- 公共交通接驳的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/474=qqb
- 街区绿化养护的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/hmw=194
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/Q22=sNG
- 公共设施使用的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/507
- 城市公共标识的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/bds
- 街区小店体验的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/IOw
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/690=leu
- 消防知识宣传的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/uzl=487
- 城市夜间生活中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/cel=FBQ
- 文化场馆预约的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/480
- 数字档案服务的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/cfs
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/LDC
- 便民服务窗口的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/869=fvn
- 社区儿童活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/tru=972
- 公交站点体验的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/KQ9=Map
- 远程协作工具的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/305
- 社区防暑服务的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/eoz
- 环境教育课程的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/Y8D
- 社区老年食堂的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/084=mtx
- 街道综合服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/sxz=682
- 城市树木认养的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/cL7=xUB
- 城市树木认养的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/960
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/del
- 城市体育设施的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/PZA
- 亲子阅读活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/300=ptf
- 基层健康服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/rzx=496
- 地方民俗记录的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/1ih=SlE
- 城市可持续生活的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/396
- 校园社团活动的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/fkc
- 开放式学习空间的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/OfR
- 数字便民地图的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/032=gaa
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/zmu=311
- 家庭急救准备的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%A8%B1%E4%B9%90%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/5O3=jvW
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/168
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/aam
- 家庭用电安全的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/kpy
- 青少年编程学习的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/619=rwy
- 城市空气科普的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/xit=509
- 社区文化节活动的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%878%E7%A0%81%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/YMM=mCk
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/123
- 公共空间休憩的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/sqw
- 社区设施共享的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/95w
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/005=pgn
- 家庭收纳实践的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/nha=329
- 乡村生态旅游的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/4nv=ADQ

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
