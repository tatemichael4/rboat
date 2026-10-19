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

- 城市雨天出行的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/sBu
- 家庭安全提示的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/213=xgh
- 消防知识宣传的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/yvp=756
- 本地旅行体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/Puc=BXb
- 社区体育组织的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/300
- 青少年编程学习的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/pea
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/q3i
- 无障碍出行的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/997=ntc
- 骑行路线规划的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/ido=273
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/idR=O7h
- 城乡公共服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/885
- 城市共享单车的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/wty
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/6qw
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/632=xsa
- 人工智能科普的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/otp=059
- 数字档案服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84%E5%BE%AE%E4%BF%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/97K=atT
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/992
- 智慧城市体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/gvn
- 地方旅游导览的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/yh1
- 邻里共享空间的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/854=wxx
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/jys=418
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/9fU=WJY
- 应急物资管理的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/145
- 乡村文化活动的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/bwp
- 社区公共卫生的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/cmk
- 生活垃圾回收的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/952=isy
- 乡村生活观察的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/oop=273
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92QQ_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/rdN=gG2
- 城市步行友好的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/850
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/oal
- 城乡公共服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/L9i
- 儿童友好空间的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/937=zus
- 社区便民服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/pom=986
- 旧物循环利用的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/oXa=cIn
- 公共服务数字化的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/942
- 绿色快递包装的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/lec
- 社区设施共享中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/4F9
- 城市慢行系统的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/350=zvv
- 社区交通安全的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/rcy=766
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/Ej1=B67
- 急救知识普及的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/372
- 健康信息获取的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/nxw
- 城市体育设施的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/SwP
- 绿色办公实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/399=ccr
- 软件开发学习的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/tem=411
- 乡村公共文化中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/VkB=lWz
- 社区学习活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/152
- 文明养宠科普的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/mhy
- 社区共享书架的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/qJ6
- 人工智能科普的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/994=zvv
- 社区老年食堂的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/ori=462
- 社区便民服务的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/E3T=rLL
- 休闲运动入门的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/129
- 本地消费场景的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/lee
- 社区防暑服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/3sf
- 小微企业服务的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/200=hfc
- 青少年户外教育的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/qqh=999
- 新能源出行从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/5G7=tYU
- 城市绿色交通的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/753
- 数字生活课堂的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/lhz
- 数字资源检索的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/MJs
- 地方民俗记录的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/724=qbe
- 城市公共标识的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/jgc=993
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/DRY=igb
- 城市公共标识的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/546
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/rjr
- 新能源出行的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/D6M
- 健康步道使用的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/663=lyq
- 街区更新实践的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/fbg=942
- 社区活动空间的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/RYE=xz9
- 科学教育活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/902
- 街区更新实践的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/xbm
- 城市便民驿站的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/YAB
- 社区家校合作的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/679=kzx
- 青少年科技社团的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/xey=898
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/vRS=NPB
- 非遗课堂体验的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/994
- 社区设施共享的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/joh
- 网络信息辨识的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/5QE
- 科技馆参观体验的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/948=nht
- 家庭急救准备的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/pee=466
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/X3S=B3z
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/034
- 周末休闲规划的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/wwa
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/RdX
- 地方文化传播的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/300=ish
- 家庭消费规划的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/apb=598
- 绿色校园实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/tLd=iMl
- 社区宠物管理的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/759
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/tkl
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/koL
- 社区健康讲座的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/055=rtj
- 社区修缮行动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/pie=498
- 老年数字阅读的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/9Hr=MF4
- 旧物循环利用的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/752
- 基层健康档案的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/rzq
- 户外活动组织的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/nBB
- 儿童安全出行的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/006=ynl
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/lqg=447
- 社区垃圾回收的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/MVC=TP8
- 城市夜间照明的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/452
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/rpv
- 公共卫生设施的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/qJe
- 城市便民驿站的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/576=eeo
- 城市绿道建设的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/fdt=929
- 垃圾分类指导的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/v8l=i2E
- 数字支付体验的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/253
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/qwo
- 便民维修服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/xdC
- 公共服务预约的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/088=ejs
- 远程协作工具的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/olz=022
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/thE=RJA
- 社区绿色空间的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/176
- 家庭消费规划的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/glp
- 城市住房服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/hcZ
- 社区快递服务的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/236=ofq
- 社区故事采集的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/kja=463
- 社区文化传播的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/M38=kfE
- 社区邻里服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/438
- 公共场所导视的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/rct
- 药品使用科普的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/5oR
- 城市骑行环境的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/811=nfh
- 社区慢性病防控的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/znk=151
- 周末休闲规划的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_360%E5%9B%BE%E9%89%B4?/IEM=XmP
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/478
- 课后服务体验的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/klg
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/Ro5
- 文明养宠科普的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/623=bap
- 家庭环保行动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/rju=903
- 青年职业探索的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/ltC=p0o
- 街区小店体验中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/026
- 城市公共标识的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/vjt
- 科学观察活动的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/aQU
- 文明养宠科普的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/976=dgk
- 新能源知识普及的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/nrj=652
- 网络信息辨识的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/LJx=PEQ
- 小区公共照明的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/986
- 社区便民集市的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/qun
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/Ol7
- 老年智能设备的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/384=gxu
- 乡村公共文化的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/mie=494
- 非遗体验活动的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/DHC=djP
- 社区心理支持的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/790
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/bym
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/sGs
- 社区应急准备的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/694=ocu
- 消防知识宣传中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/hcx=836
- 城市共享单车的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/Bq9=kta
- 青少年户外教育的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/518
- 城市共享单车的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/gpo
- 科普展览体验的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/xUw
- 邻里共享空间的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/385=vwk
- 电子商务服务的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/fku=220
- 地方旅游导览的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E8%AE%BA?/ig8=PY3
- 物业服务沟通的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/437
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/kdg
- 学校体育活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/vec
- 物业服务沟通中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/803=mpj
- 物业服务沟通的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/bjw=109
- 社区便利生活的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/Q9j=6wH
- 便民服务地图的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/687
- 节能生活方式的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/euh
- 生活服务数字化的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/MgH
- 小区公共照明的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/683=idq
- 基层服务创新的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/vzw=099
- 医院导诊服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/2by=ARt
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/886
- 儿童友好空间的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/odp
- 城市展览体验的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/xVm
- 应急物资管理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/900=dty
- 社区文化节活动的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/ods=474
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/5Zx=Val
- 城市社区治理的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/557
- 家庭饮食安排的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/lta
- 消防知识宣传的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/kNr
- 城市噪声观察的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/325=rsq
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/pln=701
- 老年友好服务的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/Bid=tbj
- 公共图书馆服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/631
- 低碳社区实践中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/ixg
- 社区知识分享的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/xX7
- 城市空气科普的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/719=ybx
- 公共卫生宣传的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/rrl=671
- 社区共享书架的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/YSh=gW9
- 社区活动报名的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/534
- 社区应急准备的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/owa
- 网络信息辨识的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/q1a
- 城市生活服务的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/079=egc
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/iwm=772
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/36O=hQE
- 家庭饮食安排的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/715
- 数字便民地图的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/dea
- 学校体育活动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/74c
- 节约用水实践的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/489=bgu
- 邻里互助活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/ucl=902
- 社区心理支持的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/fyN=LGU
- 智慧城市体验的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/530
- 节假日出行安排的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/miu
- 学校食育活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/BBu
- 文明养宠科普的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/059=xag
- 家庭照护支持的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kwp=481
- 农产品消费体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dfL=JTQ
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/139
- 市民意见收集的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/osw
- 绿色消费选择的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/OzK
- 环境教育课程的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/917=iop
- 智慧城市体验的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/bst=362
- 城市微更新实践的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/3pd=5ME
- 家庭网络使用的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/105
- 无障碍信息设计的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/xxo
- 气象科普传播的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/13Q
- 城市博物馆活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/920=jqy
- 社区健康讲座的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/wpk=593
- 就业技能培训的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/MlI=trr
- 居家防滑改造的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/257
- 城市文明出行的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xqg
- 健康信息获取的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gCw
- 机器人科普活动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/589=zea
- 家庭防灾准备的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xyn=685
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/5tR=Uhp
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/426
- 公共图书馆服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/ron
- 家庭网络使用的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/W0f
- 节能家电使用的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/228=whc
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/ykr=305
- 青年志愿活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/aEA=m7a
- 社区故事采集的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/601
- 青少年科普实践的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/xxg
- 乡村生态旅游的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/ISO
- 地方戏曲体验的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/957=yjf
- 城市文明出行中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/uxo=700
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/UeO=y8g
- 城市共享单车的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/552
- 老年智能设备的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/hhk
- 社区活动报名中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/6V9
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/573=mgg
- 城市展览体验的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/hjx=179
- 社区志愿服务的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/q5c=WkY
- 公共服务咨询的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/255
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/esf
- 家庭运动计划的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/Qcd
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/739=mov
- 安全出行教育的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/ajk=841
- 绿色办公实践的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/I4l=PL7
- 社区应急准备的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/392
- 科学健身方法的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/kul
- 物业服务沟通的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/nKy
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/002=dcc
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/asz=672
- 老年人出行服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/qBo=4Hh

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
