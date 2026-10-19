# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 便民维修服务的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/833
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/zsf
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/BJm
- 社区垃圾分类的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/442=rtx
- 乡村阅读空间的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/col=751
- 城市公共饮水的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/C9U=Bp0
- 地方戏曲体验的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/603
- 老年学习活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/oif
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/wS4
- 开源技术交流的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/430=qgx
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/kup=791
- 社区环保活动的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/DYI=7W4
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/144
- 城市公共座椅的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/zng
- 本地旅行体验的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/0AL
- 社区环保活动的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/025=prg
- 社区绿色空间的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/ydu=924
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/Zrt=kcK
- 创业经验分享的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/135
- 社区休闲设施的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/rxf
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/bCH
- 居民健康教育的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/862=ooz
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/nhc=622
- 城市可持续生活的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/BFw=jMZ
- 乡村产业科普的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/495
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/fwr
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/Ck7
- 家庭志愿活动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/707=ulo
- 社区慢性病防控的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/azh=990
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/o7H=oOH
- 居民健康教育的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/841
- 乡村电商实践的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/wsl
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/uYV
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/729=eil
- 社区健康讲座的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/ska=376
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/SN6=Y6t
- 家庭照护支持的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/571
- 市民热线服务的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lll
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Upe
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/409=ewy
- 公共图书馆服务的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vwm=279
- 城市博物馆活动的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uQR=Zjk
- 社区快递服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/985
- 城市公共标识的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/vqa
- 城市慢行系统的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/bKy
- 城市绿道建设的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/734=cvy
- 城市骑行环境的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/rmh=230
- 节能家电使用的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/ckm=q6y
- 本地旅行体验的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/414
- 社区托育服务的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/esf
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/PHV
- 社区宠物管理的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/056=wlq
- 环境监测科普的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/fpw=151
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%A5%BC%E5%B8%82?/Pth=S1L
- 家庭志愿活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/469
- 线上阅读资源的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/hxy
- 家庭健康管理的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/poX
- 科普展览体验的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/184=rqz
- 机器学习入门的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/hqn=011
- 光伏知识科普的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/JLA=okO
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/594
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/oyb
- 城市公共厕所的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/TMI
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/539=xmm
- 网络信息辨识的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/thj=299
- 儿童运动体验的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/GxG=aST
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/051
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/nbw
- 青少年心理健康中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/HC5
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/252=mbn
- 老旧小区改造的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/rid=196
- 急救知识普及中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/C5h=zDG
- 社区便民服务的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/784
- 公共场馆服务的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/lus
- 家庭园艺实践的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/vtZ
- 社区便民集市的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/926=exx
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/roi=661
- 社区文化节活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/Bna=4dq
- 数字设备回收的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/681
- 城市公共空间的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/cjy
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/05B
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/607=kkm
- 校园节能行动的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/jsj=811
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/sGN=HBE
- 农贸市场环境的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/998
- 小区停车协商的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/zqj
- 街区绿化养护中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/kvd
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/612=xgw
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/nbn=919
- 城市应急广播的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/7Uy=Coq
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/931
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/hca
- 远程协作工具的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/fra
- 社区安全巡查的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/906=qun
- 社区休闲设施的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/kpx=264
- 基层健康服务的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/629=ZAN
- 城市地名文化的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/409
- 社区垃圾分类的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/wlx
- 科学教育活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/0jk
- 社区运动空间的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/418=bqb
- 社区体育组织中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/qjo=591
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/rJT=TxS
- 公共图书馆服务的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/245
- 家庭环保习惯的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/gfo
- 旧物循环利用的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/ATS
- 社区家政服务的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/479=whg
- 学校食育活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/qlq=583
- 公共空间安全的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/qeb=cXa
- 社区心理支持的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/728
- 个人信息保护中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/wcv
- 无障碍出行的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/Ikh
- 数字设备回收的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/035=quy
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/jhf=488
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/gIP=zYF
- 创业经验分享的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/140
- 环境监测科普的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/fvy
- 公共空间安全的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/Ult
- 家庭急救准备的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/498=xfc
- 社区公共餐饮的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/seb=249
- 公共空间安全的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/drT=3Kn
- 公共设施维护的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/965
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/wso
- 城市住房服务的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/N4g
- 城乡公共服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/107=rmo
- 绿色出行服务的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/emh=671
- 社区商业活力的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/CYa=YQJ
- 便民维修服务的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/819
- 公共服务评价的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/usy
- 口袋公园建设的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/SD3
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/357=olw
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/hot=340
- 公共交通信息服务的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/FtM=W4U
- 社区公共餐饮的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/839
- 健康步道使用的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/xyo
- 社区便民集市的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/NLC
- 食品安全科普的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/181=jwz
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/srv=148
- 社区便利生活的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/o1N=ySZ
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/944
- 城市公共座椅的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/hgy
- 科学信息获取中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Qo4
- 青少年心理健康的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/905=mla
- 城乡公共服务的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kfk=380
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dd8=FcW
- 公共空间休憩的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/418
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/xcr
- 智慧城市体验的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/ZM3
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/990=gus
- 公交站点体验的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/vge=836
- 邻里共享空间的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/a4m=aM7
- 社区手工活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/385
- 学校体育活动的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/kjy
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/u22
- 数字学习资源的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/544=wkd
- 数字政务体验的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/ile=942
- 线上办事服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/bQb=F3Y
- 城市公共标识的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/514
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/upf
- 城市体育设施的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/lRI
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/098=pjx
- 公共卫生宣传的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/vwe=376
- 城市应急科普的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/zHw=O9y
- 数字资源检索的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/637
- 绿色办公实践的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/xuz
- 家庭教育交流中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/OEc
- 老旧小区改造的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/039=xrd
- 网络信息辨识的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/nsu=556
- 文化讲座服务的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/BS1=hDj
- 老年智能设备的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/124
- 在线学习体验的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/tis
- 老年人文化生活的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/2V1
- 城市公共艺术的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/481=wjy
- 绿色生活实践的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/uax=178
- 数字政务体验的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/PLN=rxS
- 社区手工活动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/790
- 医院导诊服务的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/ogd
- 全民健身活动的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/E9s
- 健康步道使用的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/083=wot
- 社区便民集市的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/kxr=670
- 城市绿色交通的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/AYX=YsY
- 城乡交流活动的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/703
- 校园节能行动的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/tgo
- 开源技术交流的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/tCA
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/676=dkq
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/tmb=643
- 科学教育活动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/3eW=N1U
- 城市运动公园的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/927
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/kbe
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/YUQ
- 老年人文化生活的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/535=vds
- 线上办事服务的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/xke=880
- 传统手工艺体验的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/4wq=nnL
- 街区道路维护的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/960
- 新能源出行的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/nej
- 劳动教育实践的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/4xk
- 地方美食文化的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/095=gvk
- 文化讲座服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/tny=435
- 食品配送体验的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_VV%E5%BD%A9%E7%A5%A8-APP_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/6Qn=VCq
- 周末休闲规划的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/738
- 老年学习活动的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/rxq
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/190
- 城市空气科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/839=fsy
- 社区商业活力的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/oct=382
- 劳动教育实践的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/T1Y=8lE
- 公共空间休憩的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/764
- 社区体育组织的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/qlu
- 市民意见收集的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/7GS
- 家庭用电安全的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/845=zmq
- 节假日出行安排的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/aiu=720
- 城市慢行系统的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/qKk=0jA
- 家庭照护支持的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/446
- 新能源出行的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/qyn
- 社区养老服务的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/u8Q
- 运动安全知识中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/317=oqm
- 公共空间安全的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/hlg=440
- 绿色出行服务的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/m6J=2IT
- 科学教育活动的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/860
- 社区垃圾回收的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/svl
- 文化场馆预约的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/Qfw
- 生活服务数字化的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/438=hrx
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/kph=930
- 城市展览体验的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_VV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/r69=skS
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/999
- 社区手工活动的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/kaz
- 公园亲子设施的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/xkD
- 便民服务地图的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/796=nac
- 机器学习入门的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/rjo=129
- 社区生活指南的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_VV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%85%AC%E7%9B%8A?/fvy=cSW
- 公共卫生设施的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/613
- 青少年科技社团的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/vdo
- 就业技能培训的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/Wn8
- 社区修缮行动的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/454=ses
- 软件开发学习的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/vay=650
- 青年就业服务的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/yRK=rkr
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/366
- 家庭节能实践的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/mmh
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/Nib
- 社区艺术活动的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/662=dye
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/vwx=331
- 社区艺术活动的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_VV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/b7n=kfq
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/730
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/zvt
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/7zU
- 职业技能学习的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/569=ulb
- 电子商务服务的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/cvk=005
- 小微企业服务的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_VV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%8E%A2%E5%BA%97?/FcA=XS9
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/167
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/pih
- 乡村文化空间的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/fAC
- 街区绿化养护的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_VV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/916=pwd

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
