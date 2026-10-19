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

- 居民健康教育的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/032
- 城市文化路线的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/gvv
- 老旧小区改造的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/xFC
- 公园休闲体验的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/065=miv
- 城市空气科普的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/miz=792
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/RGd=G6V
- 城市博物馆服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/255
- 食品配送体验的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/hpf
- 社区设施共享的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/kU2
- 日常摄影记录的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/640=srl
- 城市绿道建设的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/jej=995
- 城市社区治理的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/Hu0=5A0
- 社区共享书架的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/589
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/waf
- 非遗体验活动的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/lBL
- 社区便民服务的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/622=gdc
- 社区设施共享的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/sdw=641
- 老年数字阅读的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/X0b=d19
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/828
- 城市公共自行车的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/bia
- 传统节日科普的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/Zah
- 无障碍出行的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/775=abw
- 社区科普课堂的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/cdp=506
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/gur=gEc
- 社区便民集市的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/466
- 家庭教育交流的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/bfy
- 儿童友好街区的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/iuO
- 老年友好服务的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/545=pck
- 骑行路线规划的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/glq=954
- 在线学习体验的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/sNu=NSJ
- 家庭教育交流的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/989
- 家庭照护支持的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/tke
- 智能家居应用的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/v3L
- 食品安全科普的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/133=ype
- 社区设施共享的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/fzx=912
- 便民维修服务的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/tAA=pqB
- 低碳社区实践中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/858
- 人工智能科普的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/jha
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/m0V
- 食品安全科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/318=llq
- 家庭网络使用的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/wiv=219
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/Ooi=7p6
- 社区协商议事的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/928
- 健康饮水科普的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/qcj
- 智慧停车服务的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/23s
- 城市社区治理的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/843=bnh
- 社区便利生活的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/sle=322
- 市民意见收集的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/35S=l1M
- 基层服务创新的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/111
- 公共服务预约的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/pbv
- 社区宠物管理的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/9Pi
- 家庭急救准备的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/955=arr
- 家庭教育交流的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/zsn=603
- 城市生活服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/8hP=N9A
- 医院导诊服务的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/469
- 便民信息查询的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/qou
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/oe5
- 个人信息保护的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/999=kan
- 生活服务数字化的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/gnn=065
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/0Fp=JjJ
- 青少年编程学习的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/614
- 无障碍出行的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/nls
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/c0z
- 校园阅读活动的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/219=abc
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/dne=414
- 城市水环境观察的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/kT2=vVf
- 邻里共享空间的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/917
- 智能手机助老的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/yah
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/AnW
- 家庭运动计划的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/453=rba
- 城市雨天出行的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/sqx=203
- 生活垃圾回收的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/4w4=U3G
- 个人时间管理的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/552
- 社区活动空间的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/nut
- 老旧小区改造的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/Df7
- 数字生活课堂的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/917=qmu
- 公共设施使用的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/utz=520
- 地方美食文化的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/6As=Jpd
- 数字阅读服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/782
- 数字创意课程的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/ulv
- 街区小店体验的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/vP7
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/405=qmj
- 地方文化传播的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/uoi=666
- 社区手工活动的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/jl4=voB
- 传统节日科普的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/591
- 社区活动策划的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/uuo
- 数字学习资源的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/gFV
- 科学运动指导的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/010=bom
- 基层健康档案中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/nqp=928
- 网络安全教育的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/bdJ=Esa
- 社区设施共享的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/261
- 公共服务咨询的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/bhw
- 开源技术交流的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/DCV
- 社区防暑服务的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/337=ihp
- 城市文化路线的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xdn=513
- 生活服务数字化的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/yLQ=RoJ
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/849
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/bjy
- 数字资源检索的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/EUe
- 科学健身方法的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/601=koa
- 居家适老化改造中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/mlh=635
- 个人数据管理的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/jrD=71v
- 绿色出行服务的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/507
- 社区法律科普的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/zue
- 社区活动空间的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/heY
- 城市空气科普的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/391=int
- 节能生活方式的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/bul=913
- 通勤路线规划的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/OIz=l4Y
- 农业科普体验的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/712
- 便民信息查询的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/vjy
- 软件开发学习的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/6mv
- 老年友好服务的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/388=yzh
- 新能源出行的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/opb=524
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/tdV=aK4
- 社区阅读服务的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/942
- 地方文化传播的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/bxd
- 传统节日科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/Tu5
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/112=nii
- 数字公共文化的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/lnl=488
- 休闲运动入门的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/Vp5=lRd
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/111
- 社区家政服务的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/jux
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/sv4
- 学校体育活动的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/902=eot
- 骑行路线规划的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/mhs=413
- 城市夜间照明的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/S5J=aJr
- 儿童友好空间的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/948
- 街区绿化养护的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/bca
- 绿色生活实践的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/bbu
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/684=mki
- 社区养老服务的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/rmq=459
- 开源技术交流的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/urh=8iO
- 乡村阅读空间的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/986
- 家庭运动计划的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/hth
- 家庭节能实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/2pu
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/539=tao
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/jyq=562
- 城市适老服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/gFs=7W2
- 乡村文化空间的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/222
- 家庭急救准备的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/gcw
- 城乡公共服务的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/GnE
- 地方民俗记录的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/452=haf
- 家庭用电安全的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/kni=144
- 社区修缮行动的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/0VI=k1F
- 家庭健康科普的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/005
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/ydi
- 城市住房服务的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/HuH
- 社区共享书架的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/891=rbi
- 城市文明实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/dbx=453
- 全民健身活动的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/cmm=p8v
- 社区体育组织的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/578
- 公共服务咨询的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/bua
- 智慧停车服务的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/oVp
- 社区交通安全的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/751=rig
- 城市体育设施的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/byd=664
- 数字课堂应用的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/a2C=OlQ
- 城市公共自行车的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/949
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/zjj
- 科学教育活动中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/jiK
- 城市绿色交通的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/904=uar
- 乡村产业科普的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/gwt=925
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/lgv=Yfj
- 社区活动策划的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/774
- 志愿服务平台的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/eic
- 城市地名文化的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/b6P
- 个人数据管理的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/678=xrc
- 城市文化路线的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/okm=684
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/bUD=ZMU
- 通勤路线规划的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/919
- 家庭网络使用的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/bfh
- 城市基础设施的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/vLU
- 数字支付体验的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/792=fmo
- 在线学习体验的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/mly=605
- 家庭网络使用的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/gZX=jNe
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/864
- 小区停车协商的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/vjz
- 街区道路维护的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/s2m
- 社区法律科普的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/039=nsa
- 城市运动公园的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/oae=595
- 城市便民驿站的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/lyQ=I5s
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/776
- 乡村生态观察的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/hlr
- 老年人日常照护的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/cgF
- 数字政务体验的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/959=typ
- 文化场馆预约的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/gji=465
- 在线教育体验的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/Mhy=OCd
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/349
- 街头绿植养护的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/pfo
- 在线学习体验的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/jzZ
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/406=hka
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/xra=206
- 公共服务沟通的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/Is1=3Nn
- 周末休闲规划的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/555
- 小区停车协商的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/ewm
- 绿色生活实践的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/KN7
- 口袋公园建设的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/235=kyz
- 社区快递服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/atg=593
- 图书馆数字服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/m6R=I8m
- 安全出行教育的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/863
- 食品配送体验的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/wjh
- 城市文明实践的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/foV
- 城市博物馆服务的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/087=rwo
- 图书借阅体验的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/asl=618
- 社区手工活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/o1R=d47
- 便民信息查询的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/623
- 数字设备回收的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/ugn
- 乡村阅读空间的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/OA6
- 老年学习活动的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/466=tow
- 校园安全教育的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/bnt=132
- 城市空气科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/VhG=uU0
- 城市农夫市集的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/818
- 数字便民地图的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/egc
- 读书会组织的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/U7X
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/498=cbz
- 校园社团活动的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/jul=221
- 社区故事采集的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/pwN=zmX
- 社区知识分享的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/330
- 绿色办公实践的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/hhg
- 乡村文化活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/1z5
- 家庭节能实践的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/497=ywm
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/buw=041
- 家庭照护支持的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/3PG=dDv
- 网络信息辨识的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/662
- 科学教育活动的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/rdx
- 老年数字阅读的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/GwE
- 基层健康档案的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/102=brv
- 城市可持续生活的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/vjr=931
- 社区公共卫生的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/13M=ClF
- 创业经验分享的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/511
- 社区学习活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/nbq
- 公共文化活动的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/xIb
- 社区活动空间的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/609=pdu
- 小区电梯维护的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/cuz=704
- 乡村公共服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/OSF=vh3
- 城市绿道建设的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/011
- 居民健康教育的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/kit
- 家庭急救准备的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/wyZ
- 社区体育组织的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/795=pkx
- 儿童友好街区的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/lgv=863
- 校园社团活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/0FJ=lhC
- 学校食育活动的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/630
- 居家适老化改造的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/xhd
- 乡村阅读空间的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/DxB
- 口袋公园建设的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/116=ljs
- 邻里互助活动的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/tbi=072
- 公共卫生宣传的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/Ioj=SN4
- 儿童友好空间的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/641
- 本地消费场景的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/wwy
- 健康饮水科普的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/Tio
- 基层健康服务的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%9B%B2%E8%89%BA?/345=smd

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
