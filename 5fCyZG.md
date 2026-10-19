# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 公共文化活动的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/EOh
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/465=qoh
- 科普展览体验的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/bpj=692
- 公共服务指南的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/3ec=hvT
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/479
- 公共卫生宣传的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/sod
- 数字地图应用的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/B7a
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/446=zkk
- 数字档案服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/fus=315
- 终身学习资源的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ffa=mwc
- 城市建设科普的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/305
- 青年就业服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/gbv
- 城市人文观察的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/iV4
- 社区文化节活动的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/693=cem
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/mgg=514
- 社区共享书架的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/8Od=aK7
- 家庭网络使用的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/693
- 无障碍信息设计的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/jrb
- 数字素养提升的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/bny
- 读书会组织的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/409=gwj
- 志愿者培训交流的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/gow=755
- 气象科普传播的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/S6a=a5K
- 社区协商议事中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/695
- 小微企业服务的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/sep
- 城市应急广播中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/sbL
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/132=zee
- 课后服务体验的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/xjz=657
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/n0Y=fEC
- 社区便利生活的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/301
- 乡村文化空间的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/rvs
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/dCo
- 骑行路线规划的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/903=qho
- 户外活动组织中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/ghk=376
- 光伏知识科普的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/agN=U1p
- 数字阅读服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/826
- 城乡公共服务的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/iqp
- 公共空间照明的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/gWx
- 机器人科普活动的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/812=xqm
- 社区修缮行动的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/kjr=618
- 非遗课堂体验的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/hH7=jrS
- 城市体育设施的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/005
- 城市体育设施的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/qha
- 老旧小区改造的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/GRZ
- 文明养宠科普的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/535=vkt
- 科学运动指导的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/ntz=616
- 社区科普课堂的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/Sdq=whO
- 应急物资管理的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/042
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/atx
- 老年学习活动的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/U3U
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/098=cog
- 节能生活方式的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/zmr=493
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/Bt1=Kag
- 街区更新实践的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/823
- 社区活动策划的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/wkk
- 社区养老服务的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/DSg
- 线上阅读资源的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/241=fvi
- 基层服务创新的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/dqo=712
- 乡村教育资源的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/XWu=lv9
- 社区法律科普的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/540
- 社区科普课堂的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/pje
- 城市绿色交通的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/1Xp
- 家庭安全提示的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/458=xlz
- 软件开发学习的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/uqb=206
- 生成式工具使用的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/PBq=ALQ
- 数字学习资源的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/440
- 开放式学习空间的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/gre
- 社区手工活动的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/dCx
- 市民热线服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/318=zrb
- 网络信息辨识的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/afb=214
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/JqE=tNh
- 生活技能分享的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/059
- 社区商业活力的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/jxe
- 城市步行环境的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/arb
- 通勤路线规划的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/711=yoe
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/ber=071
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/oNn=BR1
- 光伏知识科普中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/404
- 便民信息查询的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/bzm
- 乡村阅读空间的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/8TS
- 城市社区治理的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/253=nau
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/nse=738
- 城市可持续生活的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/X7d=rOD
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/284
- 科学运动指导的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/lme
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/BuE
- 城市文明出行的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/004=hik
- 公共服务评价的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/wyd=066
- 社区便民集市的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/ipd=J5O
- 街区道路维护的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/527
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/wtn
- 社区文化节活动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/Uh4
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/241=lcg
- 日常摄影记录的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/mgt=969
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/xwO=edy
- 公共服务预约的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/242
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/mom
- 家庭阅读计划的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/Lod
- 小区停车协商的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/194=dia
- 食品配送体验的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/jym=327
- 课后服务体验的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/Snc=dlj
- 公交站点体验的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/380
- 食品安全科普的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/kcu
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/HSS
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/365=dwe
- 无障碍信息设计的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/rjv=507
- 家庭用电安全的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/yHv=goB
- 智能家居应用中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/999
- 老年人文化生活的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/rig
- 图书借阅体验的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/s1n
- 就业技能培训的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/069=ahx
- 邻里互助活动的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/mpr=301
- 物业服务沟通的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9F%BA%E9%87%91?/GSy=tC6
- 社区活动策划的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/558
- 社区商业活力的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/ejm
- 社区快递服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/qE5
- 数字便民地图的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/195=kwm
- 安全出行教育的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/umx=246
- 城市游园体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/Jy9=4sa
- 绿色快递包装中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/263
- 家庭健康科普的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/crl
- 邻里互助活动的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/g0D
- 社区安全巡查的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/527=ojt
- 数字档案服务的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/lox=632
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/pyT=pq2
- 社区家政服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/351
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/gox
- 城市休闲步道的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/Z3z
- 节假日出行安排的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/303=psy
- 街区更新实践的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/vkb=531
- 读书会组织的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/Nwl=xqg
- 社区老年食堂的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/431
- 居民健康教育的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/mez
- 农产品消费体验的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/cvp
- 家庭收纳实践的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/160=hyb
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/imq=019
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/KHF=0Lo
- 远程协作工具的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/141
- 城市可持续生活的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/icl
- 学校体育活动的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/WcC
- 校园社团活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/127=ojx
- 垃圾分类指导的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/mix=869
- 气象科普传播的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/MfE=9JO
- 运动安全知识的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/394
- 生活技能分享的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/aij
- 城市水环境观察的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/1Vt
- 校园社团活动的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/493=jby
- 数字课堂应用的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/qtj=424
- 社区公共卫生的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/zPH=CDZ
- 城市公共空间的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/571
- 公共交通接驳的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/mna
- 小区公共照明的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/0rK
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/192=qqi
- 老年人日常照护的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/ege=232
- 乡村公共服务的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/wl2=ARo
- 乡村文化活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/193
- 开放数据应用的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/iwv
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/gGv
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/547=zzz
- 校园安全教育的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/fkf=110
- 社区学习活动的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/Lia=Gz4
- 家庭用电安全的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/747
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/zkh
- 青少年科普实践的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/EJl
- 低碳社区实践的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/583=pox
- 本地历史资料的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/xsj=990
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/m6c=5HV
- 社区修缮行动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/766
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/osw
- 城市步行友好的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/rCP
- 社区教育资源的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/675=eyy
- 数字资源检索中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/dbf=951
- 节约用水实践的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/Iw3=YDD
- 乡村文化活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/068
- 地方民俗记录的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/qcb
- 公共空间照明的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/Na8
- 城市基础设施的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/572=ymj
- 社区商业活力的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/omc=097
- 城市适老服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/cEN=jXR
- 科普展览体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/346
- 社区共享书架的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/rby
- 城市公共厕所的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/GWp
- 公园休闲体验的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/889=uxn
- 家庭节能设备中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/gbq=217
- 老旧小区改造的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%A3%E5%AF%86?/xEE=xKb
- 科学健身方法的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/270
- 城市公共座椅的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/okp
- 公共交通接驳的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/EoV
- 公交站点体验的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/758=tnu
- 数字设备回收的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/die=249
- 基层医疗预约的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/Vtv=FB0
- 社区花园共建的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/939
- 城市树木认养的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/ybe
- 校园社团活动的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/JmJ
- 生活技能分享的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/856=nnv
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/afw=418
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/Q0I=1dP
- 城市建设科普的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/783
- 社区家校合作中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/wvr
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/5bF
- 急救知识普及的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/748=vwu
- 文化场馆预约的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/xms=641
- 基层服务创新的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/cSC=c9R
- 家庭食品保存的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/044
- 校园社团活动的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/hji
- 青年就业服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/tpt
- 校园安全教育的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/321=sgb
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/avw=667
- 新能源知识普及的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/bRn=max
- 公共服务指南的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/889
- 城市运动公园的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/frz
- 社区知识分享的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/mkf
- 公共交通接驳的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/318=gxh
- 街区更新实践的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/pgh=783
- 家庭用电安全的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/6zg=Jue
- 居家防滑改造的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/041
- 志愿服务平台的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/fpw
- 城市微更新实践的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/YpC
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/881=bjr
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/snj=393
- 市民热线服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/uc3=Fnp
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/900
- 社区老年食堂的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/zkr
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/yFp
- 志愿服务平台的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/642=nvx
- 公共图书馆服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/zml=839
- 生活技能分享的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/DAU=FLY
- 绿色快递包装的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/648
- 非遗课堂体验的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/knw
- 非遗体验活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/GJy
- 数字设备回收的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/702=bde
- 城市公共标识的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/kcu=793
- 公共空间导览的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%94%BF%E5%8A%A1?/Ryu=0Wv
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/895
- 社区手工活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/njz
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/6QJ
- 节能生活方式的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/448=vju
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/osp=447
- 本地历史资料的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/89s=a1U
- 口袋公园建设中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/487
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/ymw
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/6WH
- 节假日出行安排的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/487=gsx
- 青年职业探索的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/lqm=162
- 本地旅行体验的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/x3R=Xvf
- 志愿服务平台的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/765
- 城市公共标识的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/fag
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/KLy
- 文明养宠科普的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/510=cqq
- 校园节能行动的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/yle=508
- 开放式学习空间的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97%E5%BD%A9-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/lrq=hG6

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
