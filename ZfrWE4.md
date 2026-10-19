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

- 社区教育资源的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/drE
- 健康饮食教育中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/490=ocj
- 社区文化传播的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/zpq=446
- 社区文化节活动的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/hkJ=lBa
- 节能生活方式的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/590
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/yul
- 生成式工具使用的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/mbP
- 骑行路线规划的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/102=wav
- 城市建设科普的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/usu=020
- 家庭环保行动的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/AY2=bNA
- 数字生活课堂的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/937
- 儿童友好空间的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/ifh
- 公共空间安全的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/CUv
- 信息无障碍体验的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/420=ejq
- 节假日出行安排的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/hgk=338
- 城市游园体验的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/2Mr=vED
- 读书会组织的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/058
- 城市应急广播的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/wgt
- 数字课堂应用的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/0fM
- 科学信息获取的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/061=yns
- 城市基础设施的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/rlp=467
- 骑行路线规划的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/PMP=rKS
- 科学信息获取的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/662
- 城市雨天出行的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/xse
- 绿色校园实践的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/6Yl
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/929=oig
- 公共空间安全的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/urb=064
- 健康饮水科普的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/4vg=xLb
- 社区法律科普的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/326
- 城市生活服务的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/jth
- 小区电梯维护的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/vSA
- 图书借阅体验的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/666=lgw
- 城市夜间照明的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/cup=514
- 乡村阅读空间的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/BYO=UJP
- 社区手工活动的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/917
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/jiv
- 公共健身器材的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/LSp
- 城市公共标识的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/193=sjx
- 公共健身器材的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/wvu=613
- 读书会组织的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/fM0=kq7
- 科普展览体验的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/050
- 非遗课堂体验的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/ofc
- 劳动教育实践的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/xXT
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/258=ftq
- 公共服务沟通的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/bcp=029
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/wKS=IlT
- 邻里共享空间的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/413
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/ynf
- 急救知识普及的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/aBX
- 电子商务服务的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/772=qbs
- 科学教育活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/dbm=206
- 社区活动报名的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/KMT=R1K
- 口袋公园建设的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/323
- 无障碍出行的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/qft
- 亲子阅读活动的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/L1K
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/116=wkm
- 新能源出行的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/kwe=747
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/qXa=osi
- 数字设备回收的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/625
- 社区公共议事中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/pts
- 社区体育组织的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/3nT
- 便民服务窗口中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/818=gdq
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/wow=842
- 数字资源检索的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E9%94%90%E8%AF%84?/Uwa=xXR
- 城市可持续生活的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/891
- 运动安全知识的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/qyp
- 安全出行教育的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/o0x
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/075=yra
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/adf=882
- 数字档案服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/G3U=Ecv
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/933
- 租房信息服务的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/zoj
- 城市绿道建设的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/7Il
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/055=ibj
- 社区宠物管理的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/sxp=608
- 街区绿化养护的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/hIC=cOP
- 急救知识普及的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/022
- 社区老年食堂的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/kwh
- 乡村阅读活动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/h2Y
- 数字便民地图的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/536=hse
- 社区修缮行动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/zrv=044
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/M7Q=x3m
- 城市体育设施的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/270
- 乡村文化空间的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/yvm
- 节假日出行安排的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/LTW
- 线上办事服务的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/094=fwv
- 电子商务服务的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/zhx=274
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/77w=oWp
- 数字生活课堂的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/986
- 节气饮食文化的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/cjt
- 家庭节能实践的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/JTx
- 社区家校合作的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/560=jnt
- 城市雨天出行的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/tpe=209
- 基层服务创新的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E7%89%A9?/nhT=SxX
- 软件开发学习的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/039
- 社区交通安全的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/sfr
- 社区艺术活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/one
- 周末休闲规划的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/083=ttn
- 数字便民地图的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/zce=450
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/VYB=of1
- 社区法律科普的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/768
- 公益活动组织的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/ary
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/2z9
- 乡村教育资源的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/571=ohw
- 线上办事服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/bqm=795
- 科学健身方法的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/Bo2=xrT
- 终身学习资源的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/177
- 数字创作工具的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/ggn
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/g7X
- 就业技能培训的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/884=zyk
- 社区互助网络的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/pqr=529
- 乡村生态观察的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/SyQ=Bdi
- 公共交通接驳的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/224
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/zhd
- 非遗课堂体验的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/gFm
- 校园安全教育的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/562=hhv
- 街区道路维护的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/qof=646
- 网络信息辨识的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/X85=DSt
- 街区道路维护的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/151
- 城市体育设施的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/bdd
- 家庭节能设备的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/BOX
- 社区停车服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/142=jpe
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/exn=192
- 农产品消费体验的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/UBt=rEj
- 社区公共卫生的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/384
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/iac
- 智能手机助老的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/Edp
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/336=zse
- 数字素养提升的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/ufo=665
- 垃圾分类指导的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/VyX=IwI
- 数字设备回收中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/498
- 基层医疗预约的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/pxr
- 社区应急准备的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/bvD
- 科学教育活动的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/625=bur
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/fbd=460
- 健康信息获取的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/2C9=DMO
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/295
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/fac
- 本地历史资料的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/r2h
- 数字档案服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/291=rxv
- 户外活动组织的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/bxy=521
- 课后服务体验的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_360%E6%B8%AF%E8%82%A1?/TJE=h2Q
- 校园节能行动的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/592
- 城市慢行系统的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/ycu
- 线上办事服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/pwq
- 社区环保活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/367=kdr
- 社区协商议事的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/jql=056
- 通勤路线规划的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/j6l=9Ju
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/527
- 机器人科普活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/lcl
- 科普展览体验的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/h4j
- 传统节日科普的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/691=hfo
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/lbz=714
- 公共设施使用的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/Jyc=sZE
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/785
- 课后服务体验的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/pkq
- 便民服务窗口的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/pH5
- 城市住房服务的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/898=nmx
- 社区儿童活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/hnz=688
- 城市博物馆活动的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/Rj4=X3j
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/827
- 志愿服务平台的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/yhu
- 数字便民地图的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/QFf
- 家庭健康管理的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/925=xcg
- 家庭科学教育的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/hgj=507
- 乡村电商实践的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/7o1=crO
- 社区托育服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/694
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/lzh
- 家庭消费规划的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/Ba0
- 物业服务沟通的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/225=kgg
- 公共设施维护的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/kkg=429
- 社区活动空间的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/rOb=Dd5
- 社区菜市场服务的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/645
- 本地历史资料的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/pzl
- 城市水环境观察的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/piQ
- 科普展览体验的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/375=rlg
- 乡村教育资源的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/dar=109
- 青少年户外教育的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/woF=XIZ
- 本地旅行体验的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/576
- 家庭网络使用的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/wsa
- 社区托育服务中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/yj0
- 社区养老服务的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/178=cay
- 家庭食品保存的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/bqx=085
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/xfl=kmP
- 环境教育课程的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/380
- 数字素养提升的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/pgd
- 居民健康教育的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/oky
- 街区更新实践中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/599=rfu
- 网络信息辨识的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/opx=289
- 城市休闲步道的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/1ME=56M
- 城市步行友好的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/282
- 公共服务预约的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/skz
- 智能手机助老的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/6ui
- 数字学习资源的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/190=irh
- 城市人文观察中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/iji=630
- 街头绿植养护的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/CUw=YoM
- 职业技能学习的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/077
- 城市建设科普的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/upt
- 公共空间照明的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/lQw
- 社区便民集市的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/161=vru
- 社区手工活动的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/kwy=398
- 居民健康教育的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/jAl=8jx
- 急救知识普及的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/173
- 街区更新实践的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/rrp
- 城市便民驿站的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/YOr
- 数字阅读服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/734=xwe
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/cjw=190
- 公共服务评价中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/qdv=XMF
- 科学观察活动的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/284
- 家庭养老规划的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/nme
- 社区公共卫生的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/r3w
- 小微企业服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/986=iwb
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/mhv=138
- 家庭食品保存的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/RL8=QYm
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/770
- 基层健康服务的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/pzm
- 社区休闲设施的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/cfk
- 地方文化传播的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/899=wpj
- 小微企业服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/xqn=101
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/QGT=fy2
- 数据分析入门的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/315
- 家庭照护支持的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/tpt
- 城市公共座椅的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/JpC
- 乡村教育资源的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/444=nth
- 开放式学习空间的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/qjb=902
- 生成式工具使用的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/hV8=De0
- 社区便民集市的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/603
- 数字艺术创作的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/lmh
- 绿色生活实践的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/4yz
- 新能源知识普及的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/084=zoi
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/yoi=240
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/BT9=QjT
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/488
- 社区休闲设施的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/bqg
- 社区应急准备的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/sNt
- 公共服务预约的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/475=xdb
- 城市步行友好的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/sho=192
- 远程协作工具中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/yir=zMw
- 绿色消费选择的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/524
- 生活技能分享的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/zth
- 科学观察活动的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/AiZ
- 城市运动公园的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/015=svc
- 绿色办公实践的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/teu=026
- 社区慢性病防控的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/BjF=l6g
- 软件开发学习的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/095
- 公益活动组织的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/vgr
- 社区健康讲座的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/xOw
- 节能生活方式的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/796=qon
- 老年人日常照护的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/rrt=846
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/Ayb=pUJ

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
