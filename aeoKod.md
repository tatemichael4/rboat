# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 社区公共卫生的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/454
- 邻里互助活动的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/dhw
- 个人时间管理的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/60X
- 老年人日常照护的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/256=krw
- 亲子科普活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/nip=558
- 社区学习活动的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/wYG=8V3
- 学校食育活动的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/857
- 城市基础设施的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/psz
- 非遗体验活动的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/4lD
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/718=owe
- 在线教育体验的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/hpz=410
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/1tO=3dZ
- 校园安全教育的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/689
- 城乡交通衔接的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/yfr
- 城市公共艺术的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/D9b
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/678=fzn
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/uyy=553
- 农产品消费体验的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/Buh=tWs
- 城市共享单车的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/461
- 智能家居应用中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/vjy
- 就业技能培训的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/bPn
- 城市雨天出行的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/329=pyn
- 数字便民地图的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/pfk=459
- 节假日出行安排的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C?/9ZN=SWx
- 社会体育指导的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/935
- 通勤路线规划的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/jpo
- 社区应急准备的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/lv2
- 电子商务服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/912=tbj
- 线上阅读资源的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/blz=114
- 乡村文化活动的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/jA9=XfF
- 儿童户外活动的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/583
- 社区托育服务的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/dpu
- 城市地名文化的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/aAP
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/545=zxu
- 机器人科普活动的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/mad=560
- 个人时间管理的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E5%91%A8%E6%8A%A5?/KkS=0fY
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/089
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/aui
- 儿童友好空间的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/Mk5
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/985=qno
- 节假日出行安排的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/ipl=087
- 家庭急救准备的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/MM4=J7v
- 公共文化活动的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/992
- 公共服务指南的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/poe
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/Tjs
- 社区家校合作的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/969=tiq
- 图书馆数字服务的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/mql=486
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/iaK=YLH
- 租房信息服务的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/916
- 居家适老化改造的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/umo
- 科学健身方法的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/hP0
- 口袋公园建设的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/517=mob
- 家庭园艺实践的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/uis=664
- 家庭网络使用的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%A7%91%E6%8A%80?/EHB=JN6
- 乡村产业科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/043
- 青少年科普实践的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/blb
- 便民信息查询的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/K8B
- 校园节能行动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/780=gaw
- 社区互助网络的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/dfi=056
- 公共空间照明的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/ux4=LS1
- 公共设施使用的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/788
- 光伏知识科普的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tcn
- 家庭园艺实践的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3GO
- 环境教育课程的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/341=mce
- 人工智能科普的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nhu=490
- 公共空间照明的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/6i2=Dsm
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/204
- 社区活动空间的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/ewo
- 小微企业服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/iNe
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/169=hog
- 公共服务数字化的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/pwf=941
- 节气饮食文化的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/Tj5=GCE
- 家庭环保习惯的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/583
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/qwz
- 公共设施使用的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/Ltl
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/584=ree
- 健康饮食教育的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/wyd=804
- 环境教育课程的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83100-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%A8%8E%E5%8A%A1?/bOZ=3HS
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/207
- 本地历史资料的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/vty
- 城乡公共服务的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/5pc
- 社区活动报名的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/748=mki
- 城市公共饮水的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/rcy=727
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/rBG=L4d
- 地方美食文化的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/644
- 信息无障碍体验的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/olt
- 城乡交流活动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/wgs
- 社区活动策划中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/187=hyo
- 应急物资管理的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/alk=228
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/FrG=Ndc
- 儿童阅读角的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/493
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/axh
- 科技馆参观体验的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/lV4
- 青少年编程学习的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/596=jsr
- 学校体育活动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/jjz=494
- 线上办事服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/8TI=c3m
- 医院导诊服务的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/230
- 家庭网络使用的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/wqg
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/qL3
- 城市建设科普的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/010=sxp
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/cfj=060
- 科学信息获取的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/gKk=CCe
- 健康饮食教育的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/668
- 街区小店体验的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/gry
- 数字创意课程的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/YlJ
- 老年运动活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/405=nxe
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/bwm=296
- 安全出行教育的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95welcome_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/Di7=yff
- 无障碍出行的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/815
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/wri
- 城市人文观察的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/KZJ
- 机器人科普活动的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/310=nwv
- 文明养宠科普中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/eti=510
- 本地历史资料的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E7%BB%8F%E6%B5%8E?/9Fr=0gJ
- 数字创意课程的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/174
- 公交无障碍服务的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/dzq
- 远程协作工具的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/WfR
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/331=tgm
- 城市住房服务的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/gyz=457
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/EDe=Y6v
- 无障碍出行的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/048
- 个人数据管理的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/apu
- 基层服务创新中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/GpF
- 城市便民驿站的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/743=pzk
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/cap=599
- 地方民俗记录中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/hQJ=Bfu
- 家庭用电安全的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/658
- 城乡公共服务的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/yrx
- 城市建设科普的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/mqK
- 社区手工活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/510=xtp
- 基层医疗预约的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/qsl=087
- 城市适老服务的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83100-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/QGw=sWL
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/177
- 在线学习体验的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/aev
- 城市夜间照明的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/6ct
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/013=gpp
- 城市博物馆服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/qnd=421
- 生活垃圾减量的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/O6f=M4x
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/265
- 光伏知识科普中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/dbr
- 地方文化传播的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/nZ2
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/744=nih
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/txs=654
- 社区公共卫生的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BC%80%E5%BF%83100-APP_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/c28=27c
- 灵活就业交流的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/621
- 科技馆参观体验的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/cct
- 城市骑行环境的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/X9U
- 城市博物馆服务的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/943=pzq
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/kgz=275
- 绿色生活实践的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83100-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/oQR=LJB
- 安全出行教育的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/923
- 新能源出行从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/woo
- 公共服务沟通的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/ueq
- 创业经验分享的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/278=eif
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/plh=677
- 社区菜市场服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%8A%A8%E6%BC%AB?/57m=v08
- 休闲运动入门的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/442
- 本地历史资料的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/htk
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/raq
- 城市体育设施的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/725=fiw
- 医院导诊服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/ejs=660
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/o64=5QI
- 社区法律科普的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/910
- 城市步行友好的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/bsk
- 节气饮食文化的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/N16
- 家庭用电安全的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/283=nnp
- 科学运动指导的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/qtm=090
- 食品安全科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83100-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/fjQ=m1K
- 社区便民集市的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/134
- 社区运动空间中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/hpg
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/xf4
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/357=fjx
- 社区安全巡查的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/jda=673
- 开放式学习空间的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/WOh=UOk
- 城市可持续生活的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/113
- 青年职业探索的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/svx
- 邻里互助活动的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/r3Y
- 社区科普课堂的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/769=nsm
- 食品安全科普的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/yrb=708
- 骑行路线规划的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/0nM=iDy
- 社区便民服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/300
- 城市绿色交通的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/qep
- 开放数据应用的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/Qmx
- 药品使用科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/544=aoi
- 个人数据管理的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/tcf=807
- 地方旅游导览的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/iWU=D3C
- 个人时间管理的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/525
- 社区阅读服务的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/gtq
- 日常摄影记录的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/3sy
- 街头绿植养护的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/117=upi
- 城市共享单车的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/rgx=085
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83100-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/qLp=8U2
- 公共健身器材的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/637
- 社区绿色空间的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/lyo
- 数字资源检索的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/0cQ
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/549=rab
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/fcj=801
- 农贸市场环境的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/pOm=Tdg
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/280
- 气象科普传播的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/fin
- 青少年科普实践的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/3YZ
- 乡村生态观察的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/855=boq
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/cea=439
- 健康信息获取的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83100-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/3U0=MeY
- 旧物循环利用中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/515
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/jfv
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/EfQ
- 城市空气科普的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/761=xro
- 乡村文化空间的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/flk=448
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/XMp=prX
- 社区便利生活的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/071
- 基层健康档案的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/bir
- 科学教育活动的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/rUz
- 校园社团活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/645=ocn
- 志愿者培训交流的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/isk=374
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/cTZ=wJ9
- 青年就业服务的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/615
- 开放数据应用的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/ije
- 药品使用科普的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/YUJ
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/630=ohi
- 节约用水实践的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/fis=184
- 城市噪声观察的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/3rp=YdV
- 智能手机助老的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/686
- 智能手机助老的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/xcv
- 街区绿化养护的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/Co3
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/068=sbe
- 数字课堂应用的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/iwr=202
- 社区庭院绿化的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/FAv=5ZC
- 社区便民集市的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/428
- 社区托育服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/fvn
- 城市应急科普的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/JVp
- 社区儿童活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/345=wbj
- 街区小店体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/hmo=659
- 绿色快递包装的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/0tV=8km
- 社区花园共建的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/548
- 城乡交通衔接的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/bnj
- 数字阅读服务中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/dnk
- 公共场馆服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/159=ynl
- 公共空间安全的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/zdu=110
- 家庭园艺实践的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/YYG=Yg7
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/389
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/wac
- 公共空间安全的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/heK
- 城市公共饮水的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/231=sla
- 学校食育活动的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/rxq=910
- 农村环境治理的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/ydc=fGD
- 老年人日常照护的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/064
- 城市博物馆活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/nps
- 城市共享单车的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/EO0
- 城市公共座椅的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/689=nfy

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
