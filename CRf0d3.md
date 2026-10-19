# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 周末休闲规划的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/lUY
- 人工智能科普的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/175=xfo
- 市民热线服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/kqi=592
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/A2Y=jxp
- 社区消防演练的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/232
- 青年就业服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/hlu
- 城市游园体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/pjN
- 数字学习资源的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/223=bzv
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/hvl=723
- 城市展览体验的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/Zi0=bem
- 非遗体验活动的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/544
- 家庭用电安全的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/idv
- 志愿者培训交流的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/A9P
- 农贸市场环境的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/091=srf
- 公共空间安全的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/zky=638
- 老年人文化生活的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/IL9=8Ob
- 社区防暑服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/260
- 科学信息获取的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/dfl
- 新能源出行的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/SKG
- 社区文化节活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/304=afz
- 儿童户外活动中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/ysh=657
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/N9p=7cd
- 社区知识分享的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/924
- 家庭食品保存的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/chm
- 电动汽车充电的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/xAu
- 医院导诊服务的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/987=pis
- 乡村生活观察的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/wzn=062
- 社区快递服务的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8D%8F?/XeY=oUy
- 城市文化路线的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/192
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/yth
- 城市公共饮水的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/D1G
- 旧物循环利用的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/100=vmk
- 社区休闲设施的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/ucx=902
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/CJZ=KZc
- 居家防滑改造的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/800
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/feb
- 数字课堂应用的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/F3D
- 社区儿童活动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/570=kyp
- 职业技能学习的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/iuy=265
- 城市应急广播的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/Im8=Crl
- 社区宠物管理中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/007
- 机器学习入门的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/vpv
- 社区科普课堂的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/IjS
- 社区修缮行动的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/399=gep
- 便民服务窗口的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/wwc=670
- 公共场所导视的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/JD8=2Ia
- 公共卫生设施的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/495
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/yiq
- 城市公共标识的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/r8h
- 本地历史资料的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/756=cvt
- 街道综合服务的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/mcg=877
- 街区道路维护的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/dSK=OZ0
- 环境监测科普的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/802
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/azc
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/tWd
- 城市公共饮水的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/608=rlz
- 家庭收纳实践的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/rjl=657
- 城市微更新实践的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/AO4=PK7
- 家庭消费规划的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/742
- 数字艺术创作的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/soz
- 日常摄影记录的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/b3u
- 居家防滑改造的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/322=ryr
- 课后服务体验的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/hkl=376
- 绿色消费选择的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/Vk2=cLa
- 物业服务沟通的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/655
- 健康步道使用的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/oav
- 信息无障碍体验的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/w7N
- 城市运动公园的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/752=utf
- 读书会组织的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/urx=636
- 城市公共饮水的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/Kcj=yDf
- 智能家居应用的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/941
- 急救知识普及的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/nxo
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/eau
- 节能生活方式的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/971=mpb
- 环境教育课程的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/jht=478
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/c2d=KZN
- 公共服务指南的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/043
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/bij
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/QOf
- 志愿服务平台的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/271=utb
- 乡村生态观察的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/mmn=594
- 节约用水实践的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/wmW=ldq
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/561
- 社区邻里服务的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hvk
- 生成式工具使用的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pz8
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/522=arx
- 城市绿色交通的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ngo=129
- 家庭急救准备的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/S5Y=yH2
- 家庭节能设备的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/820
- 科技馆参观体验的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/vue
- 社区消防演练的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/tBd
- 城乡公共服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/607=rmy
- 公共交通信息服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/cro=354
- 城市文化路线的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/CpQ=8V6
- 食品配送体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/093
- 城市运动公园的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/rxf
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/w9z
- 家庭教育交流的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/314=zee
- 青少年科技社团的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wyy=180
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/eB3=cmF
- 家庭环保行动的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/148
- 城市水环境观察的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/yqa
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/m1z
- 小区电梯维护的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/907=mmo
- 环境教育课程的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/scm=777
- 节假日出行安排的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/LSE=M7G
- 社区儿童活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/012
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/anr
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/GlI
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/639=ujg
- 老年人日常照护的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/icy=088
- 街道综合服务的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/4HQ=hZ3
- 街头绿植养护的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/626
- 小区停车协商的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/rwq
- 健康步道使用的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/pFp
- 城市文明实践的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/978=hoc
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/gse=809
- 乡村公共文化中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/R2K=X2y
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/578
- 数字政务体验的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/pwr
- 机器学习入门的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/fpp
- 气象科普传播的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/189=rxc
- 就业技能培训的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/lay=434
- 校园社团活动的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/YgF=a0q
- 数字课堂应用的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/145
- 城市步行环境的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/jbz
- 街区小店体验的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/LQl
- 农业科普体验的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/357=epi
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/iio=279
- 街道综合服务的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/1JV=7L2
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/140
- 公共场馆服务的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/stl
- 公共空间安全的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/Hub
- 社区垃圾回收的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/523=shn
- 节约用水实践的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/gqv=114
- 社区公共餐饮的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/FV2=bsr
- 居民健康教育的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/103
- 家庭网络使用的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/nur
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/gEx
- 青少年心理健康的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/632=fsu
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/bfj=601
- 灵活就业交流的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/Gss=FD6
- 小区公共照明的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/675
- 社区家政服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/qso
- 社区宠物管理的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/BEX
- 社区学习活动的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/436=qwl
- 居家防滑改造的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/nic=488
- 图书馆活动策划的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/4cu=Yb8
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/876
- 公共空间导览的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/fjw
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/IEq
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/776=ajd
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/ueg=248
- 家庭环保习惯的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/9ek=w1n
- 环境教育课程的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/145
- 垃圾分类指导的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/ezd
- 地方文化传播的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/MyV
- 农贸市场环境的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/584=dch
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/wwn=568
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%88%B7%E5%A4%96?/tHz=kfK
- 社区商业活力的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/918
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/voa
- 数字阅读服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/DDI
- 食品配送体验的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/589=xlv
- 科学教育活动的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/vwb=544
- 节日文化体验的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/sia=8We
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/900
- 本地消费场景的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/zwl
- 社区应急准备的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/fV9
- 地方民俗记录的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/322=ozp
- 街区绿化养护的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/bni=976
- 安全出行教育的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/zB3=LyO
- 社区宠物管理的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/173
- 食品安全科普的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/tlq
- 生活服务数字化的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/4FG
- 城市公共自行车的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/194=ueg
- 社区故事采集的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/hgh=062
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/Nx1=P4n
- 社区互助网络的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/159
- 地方戏曲体验的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/vpt
- 社区健康讲座的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/Ma7
- 全民阅读推广的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/225=cjt
- 儿童运动体验中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/tbk=308
- 城市基础设施的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/hmw=qh8
- 社会体育指导的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/215
- 文化讲座服务的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/oly
- 城市便民驿站的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/0L0
- 家庭网络使用的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/098=aau
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/tes=565
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/cx7=J2h
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/193
- 基层健康服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/zcc
- 校园阅读活动的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/HPH
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/895=kgv
- 数字公共文化的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/jfa=462
- 数字艺术创作的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/goe=CJt
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/423
- 科学信息获取的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/vin
- 乡村阅读空间的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/V3H
- 全民阅读推广的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/408=hbo
- 数字便民地图的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/vhz=048
- 骑行路线规划的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/kbi=2RQ
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/396
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/vvf
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/dky
- 社区便利生活的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/319=xxy
- 乡村公共文化的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/nzw=580
- 城市文明出行的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/k4Q=Tlj
- 校园阅读活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/094
- 便民服务窗口的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/iot
- 非遗体验活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/i7m
- 城市步行友好的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/757=ywa
- 公共空间休憩的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/hjz=041
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/Elx=2NO
- 电子商务服务的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/441
- 社区便利生活的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/ser
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/TYl
- 社区公共卫生的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/713=jrl
- 数字支付体验的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/xle=929
- 公益活动组织的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/7Xx=iOv
- 社区垃圾分类的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/487
- 旧物循环利用的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/zxv
- 街区小店体验的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/RO3
- 公共空间导览的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/007=pol
- 老年人出行服务的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/cvj=911
- 运动安全知识的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E7%89%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/3DJ=S0v
- 社区互助网络的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/057
- 城市游园体验的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/mst
- 学校体育活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/sho
- 社区老年食堂的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/740=wku
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/ehx=475
- 城市文明出行的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%A4%A7%E5%8E%852025_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%A3%9F%E5%93%81?/6TK=aT9
- 城市农夫市集的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/031
- 节能家电使用的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/jpu
- 老年友好服务的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/viv
- 数字资源检索的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/192=xbk
- 数字便民地图的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/fho=626
- 青少年科技社团的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/y7P=igC
- 志愿服务平台的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/926
- 环境教育课程的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/vhx
- 社区儿童活动的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/vB2
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/945=yjb
- 乡村文化活动的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/xbd=227
- 社区阅读服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/2Zs=8hp
- 基层医疗预约的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/174
- 基层健康服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/qqc
- 数字课堂应用的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/GgY
- 急救知识普及的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/956=xrw
- 社区花园共建的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/aai=448
- 学校体育活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E4%B9%90%E9%80%8F78500%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/dYf=vC1

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
