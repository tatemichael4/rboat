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

- 家庭园艺实践的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/763
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/ewa
- 消防知识宣传的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/0TZ
- 城市住房服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/797=xjj
- 乡村电商实践的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/oqq=129
- 社区手工活动的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/IdI=jDL
- 家庭消费规划的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/794
- 社区体育组织的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/rug
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/aq5
- 科普展览体验的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/055=cui
- 居家防滑改造的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/nwq=583
- 公园亲子设施的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/T5c=YiR
- 老年数字阅读的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/174
- 城市空气科普的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/jox
- 小区公共照明的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/vWE
- 城市游园体验的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/662=vau
- 社区健康讲座的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/ibh=618
- 街道综合服务的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/H2X=wZf
- 城乡交流活动的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/516
- 智能家居应用的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/qdl
- 城市应急广播的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/4Gf
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/176=ydw
- 无障碍信息设计的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/fnk=958
- 城市雨天出行的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/qDw=hr2
- 无障碍出行的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/759
- 基层健康服务的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/qkd
- 城市公共厕所的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/9xk
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/097=yaf
- 数字生活课堂的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/jaw=226
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%AF%8D%E5%A9%B4?/UcU=Iwi
- 社区手工活动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/815
- 全民健身活动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xho
- 生活技能分享的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/qk3
- 社区便民服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/854=vmb
- 公共服务沟通的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/bnk=982
- 数字档案服务的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xEo=owq
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/279
- 城市文明实践的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/bmh
- 消防知识宣传的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/9NK
- 青少年心理健康的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/921=flb
- 家庭安全提示的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/bcb=246
- 社区协商议事的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/LJJ=QWE
- 科学运动指导的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/348
- 生活垃圾回收的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/xjv
- 社区阅读服务的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/YnJ
- 青年就业服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/805=ymz
- 城市可持续生活的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/rcr=627
- 旧物循环利用中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/q4y=Yo1
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/100
- 无障碍信息设计的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/ipo
- 健康步道使用中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/Ra1
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/714=nkt
- 城市展览体验的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/pwo=629
- 社区老年食堂的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/YAw=VnH
- 公共服务沟通的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/189
- 社区修缮行动的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/wxe
- 小区公共照明的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/LmJ
- 社区协商议事的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/909=mpd
- 城市展览体验的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/hls=616
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/09l=fLK
- 城市展览体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/767
- 全民阅读推广的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/haj
- 课后服务体验的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/gbS
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/195=ntv
- 乡村公共服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/axh=364
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/UmB=mzq
- 社区活动策划的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/052
- 物业服务沟通的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/wfh
- 通勤路线规划的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/yuZ
- 家庭饮食安排的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/645=qsm
- 街区更新实践的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/zed=855
- 社区安全巡查的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/yBH=r39
- 城市空气科普的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/404
- 城市社区治理的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/tbm
- 城市生活记录的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/MiG
- 学校体育活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/254=uur
- 家庭收纳实践的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/nfm=115
- 开放数据应用的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/4cJ=56H
- 在线教育体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/616
- 线上阅读资源的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/wzv
- 家庭运动计划的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/uOK
- 家庭急救准备的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/204=tsm
- 社区停车服务的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/goj=341
- 光伏知识科普的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%80%9F%E8%A7%88?/Equ=oDD
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/563
- 城市公共厕所的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/xvp
- 老旧小区改造的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/TQY
- 灵活就业交流的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/434=xnv
- 居民健康教育的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/git=289
- 老年学习活动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/dcX=UkA
- 公共场馆服务的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/368
- 地方文化传播的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/mva
- 物业服务沟通的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/Hkf
- 社区商业活力的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/312=kva
- 数字档案服务的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/xqc=435
- 儿童户外活动的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/AWU=dpQ
- 电动汽车充电的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/639
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/ehd
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/ZBK
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/498=udx
- 旧物循环利用的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/gle=153
- 光伏知识科普的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/HQ1=aQ1
- 青少年户外教育的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/540
- 家庭养老规划的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/boy
- 社区生活指南的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/2x5
- 健康饮水科普的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/740=nem
- 家庭防灾准备的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/zjd=369
- 社区健康讲座的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/9KN=ZJ2
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/772
- 城乡交流活动的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/mpp
- 小区电梯维护的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/Udh
- 社区邻里服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/854=mvn
- 亲子阅读活动的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/pxy=794
- 乡村产业科普的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/RdE=mXZ
- 地方旅游导览的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/615
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/kwy
- 社区科普课堂的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/AJW
- 社区法律科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/686=gfx
- 社区庭院绿化的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/irt=978
- 医院导诊服务的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/lCE=eeQ
- 家庭收纳实践的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/869
- 乡村公共服务的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/awk
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/8dL
- 家庭急救准备的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/518=qvc
- 城市公共标识的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/svw=944
- 线上办事服务的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/jmy=Kvb
- 社区科普课堂的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/308
- 生活垃圾减量的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/ayv
- 公共图书馆服务的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/S76
- 儿童友好空间的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/406=yvb
- 地方美食文化的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/bhi=748
- 家庭运动计划的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%84%E8%AE%BA?/Y8A=Ec6
- 数字阅读服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/358
- 数字地图应用的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/lhr
- 青年就业服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/n4c
- 城市空气科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/738=zwe
- 街区更新实践的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/ovp=079
- 基层服务创新的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/sEt=MVV
- 城市便民驿站的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/972
- 电子商务服务的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/jul
- 老年数字阅读的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/ZuK
- 城市社区治理的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/939=bjb
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/qcc=296
- 社区知识分享的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/CsL=eTm
- 家庭环保行动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/731
- 家庭防灾准备的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/qey
- 科普展览体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/q9r
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/512=gvg
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/dpd=490
- 社区垃圾分类的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/ccP=07A
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/929
- 数字公共文化的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/qqn
- 校园社团活动的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/4Gd
- 社区生活指南中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/773=ujw
- 食品安全科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/iwq=356
- 社区体育组织的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/ePv=PBT
- 科学运动指导的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/350
- 本地旅行体验的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/yyv
- 家庭安全提示的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/QcT
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/765=ssc
- 应急物资管理的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/urf=983
- 社区共享书架的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/kzm=Yee
- 城市步行友好的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/057
- 城市绿色交通的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/lru
- 青少年科普实践的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/YrO
- 传统手工艺体验的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/634=hjc
- 本地历史资料的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/keb=399
- 城市生活服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/W28=8qs
- 社区体育组织的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/265
- 公共卫生宣传的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/twk
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/QMY
- 社区手工活动的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/244=skw
- 地方美食文化的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/xkv=264
- 老年运动活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/5y5=KY0
- 骑行路线规划的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/276
- 科学教育活动的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/prl
- 家庭健康科普的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/c5m
- 口袋公园建设的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/007=pag
- 社区邻里服务的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/eag=824
- 环境教育课程的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/eCC=0df
- 休闲运动入门的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/827
- 个人时间管理的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/zmi
- 绿色建筑理念的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/50L
- 公交站点体验的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/854=fse
- 志愿服务平台的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/vkd=796
- 公共服务沟通的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/Wxi=yjF
- 公园亲子设施的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/233
- 家庭健康管理的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/kio
- 家庭用电安全的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/Eyw
- 全民阅读推广的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/409=fcj
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/pxn=781
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/aWX=H97
- 老年运动活动的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/095
- 开放式学习空间的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/yzu
- 人工智能科普的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/RQ1
- 生活服务数字化的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/112=yre
- 老年友好服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/wcv=443
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/Msr=JNy
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/987
- 网络信息辨识的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/pee
- 社区休闲设施的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/C9A
- 公共卫生设施的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/379=wmh
- 基层医疗预约中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/jns=253
- 社区体育组织的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/Heq=i7S
- 传统节日科普的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/892
- 地方文化传播的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/ukd
- 青少年科普实践中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/GbJ
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/773=ltc
- 公交站点体验的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/mdb=392
- 儿童友好街区的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/CIM=Ms9
- 节日文化体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/873
- 社区活动策划的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cxc
- 志愿者培训交流的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/ODj
- 城市共享单车的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/135=dym
- 节能家电使用的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/tpk=800
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/VYB=eFK
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/510
- 城市社区治理的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/bvh
- 邻里共享空间的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/8eJ
- 乡村电商实践的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/391=ibr
- 社区共享书架的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/cfw=047
- 口袋公园建设的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/cIB=ae3
- 数字艺术创作的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/957
- 老年人日常照护的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/yfj
- 农产品品牌传播的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/LK9
- 家庭安全提示的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/279=pev
- 乡村阅读空间的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/gvb=358
- 农业科普体验的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/mCg=s0D
- 社区公共卫生的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/414
- 城市住房服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/rdh
- 社区文化传播的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/ODM
- 非遗体验活动的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/394=sje
- 城市适老服务的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/gmb=976
- 城市住房服务的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/PKn=qgz
- 老年数字阅读的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/420
- 本地消费场景的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/zox
- 健康信息获取的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/1X0
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/500=zrf
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/snq=827
- 老年人文化生活的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/YjP=hC9
- 儿童户外活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/705
- 农业科普体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/gdr
- 垃圾分类指导的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/fvP
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/310=kst
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/jkp=980
- 数字档案服务的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/LVn=yei
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/398
- 居家适老化改造的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/uci
- 绿色生活实践的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/Vut
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/597=oma

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
