# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 科学睡眠习惯的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/RlR
- 公共文化活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/823=lhb
- 机器人科普活动的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/kaa=252
- 社区邻里服务的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/F5B=kiY
- 乡村生态观察的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/133
- 居民健康教育的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/xco
- 食品安全科普的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/jKB
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/761=cpc
- 智慧停车服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/rkw=719
- 小区停车协商的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/3iy=opI
- 市民意见收集的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/560
- 机器人科普活动的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/fzp
- 绿色出行服务的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/A76
- 数字资源检索的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/717=yzf
- 儿童友好街区的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/gqq=877
- 城市共享单车的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/Ake=4Id
- 口袋公园建设的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/001
- 科普展览体验的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/ork
- 地方旅游导览的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/E6m
- 社区防暑服务的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/008=mbq
- 社区文化节活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/xgt=656
- 就业技能培训的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%8E%E4%BA%8B?/MvX=eNm
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/661
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/rhe
- 绿色出行服务的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/KXl
- 开放式学习空间的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/580=max
- 社区停车服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/wjm=352
- 在线学习体验中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/i2z=nog
- 城市骑行环境中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/458
- 个人信息保护的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/tup
- 乡村阅读活动的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/zlz
- 青年就业服务的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/821=xrd
- 城市骑行环境的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/fow=276
- 城市展览体验的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/nMc=fA4
- 社区修缮行动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/813
- 老年人出行服务的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/bou
- 线上阅读资源中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/6nS
- 个人数据管理的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/020=pnc
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/pcc=627
- 儿童友好空间的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/LID=sU0
- 城市人文观察的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/256
- 药品使用科普的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/fji
- 乡村电商实践的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/hZf
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/080=dwq
- 文化讲座服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/odo=155
- 本地消费场景的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/QbC=AvL
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/861
- 青少年心理健康的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/zcr
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/gd9
- 文明养宠科普的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/780=zju
- 全民阅读推广的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/rfl=831
- 城市骑行环境的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E9%99%85?/lcj=Dkv
- 社区科普课堂的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/588
- 社区健康讲座的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/ubz
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/xBy
- 乡村产业科普的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/283=dru
- 食品配送体验的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/ogg=246
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%96%87%E6%91%98?/OPO=Y6X
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/691
- 公共交通接驳的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/szh
- 数字政务体验的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/sUC
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/825=vfk
- 家庭阅读计划的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/kte=652
- 社区共享书架的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/4r3=20e
- 本地消费场景的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/562
- 乡村公共阅读的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/tmd
- 公交站点体验的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/idd
- 社区安全巡查的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/657=lhe
- 社区知识分享的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/yep=398
- 数字档案服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/IOQ=vkK
- 青少年科技社团的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/494
- 便民服务窗口的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/jwy
- 社区修缮行动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/H12
- 无障碍出行的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/261=tsp
- 机器学习入门的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/gjz=770
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/aus=2ed
- 灵活就业交流的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/137
- 城市公共座椅的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/pde
- 公共服务数字化的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/VnA
- 在线学习体验的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/186=kkp
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/qqw=907
- 文明养宠科普的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/5Hz=3uE
- 社区商业活力的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/041
- 乡村阅读空间的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/dhr
- 家庭养老规划的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/Jk0
- 数字课堂应用的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/264=khx
- 志愿者培训交流的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/nbl=766
- 社区应急准备的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/v0c=emT
- 社区儿童活动的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/987
- 城市应急科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/qzg
- 基层服务创新的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/O6W
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/618=xjx
- 家庭收纳实践的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/war=668
- 生成式工具使用的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/i6i=qWL
- 社区养老服务的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/855
- 家庭理财科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/rgu
- 本地消费场景的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/af5
- 志愿服务平台的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/617=byt
- 公共场所导视的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/enx=296
- 节约用水实践的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/Zg2=cC3
- 社区公共议事的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/065
- 乡村阅读空间的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/meo
- 跨代沟通活动的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/ZvD
- 生活垃圾减量的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/442=uaj
- 青年志愿活动中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/jyf=398
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/Uvt=X49
- 邻里互助活动的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/521
- 生活服务数字化的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/eix
- 社区花园共建中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/BXY
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/027=iwz
- 绿色生活实践的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/vqs=420
- 社区艺术活动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%85%A7%E7%9C%BC?/mpH=Pq2
- 创业经验分享的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/210
- 城市建设科普的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/qia
- 家庭环保行动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/o0H
- 城市共享单车的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/482=sgg
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/coy=416
- 药品使用科普的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/K7p=UzD
- 社区故事采集的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/215
- 公益活动组织的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/bhs
- 青少年科技社团的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/Zyf
- 线上办事服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/498=acd
- 文化场馆预约的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/whk=209
- 便民服务地图的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/xNS=sRq
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/250
- 社区信息发布的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/uar
- 开放式学习空间的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/YF3
- 邻里互助活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/128=mih
- 文明养宠科普的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/deo=528
- 家庭节能实践的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/XcI=DqO
- 儿童友好空间的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/945
- 城市休闲步道的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/krk
- 社区教育资源的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/v26
- 运动安全知识的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/353=htv
- 家庭饮食安排的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/oew=820
- 药品使用科普的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/cSF=nHA
- 家庭运动计划的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/425
- 旧物循环利用的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/rzs
- 社区阅读服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/4ct
- 绿色生活实践的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/876=hzv
- 信息无障碍体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/bep=392
- 社区老年食堂的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%90%86%E8%B4%A2?/DXg=84q
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/696
- 绿色生活实践的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/pfe
- 地方文化传播的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/rgA
- 旧物循环利用的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/574=war
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/vvk=232
- 健康步道使用的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/snp=bro
- 城市应急广播的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/799
- 公共设施维护中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/aqo
- 物业服务沟通的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/LOS
- 城市慢行系统的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/571=vaj
- 城乡公共服务的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/lxc=023
- 社区慢性病防控的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/iII=til
- 数字设备回收的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/413
- 开放数据应用的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/ojr
- 社区信息发布的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/lqu
- 非遗体验活动的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/958=ezw
- 家庭运动计划的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/ybn=334
- 城市夜间照明的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/HM5=En6
- 公共空间照明的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/111
- 校园社团活动的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/dtx
- 社区家政服务的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/8S5
- 亲子阅读活动的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/284=igs
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/qhg=595
- 小区公共照明的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/Rrf=Dh5
- 智能手机助老的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/988
- 便民服务窗口的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/aqw
- 学校食育活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/LlP
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/593=ucb
- 社区菜市场服务的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ryc=796
- 通勤路线规划的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/FZQ=yCq
- 文化场馆预约的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/247
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/zjn
- 学校食育活动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/FzL
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/935=jqk
- 校园阅读活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/awh=662
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/Lkv=F7R
- 邻里互助活动的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/194
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/nqj
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/VNv
- 社区绿色空间的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/630=rlv
- 社区生活指南的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/qhz=871
- 社区垃圾分类的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/E9E=pNC
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/551
- 城市夜间照明的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/brp
- 社区读书角建设的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/e6x
- 远程协作工具的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/308=vgf
- 城市展览体验的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/tny=268
- 生活技能分享的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/hzC=Qmv
- 公共文化活动的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/895
- 数字政务体验的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/qfr
- 家庭教育交流的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/6c4
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/905=eph
- 环境教育课程的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/sfc=059
- 新能源知识普及的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/H4K=i5l
- 公共卫生设施的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/869
- 社区手工活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/ibh
- 基层服务创新的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Ymc
- 食品配送体验的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/408=hvr
- 地方民俗记录的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/fvg=935
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/A7m=lZl
- 城市雨天出行的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/663
- 社区生活指南的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/kxf
- 儿童友好街区的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/jVb
- 社区托育服务的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/348=vtn
- 骑行路线规划的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/lob=313
- 旧物循环利用的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/DAd=IwR
- 城市公共自行车的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/035
- 数字设备回收的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/fjp
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/2Fk
- 青少年户外教育的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/678=hfu
- 校园阅读活动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/uog=060
- 公共服务咨询的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/Sf7=kFI
- 公共服务预约的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/413
- 公共空间照明的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/ort
- 社区环保活动中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/jyh
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/173=cno
- 健康饮食教育的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/lsc=022
- 开放数据应用的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/0ro=puO
- 农产品品牌传播的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/399
- 社区养老服务的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/ipo
- 城市公共空间的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/TIj
- 社区养老服务的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/061=rbm
- 公共卫生宣传的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/wbn=487
- 日常摄影记录的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%82%E7%82%B9?/YgJ=d8U
- 城市生活服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/985
- 居家适老化改造的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/kpw
- 社区知识分享的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/TfF
- 文化讲座服务的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/056=cqk
- 骑行路线规划的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/sfe=764
- 青少年科普实践的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/1RE=Xsd
- 城市共享单车的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/606
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/ywt
- 城市公共厕所的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/ROZ
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/103=ltd
- 绿色建筑理念的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/qmh=257
- 街道综合服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/aXm=1aZ
- 市民意见收集的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/809
- 软件开发学习的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/cer
- 线上办事服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/ggP
- 周末休闲规划的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/466=gor
- 儿童户外活动的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/epi=457
- 节日文化体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/JEX=bfU
- 图书借阅体验的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/316
- 家庭教育交流的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/dsw
- 公共服务指南的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/DjW
- 公交站点体验的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/806=owp
- 地方戏曲体验的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/rsb=878
- 社区应急准备的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/fLM=gFi

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
