# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 老年人日常照护的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/wnt=464
- 城市共享单车的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/Hdu=IsT
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/263
- 公共服务评价的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/guy
- 机器人科普活动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/xSl
- 公共交通接驳的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/037=pmv
- 城市运动公园的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/zda=973
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/8Nh=30q
- 数字设备回收的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/687
- 职业技能学习的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/kyt
- 市民热线服务的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/90N
- 数字政务体验的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/784=dpr
- 乡村生活观察的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/mwq=614
- 数字创作工具的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/Tfg=GVq
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/348
- 公共卫生宣传的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/zdt
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/Z0t
- 休闲运动入门的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/168=noi
- 基层服务创新中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/lrb=846
- 急救知识普及的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/Dz4=Un7
- 小微企业服务的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/767
- 节日文化体验的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/okb
- 节约用水实践的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/mqK
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/187=nfu
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/ytg=944
- 城市空气科普的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/lcA=tkQ
- 社区活动报名的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/391
- 青少年科普实践的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/qis
- 软件开发学习的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/Di6
- 城市树木认养的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/885=jeo
- 城市空气科普的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/kee=829
- 智慧城市体验的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/ao4=VUp
- 家庭健康管理的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/732
- 公园亲子设施的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/crj
- 小区公共照明的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/w2i
- 家庭环保习惯的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/139=dkl
- 便民服务地图的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/wmr=445
- 数字生活课堂的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/22v=1hq
- 城市绿道建设的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/229
- 线上办事服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/lmm
- 街区更新实践的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/TLl
- 农产品消费体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/428=juu
- 城市生活服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/hbe=058
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/KQi=APF
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/731
- 城市文化路线的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/dsu
- 数字生活课堂的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/qBM
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/889=jqu
- 本地历史资料的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/zdu=390
- 城市绿道建设的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/5Jt=soF
- 社区生活指南的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/318
- 城市博物馆活动的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/vrq
- 老年数字阅读的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/kH9
- 本地历史资料的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/056=ywb
- 社区体育组织的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/kml=202
- 健康步道使用的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/esR=0uT
- 社区老年食堂的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/490
- 公共场所导视的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/lmm
- 社区心理支持的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/2po
- 个人信息保护的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/275=qyu
- 公共服务指南的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/ucz=339
- 城乡公共服务的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/jfQ=y1c
- 社区花园共建的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/927
- 志愿者培训交流的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/ghf
- 城市文化路线的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/5z1
- 物业服务沟通的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/043=zpr
- 数字课堂应用的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/lgn=951
- 环境监测科普的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/gNP=BaE
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/833
- 城市社区治理的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/rjk
- 城市骑行环境的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/VcJ
- 社区花园共建的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/375=ydf
- 家庭环保行动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/phq=989
- 节日文化体验的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/n6T=vMG
- 公共场所导视的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/773
- 应急物资管理的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/fjm
- 社区活动空间的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/0LD
- 基层医疗预约的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/419=bhg
- 农产品品牌传播的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/enx=263
- 无障碍出行中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/dIu=GHr
- 绿色消费选择的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/074
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/xhg
- 城市绿道建设的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/30Y
- 非遗体验活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/583=sng
- 邻里互助活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/xma=239
- 社区庭院绿化的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/8je=mMZ
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/878
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/kpf
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/ydO
- 社区科普课堂的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/538=xyq
- 城市步行环境的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/mdp=328
- 小区电梯维护的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/mgj=HDY
- 数字素养提升的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/227
- 乡村产业科普的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/tjd
- 公共场所导视的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/pB9
- 社区家政服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/024=cph
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/hxw=026
- 公共服务沟通的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/QBJ=uGA
- 社区文化节活动的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/822
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/hci
- 家庭防灾准备的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/WWq
- 家庭环保习惯的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/200=lwc
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/rqi=522
- 小区公共照明中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/OYF=Blu
- 老年人出行服务的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/086
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/iem
- 线上办事服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/JiG
- 劳动教育实践的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/407=zcf
- 城市骑行环境的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/ivg=239
- 公共服务指南的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/irV=piI
- 节约用水实践的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/820
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/log
- 城市公共饮水的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/PL9
- 社区商业活力的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/588=qdb
- 智能手机助老的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/rso=692
- 城市树木认养的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/BcF=T7l
- 社区垃圾分类的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/491
- 城市运动公园的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/egx
- 便民服务窗口的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/3ZG
- 公共服务数字化的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/253=bdf
- 居家适老化改造的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/iza=502
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/tt3=vlt
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/499
- 公共空间安全的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/sol
- 电动汽车充电的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/Pp0
- 邻里共享空间的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/926=kae
- 家庭安全提示的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/vwt=442
- 社区绿色空间的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/HnE=DnA
- 学校食育活动的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/106
- 社区文化传播的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/amz
- 家庭饮食安排的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/BVM
- 城市噪声观察的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/287=yhx
- 乡村公共文化的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zxo=581
- 社区体育组织的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vVr=kay
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/530
- 城市可持续生活的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/oyo
- 社区环保活动的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/gyr
- 社区修缮行动的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/206=xmr
- 社区快递服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/lma=486
- 城市住房服务中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/H4W=PbY
- 家庭环保习惯的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/830
- 城市博物馆活动的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/bau
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/qMR
- 儿童运动体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/497=gbw
- 小区停车协商的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/adg=613
- 城市住房服务的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/6Iy=yTU
- 小微企业服务的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/885
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/xxy
- 环境教育课程的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/E4g
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/778=amp
- 校园节能行动的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/oby=741
- 旧物循环利用的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/6Nw=0x7
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/196
- 城乡交通衔接的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/uub
- 社区宠物管理的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/CXd
- 社区便民集市的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/750=fjd
- 街道综合服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/rmw=452
- 社区垃圾分类的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/YGD=fhp
- 乡村产业科普的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/382
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/yjr
- 数字地图应用的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/6Lt
- 基层服务创新的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/158=dag
- 农业科普体验的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/yvy=435
- 数字课堂应用的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/GZB=WxZ
- 便民服务窗口的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/377
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/yrj
- 城市农夫市集的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/A19
- 便民信息查询的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/051=bny
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/sps=909
- 老年人文化生活中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/CRN=SQS
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/865
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/hin
- 街区更新实践的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/QZ4
- 城市公共自行车的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/696=qdr
- 儿童友好空间的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/hge=914
- 便民服务窗口的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/pmU=B4s
- 老年智能设备的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/565
- 老年运动活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/jfc
- 亲子阅读活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/OSQ
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/872=jrj
- 本地旅行体验的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/gub=815
- 科学信息获取的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/URQ=WKS
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/045
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/elo
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/GpN
- 社区活动策划的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/585=gsb
- 公共卫生宣传的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/tdi=662
- 绿色出行服务的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/jLG=hNy
- 居家适老化改造的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/996
- 电动汽车充电中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/zrq
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/SwS
- 公共空间休憩的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/010=svv
- 基层健康服务的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/vkq=954
- 公共健身器材的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/dsY=LMB
- 青年志愿活动的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/680
- 街区小店体验的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/jfe
- 青少年科技社团的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/Qed
- 科学健身方法的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/930=qkl
- 城市夜间照明的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/nig=003
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/s4J=ZSX
- 社区应急准备的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/210
- 家庭养老规划的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/pvg
- 社区宠物管理的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/9l3
- 社区休闲设施的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/344=ivp
- 公园无障碍服务的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/pyy=922
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/qta=NRc
- 社区家校合作的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/156
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/pst
- 社区手工活动的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/Flu
- 居民健康教育的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/254=gjf
- 城市微更新实践中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/ihq=849
- 老年人出行服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/SOw=TQa
- 家庭科学教育的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/204
- 公共服务预约的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/uus
- 文化讲座服务的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/Ump
- 读书会组织的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/760=hnb
- 社区便民服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/jzc=985
- 城市公共座椅的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/jXA=HZv
- 学校体育活动的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/397
- 公园亲子设施的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/hus
- 社区运动空间的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/WOf
- 社区手工活动的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/211=gkc
- 社区垃圾回收的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/gxc=982
- 城市文明出行的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/6Uc=r1R
- 消防知识宣传的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/321
- 家庭运动计划的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/bzv
- 气象科普传播的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/WD5
- 城市空气科普的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/837=sbs
- 科学观察活动中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/tnn=330
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/mIC=wI7
- 小区停车协商的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/939
- 乡村文化空间的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/vhd
- 消防知识宣传的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/ol4
- 数字设备回收的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/793=kxw
- 城市夜间照明的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/pej=047
- 科普展览体验的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/lby=TbD
- 社区文化传播的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/143
- 家庭照护支持的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/vzm
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/PID
- 居民健康教育的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/760=mwi
- 家庭阅读计划的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/kpv=208
- 家庭园艺实践的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/zIU=EHI
- 城市绿色交通的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/924
- 城市农夫市集的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/lah
- 城市博物馆服务的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/tag
- 光伏知识科普的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/290=doy
- 公共卫生宣传的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/atd=229
- 数字艺术创作的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/aQL=uyG
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/705
- 社区活动空间的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%96%9C%E5%8A%9B%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/ezj

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
