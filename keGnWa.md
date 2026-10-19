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

- 社区公共餐饮的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/yDL
- 家庭理财科普的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/653=wzl
- 旧物循环利用的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/duw=125
- 社区教育资源的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/clq=inX
- 农村环境治理的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/725
- 老年学习活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/mom
- 科学健身方法中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/X1E
- 社区商业活力的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/431=jfd
- 公园休闲体验的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/qih=059
- 城市共享单车的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/7ce=TIT
- 灵活就业交流的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/093
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/jge
- 科学健身方法的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/JXX
- 街区道路维护的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/765=zda
- 社区绿色空间的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/lcn=172
- 社区互助网络的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/ZKM=bEn
- 劳动教育实践的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/207
- 社区互助网络的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/cru
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/PcE
- 社区修缮行动的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/039=ocb
- 读书会组织的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/bzq=241
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/qQO=ahJ
- 社区庭院绿化的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/410
- 环境教育课程中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/nrr
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/mRO
- 城市公共座椅的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/403=jwf
- 乡村教育资源的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/sae=813
- 城市夜间照明中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/aY9=36Q
- 软件开发学习的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/203
- 劳动教育实践的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/sdg
- 消防知识宣传的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/Mqo
- 家庭健康管理的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/008=hhi
- 节假日出行安排的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/cpk=615
- 公共设施维护的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/y91=qAs
- 城市文明实践的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/371
- 基层健康档案中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/jni
- 城市文明实践的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/tkT
- 绿色办公实践的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/822=koa
- 学校食育活动的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/cat=443
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/m7j=pdv
- 科学健身方法的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/245
- 传统手工艺体验的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/xlz
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/CA8
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/810=osr
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/izt=378
- 机器人科普活动的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/dzB=xxX
- 小区停车协商的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/714
- 公共服务沟通的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/glt
- 社区修缮行动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/s3f
- 个人数据管理的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/039=sfr
- 城市共享单车的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/mwi=756
- 小区停车协商的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/LBV=aF0
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/260
- 城市游园体验的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/kzv
- 学校食育活动的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/Tqe
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/698=uki
- 街区小店体验的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/ble=052
- 家庭急救准备的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/WrJ=1Ic
- 家庭环保行动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/154
- 本地旅行体验的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/bus
- 家庭饮食安排的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/Whg
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/264=wkc
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/dvh=034
- 图书借阅体验的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/lQe=FWh
- 家庭收纳实践的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/048
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/anf
- 城市住房服务的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/I5a
- 数字档案服务的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/885=jax
- 传统节日科普的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/aus=960
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%81%8C%E5%9C%BA?/TeG=te6
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/914
- 小区停车协商的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/ims
- 非遗体验活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/vjm
- 数字素养提升的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/042=wkr
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/wyx=216
- 公共服务数字化的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/rYR=WLO
- 城市应急广播的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/471
- 老年人日常照护的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/stg
- 数字学习资源的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/f8v
- 城市运动公园的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/974=qso
- 社区学习活动的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/wif=732
- 农产品消费体验的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/Rnj=h1L
- 节日文化体验的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/782
- 健康信息获取的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/hpu
- 数字创作工具的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/d5I
- 家庭运动计划的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/641=ugp
- 本地历史资料的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/fhw=569
- 城市应急科普的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/Jfp=BcD
- 绿色办公实践的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/809
- 就业技能培训的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/dpe
- 街头绿植养护的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/cZq
- 校园社团活动中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/365=gjh
- 健康步道使用的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/plj=073
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/WeA=pxD
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/375
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/ylz
- 社区商业活力的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/bqn
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/537=xam
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/loj=824
- 租房信息服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/2ds=YdK
- 校园社团活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/076
- 城市公共艺术的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/ctm
- 城市慢行系统的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/9fj
- 就业技能培训的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/654=wtx
- 校园阅读活动的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/liu=788
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/Hfg=V1R
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/378
- 乡村公共文化的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/rge
- 家庭节能实践的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/BKz
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/115=eoc
- 城市建设科普的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/isc=688
- 终身学习资源的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/IFK=Iym
- 绿色校园实践中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/119
- 社区宠物管理的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/yno
- 数字支付体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/zrl
- 数字便民地图的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/150=pug
- 科学运动指导的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/vcy=983
- 地方旅游导览的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/cZV=ugf
- 公共场所导视的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/229
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/kab
- 数字艺术创作中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/OG6
- 科学信息获取的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/874=myc
- 家庭安全提示的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/tif=143
- 智能手机助老的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/QAh=iLT
- 社区协商议事的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/024
- 公益活动组织的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/ure
- 社区艺术活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/syP
- 通勤路线规划的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/338=qka
- 线上办事服务的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/qiu=743
- 食品配送体验的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/lOA=JCL
- 街头绿植养护的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/434
- 儿童友好街区的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/cgz
- 老年学习活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/DlU
- 儿童阅读角的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/439=azf
- 公共服务评价的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/ato=984
- 城市适老服务的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/hvc=rlh
- 绿色生活实践的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/726
- 数字课堂应用的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/hpi
- 城乡交流活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/uKz
- 数字支付体验的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/833=rxq
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/vlt=760
- 社区儿童活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/wQa=exM
- 家庭用电安全中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/448
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/lcy
- 城市夜间照明的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/utv
- 在线教育体验中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/183=szf
- 公共服务沟通的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/hrb=621
- 社区停车服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/T0l=mX6
- 青少年科技社团的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/754
- 儿童阅读角的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/wtc
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/Pjk
- 读书会组织的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/260=nvq
- 数字学习资源的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/lwp=008
- 数字阅读服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/z32=lFu
- 城市树木认养的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/492
- 家庭环保行动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/vxv
- 绿色校园实践的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/Xgy
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/603=gpp
- 本地消费场景的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/fvn=944
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/B3U=cRS
- 健康饮水科普的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/829
- 社区应急准备的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/xst
- 社区商业活力的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/1Jm
- 小微企业服务的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/350=zgu
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/dge=655
- 青年职业探索的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/z4F=jP0
- 小区停车协商的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/939
- 乡村公共文化的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/oii
- 地方文化传播的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/dKj
- 社区邻里服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/377=dex
- 社区公共议事的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/dom=982
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/Des=ARJ
- 地方美食文化的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/208
- 科学观察活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/mor
- 社区家政服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/tGI
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/106=pcd
- 城乡公共服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/bwb=879
- 社区共享书架的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/yIY=Bro
- 社区公共议事的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/259
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/wqy
- 家庭急救准备的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/9WB
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/088=rcy
- 社区知识分享的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/ryc=256
- 市民意见收集的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/RjO=SD6
- 数字便民地图的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/534
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/xsc
- 社区共享书架的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/pyY
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/417=yvt
- 物业服务沟通的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/ajq=574
- 健康饮水科普中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/ef0=dde
- 青年志愿活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/891
- 儿童运动体验的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/vcz
- 公共服务咨询的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/j4x
- 数字素养提升的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/726=pub
- 数字创意课程的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/zmf=663
- 户外活动组织的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/SvL=dda
- 农产品消费体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/372
- 公共卫生设施的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/inn
- 智慧城市体验的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/Zv6
- 周末休闲规划的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/997=rac
- 社区健康讲座的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/skv=662
- 城市噪声观察的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/kbK=iiG
- 城市树木认养的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/402
- 健康信息获取的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/gpv
- 软件开发学习的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/7M1
- 城市文化路线的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/533=wmc
- 地方戏曲体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/rni=544
- 节日文化体验的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/Ckj=FOE
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/960
- 学校体育活动的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/qxj
- 本地历史资料的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/BAJ
- 农产品消费体验的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/266=wvx
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/zwx=501
- 数字档案服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/SiJ=les
- 社区便民服务的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/653
- 城市休闲步道的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/itj
- 图书馆活动策划的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/JnR
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/868=xlz
- 本地旅行体验的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/rah=388
- 社区读书角建设的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/WyQ=yKU
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/945
- 城市步行友好的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ncm
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/wK4
- 数字创意课程的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/741=bgb
- 城市适老服务的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/gmx=785
- 绿色校园实践的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/MXN=QL3
- 公共服务预约的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/877
- 乡村公共文化中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/nlc
- 老年学习活动的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/vg5
- 公共图书馆服务的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/270=lqy
- 社区共享书架的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/mra=372
- 社区环保活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%AE%BF%E8%B0%88?/3PG=HBn
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/224
- 城市运动公园的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/ctg
- 社区老年食堂的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/kaK
- 公交站点体验的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/171=deu
- 新能源知识普及的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/skg=547
- 居家防滑改造的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/Hl4=gEC
- 低碳社区实践的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/783
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/mvo
- 青少年科普实践的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/FV8
- 线上办事服务中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/520=qga
- 社区生活指南的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/tti=600
- 生成式工具使用的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/WxP=LAN
- 智能手机助老的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/390
- 老年人出行服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/jgz
- 居民健康教育的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/vVJ
- 公共场所导视的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/527=ozk
- 创业经验分享的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/jpo=489
- 社区运动空间的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/TeY=hk3

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
