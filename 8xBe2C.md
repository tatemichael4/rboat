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

- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/211
- 城市可持续生活的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/nla
- 老年人日常照护的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/TZQ
- 社区设施共享的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/776=dky
- 青年就业服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/mle=387
- 公共空间照明的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/0A0=3CM
- 本地消费场景的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/746
- 社区运动空间的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/gsb
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/4ct
- 公共图书馆服务的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/925=keg
- 青年志愿活动的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/bpr=749
- 城市微更新实践的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/UUM=hCI
- 社区便民服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/218
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/shg
- 社区交通安全的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/DTX
- 城市可持续生活的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/306=fmf
- 城市住房服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/rcs=547
- 居民健康教育的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A98VIII_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/qcJ=970
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/687
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/ony
- 家庭安全提示的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/jxf
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/282=pou
- 数字便民地图的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/yer=435
- 电子商务服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/fb5=Aw6
- 智能手机助老的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/068
- 乡村电商实践的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/fhl
- 社区应急准备的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/92E
- 老年智能设备的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/255=jce
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/wzy=677
- 社区交通安全的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/6If=sy8
- 智能手机助老的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/476
- 科学信息获取的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/okp
- 家庭理财科普的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/ERt
- 城市应急广播的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/198=blh
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/yhy=010
- 城市共享单车的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/LUw=9ca
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/255
- 城市共享单车的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/ley
- 科技馆参观体验的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/Nrh
- 儿童户外活动的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/190=iiq
- 网络信息辨识的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/qup=957
- 公共服务沟通的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/Hzo=x1i
- 非遗体验活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/649
- 个人数据管理的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/yam
- 健康步道使用的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/ynT
- 电子商务服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/192=olx
- 社区法律科普的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/cub=622
- 社区家校合作的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/jRz=Yfm
- 家庭收纳实践的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/292
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/rsh
- 公交站点体验的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/yS2
- 社区菜市场服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/056=yra
- 城市人文观察的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/fnr=404
- 农业科普体验的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/CnP=JSW
- 社区法律科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/443
- 家庭急救准备的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/mmt
- 健康饮水科普的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/hVm
- 个人时间管理的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/627=evb
- 绿色建筑理念的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/qmw=191
- 家庭运动计划的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/Mmv=uHA
- 通勤路线规划的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/317
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/cyl
- 公共服务数字化的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/ngE
- 急救知识普及的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/087=jrj
- 绿色办公实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/rop=165
- 本地历史资料的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_360%E4%B8%93%E9%A2%98?/Zfl=ExZ
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/219
- 家庭园艺实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/jem
- 低碳社区实践的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/cP9
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/080=lym
- 无障碍出行的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/dcs=002
- 开放式学习空间的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/RMo=t5b
- 生活服务数字化的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/902
- 数字创意课程的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/sez
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/QM2
- 公共空间照明的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/407=ati
- 地方文化传播的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/wvn=201
- 社区学习活动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/58c=vp2
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/126
- 社区交通安全的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/yzb
- 公共文化活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/eDk
- 城市空气科普的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/359=okl
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/lse=904
- 城市微更新实践的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/8qX=pke
- 社区教育资源的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/207
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/efl
- 儿童安全出行的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/AL2
- 开源技术交流的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/520=fae
- 电动汽车充电的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/pyt=312
- 生成式工具使用的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/7Et=H04
- 药品使用科普的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/243
- 社区学习活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/wox
- 便民信息查询的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/KwA
- 儿童友好空间的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/035=adw
- 应急物资管理的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/hpx=497
- 公共文化活动的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/WRM=A0B
- 社区交通安全的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/550
- 市民意见收集的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/pmf
- 医院导诊服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/cVZ
- 老年学习活动的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/899=mcc
- 应急物资管理的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/jth=888
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/nwi=1hv
- 社区家政服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/756
- 全民阅读推广中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/sng
- 乡村公共服务的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/uXG
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/074=eaf
- 邻里互助活动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/iys=707
- 智慧城市体验的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/zA0=h7l
- 气象科普传播的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/132
- 城市慢行系统的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/jxv
- 数字支付体验的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/5u6
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/032=qwd
- 老年学习活动的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/azr=733
- 家庭照护支持的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/L5M=ufl
- 本地消费场景的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/274
- 社区公共议事中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/nit
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/SpG
- 健康信息获取的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/233=odz
- 老年智能设备的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/ulp=385
- 公交站点体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/pjF=vkH
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/951
- 城市农夫市集的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/xnm
- 应急物资管理的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/DRO
- 个人数据管理的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/972=rfk
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/enn=921
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_360%E6%9B%B2%E8%89%BA?/mqb=GDe
- 线上阅读资源的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/615
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/mkt
- 街区更新实践的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/0ny
- 农村环境治理的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/130=sxi
- 环境教育课程的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/plw=351
- 家庭理财科普的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%AE%BF?/KW8=a3b
- 信息无障碍体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/174
- 老年人文化生活的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/cjm
- 校园阅读活动的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/Ypt
- 社区故事采集的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/709=kdy
- 家庭节能实践的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/xax=339
- 城市文明实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/UOG=Zfp
- 开放式学习空间的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/921
- 图书馆数字服务的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/wyo
- 健康步道使用的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/AMw
- 智能家居应用中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/345=pyf
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/zkz=814
- 机器人科普活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/GE0=lgz
- 职业技能学习的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/222
- 街区道路维护的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/ezd
- 乡村公共服务的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/GFq
- 乡村文化空间的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/626=wjq
- 城市应急科普的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/wtb=041
- 周末休闲规划的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/fm8=APB
- 基层服务创新的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/984
- 街区道路维护的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/txm
- 公共卫生设施的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/EY8
- 安全出行教育的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/902=jpd
- 农产品品牌传播的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/gel=283
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/BWw=egO
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/625
- 地方民俗记录的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/bjc
- 儿童阅读角的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/H1w
- 科学观察活动的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/982=emt
- 城市应急科普的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/sup=976
- 数字艺术创作的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/iHQ=dfl
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/868
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/jyq
- 数字阅读服务的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/8Rr
- 智能家居应用的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/080=rhz
- 老年人日常照护的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/gmg=200
- 日常摄影记录的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/afI=FFF
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/548
- 地方文化传播的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/rmu
- 社区便民服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/lfR
- 节气饮食文化的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/061=aoi
- 农产品品牌传播的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/jmq=251
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/7wW=YI8
- 个人信息保护的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/836
- 城市骑行环境的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/xbb
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/gfr
- 环境教育课程的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/466=ack
- 社区菜市场服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/ecg=812
- 城市便民驿站的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/Iul=oY9
- 城市公共空间的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/616
- 小区公共照明的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/ruz
- 生活技能分享的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/OzF
- 社区快递服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/242=wke
- 家庭园艺实践的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/dmp=563
- 食品配送体验的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/1G2=4J0
- 口袋公园建设的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/484
- 城市应急广播的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/tsh
- 老年学习活动的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/deC
- 街区小店体验的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/391=gnp
- 城市绿道建设的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/kun=486
- 无障碍出行的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/GY2=4Jd
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/862
- 乡村公共文化的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/pfz
- 节气饮食文化的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wgR
- 社区手工活动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/771=uim
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/svg=979
- 城市共享单车的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/SO5=Yuj
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/561
- 农贸市场环境的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/mkj
- 城市人文观察的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/8PQ
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/211=iba
- 公交站点体验的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/ycl=889
- 老年数字阅读中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/bXt=NaH
- 社区活动空间的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/640
- 文化场馆预约的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/hct
- 数字创作工具的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/UP5
- 学校体育活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/389=oke
- 城市慢行系统的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/tyf=527
- 小微企业服务的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/WUS=nES
- 家庭安全提示的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/358
- 数字艺术创作的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/vnh
- 社区公共议事的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/1VR
- 图书馆数字服务的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/299=sst
- 本地消费场景的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/aqk=300
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/eUd=ofs
- 城市便民驿站的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/309
- 社区家校合作的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/hnl
- 社区邻里服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/cSR
- 本地旅行体验的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/980=msv
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/tya=376
- 数字课堂应用的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/vME=Ywc
- 街区更新实践的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/921
- 地方美食文化中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/otn
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/rmC
- 社区协商议事的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/962=zir
- 公共服务指南的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/lxi=626
- 数字创作工具的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/sgl=a3p
- 城市生活服务的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/820
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/nmx
- 公共空间休憩的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/t0S
- 科学信息获取的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/001=nxg
- 公共交通接驳的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/kke=406
- 居家防滑改造的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/fDI=TGr
- 安全出行教育的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/387
- 环境教育课程的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/xks
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/iz1
- 科学运动指导的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/105=pum
- 社区防暑服务的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/afv=383
- 数字创意课程的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/yT5=LCc
- 城市展览体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/860
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/mzc
- 社区协商议事的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/HJZ
- 社区绿色空间的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/016=nvy
- 科技馆参观体验的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/pko=897
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/BoK=7F3
- 文明养宠科普的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/525
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/uqo
- 儿童友好街区的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/QoX
- 公共空间照明的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/383=lib

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
