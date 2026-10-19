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

- 数字支付体验的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/MNc
- 无障碍出行的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/011=dnb
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/auo=861
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/f9o=cHd
- 城市步行环境的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/390
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/foo
- 社区慢性病防控的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/Y8e
- 老年人日常照护的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/699=sgb
- 绿色快递包装中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/yrr=237
- 乡村公共文化的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/oh4=F0P
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/299
- 软件开发学习中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/yzk
- 地方文化传播的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/NlZ
- 家庭安全提示的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/839=dsu
- 城市可持续生活的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/uop=922
- 个人时间管理的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/fdo=S9Z
- 环境监测科普的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/382
- 邻里共享空间的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/emw
- 街区道路维护的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/BIM
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/146=utu
- 城市慢行系统的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/jtw=947
- 科普展览体验的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/w03=qa0
- 家庭健康管理的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/726
- 公共图书馆服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/qti
- 城市公共标识的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/TZm
- 城市适老服务的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/612=ifv
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/eau=295
- 开源技术交流的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/LHk=b1U
- 志愿者培训交流的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/995
- 居家适老化改造的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/laq
- 生活服务数字化的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/8XT
- 绿色消费选择中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/117=gni
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/gfm=404
- 环境教育课程的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%90%8D%E8%B4%AF-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/Z2c=tuX
- 志愿服务平台的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/022
- 街区更新实践的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/vtq
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/RxW
- 城市夜间生活的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/889=jow
- 农村环境治理的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/fbw=629
- 邻里互助活动的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%90%8D%E8%B4%AF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/kiz=dJj
- 旧物循环利用的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/337
- 医院导诊服务的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/vch
- 社区邻里服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/Ig3
- 校园阅读活动的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/453=nzv
- 街区更新实践的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/yqe=711
- 乡村文化空间的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/2E0=hpR
- 科技馆参观体验的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/339
- 居家适老化改造中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/yyp
- 校园安全教育的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/lTT
- 社区家校合作的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/613=mjd
- 图书借阅体验的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/cvo=236
- 城市应急广播的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%90%8D%E8%B4%AF-APP_%E6%90%9C%E7%8B%90%E5%9C%B0%E4%BA%A7?/bBb=j7M
- 电动汽车充电中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/075
- 社区防暑服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/nkg
- 公共服务评价的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/t5y
- 社区运动空间的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/901=cou
- 数字支付体验的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/tng=437
- 社区体育组织的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/NYk=yqX
- 无障碍出行的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/278
- 社区便民服务的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/lra
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/vlH
- 科学信息获取的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/677=psf
- 城市文明出行的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/kde=812
- 公交无障碍服务的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/LXq=mQo
- 在线教育体验的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/242
- 社会体育指导的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/pya
- 公共场所导视的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/XZv
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/917=cjl
- 社区应急准备的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/hhk=080
- 社区便民集市的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/fvN=wT3
- 社区学习活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/767
- 城乡公共服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/gbh
- 城市便民驿站的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/Itz
- 生成式工具使用的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/257=pmc
- 安全出行教育的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/ndw=113
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-%E6%B3%A8%E5%86%8C_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/HQz=qga
- 数字艺术创作中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/634
- 生活技能分享的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/gus
- 城市公共空间的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/WWw
- 城市建设科普的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/252=iue
- 城市生活服务的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/vkh=934
- 农村环境治理的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/DQj=haj
- 志愿服务平台的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/817
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/pdi
- 青少年心理健康的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/8HP
- 社区慢性病防控的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/522=pkj
- 数字生活课堂的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/svb=279
- 网络安全教育的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%90%8D%E8%B4%AF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/uMn=SaE
- 家庭健康科普的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/484
- 数字地图应用的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/gbv
- 地方美食文化的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/NLi
- 生活服务数字化中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/174=ugw
- 社区心理支持的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/tbb=499
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/QI0=t1r
- 社区科普课堂的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/453
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/gva
- 社区家政服务的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/04B
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/879=ynm
- 社区垃圾回收的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/one=197
- 科普展览体验的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/n8U=d4I
- 远程协作工具的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/172
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/nev
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/g96
- 学校食育活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/731=nce
- 节气饮食文化的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/tzo=676
- 数字资源检索的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/uBE=ZLl
- 公共空间安全的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/017
- 社区绿色空间的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/jmu
- 社区便利生活的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/7U5
- 农村环境治理的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/727=xzz
- 家庭食品保存的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/nve=442
- 儿童户外活动的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/GXR=lF9
- 软件开发学习的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/310
- 公园亲子设施的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/qyv
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/bgW
- 公交无障碍服务的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/664=csi
- 市民意见收集的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/xfg=412
- 公共交通接驳的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/qow=X8y
- 无障碍信息设计的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/008
- 机器人科普活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/jev
- 青少年科普实践的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/8ZM
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/733=gow
- 数字生活课堂的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/crr=847
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/S0r=ahV
- 城市绿色交通的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/346
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/utd
- 社区停车服务的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/0uR
- 小区电梯维护的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/662=xbn
- 居民健康教育的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/isf=206
- 公共空间导览的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E9%99%85?/9cx=e0u
- 公共空间照明的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/821
- 地方美食文化中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/znh
- 乡村教育资源的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/BtH
- 在线学习体验的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/708=zlp
- 老年智能设备的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/rky=581
- 城市运动公园的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/h1l=AvG
- 租房信息服务的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/072
- 社区便利生活的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/rum
- 城市住房服务的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/Yvt
- 社区教育资源的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/265=ilp
- 乡村产业科普的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/oii=267
- 数字生活课堂的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/zCH=Xca
- 开放数据应用的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/302
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/akp
- 新能源知识普及的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/9QZ
- 城乡公共服务的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/737=vph
- 在线学习体验的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/xek=598
- 公共设施维护的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/xMJ=jRW
- 校园社团活动的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/816
- 城市公共饮水的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/qxl
- 城市文明出行的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/Yp7
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/948=arw
- 老年数字阅读的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/cdo=353
- 小区公共照明中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/vhg=Yky
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/966
- 社区科普课堂的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/rxw
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/JPh
- 社区便民集市的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/508=rez
- 智慧城市体验的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/mua=232
- 社区文化传播的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/OXK=ZqZ
- 公园亲子设施的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/211
- 软件开发学习的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/gxb
- 公园休闲体验的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/x1i
- 公交站点体验的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/053=hpx
- 节假日出行安排的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/hca=248
- 全民健身活动的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/NL9=KgS
- 城市生活记录的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/436
- 地方美食文化的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/zug
- 便民信息查询的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/kW9
- 职业技能学习的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/354=ute
- 城市文化路线的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/rcv=268
- 城市噪声观察的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/3G5=d4z
- 青年就业服务的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/832
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/pdh
- 新能源知识普及的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/0rJ
- 数字公共文化的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/020=awy
- 公共服务评价的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/nun=814
- 社区法律科普的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/sdD=zvz
- 周末休闲规划的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/413
- 数字创意课程的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/eiu
- 城市共享单车的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/hlv
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/940=opv
- 青年志愿活动中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/slm=955
- 城市空气科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/JY3=n8P
- 农产品品牌传播的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/031
- 生活技能分享的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/xtj
- 城市人文观察的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/8KO
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/140=pug
- 机器学习入门的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/cjo=501
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/9Jt=DzU
- 校园社团活动中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/897
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/hkf
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/g1S
- 公共空间安全的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/524=ogg
- 文化讲座服务的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/gtw=922
- 街区更新实践的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/8qH=6to
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/712
- 网络安全教育中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/mqv
- 公共交通接驳的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/Mv0
- 青少年科技社团的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/538=kzz
- 地方民俗记录的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/rgw=658
- 家庭理财科普的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/tW7=d4B
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/457
- 节能家电使用中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ind
- 城市应急广播中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/f7I
- 社区文化节活动的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/307=jyh
- 老年友好服务的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rcn=782
- 城市空气科普的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5bh=yF3
- 老旧小区改造的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/954
- 公园休闲体验的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/ibb
- 数字设备回收的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/Zta
- 社区互助网络的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/975=mwk
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/iuj=967
- 老年友好服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/7P6=XVN
- 基层服务创新的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/425
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/xyb
- 城市雨天出行的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/IU9
- 非遗体验活动的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/877=jik
- 电动汽车充电的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/guc=233
- 乡村阅读空间的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/3BV=WZm
- 读书会组织的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/581
- 机器学习入门的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/vzz
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/0oM
- 数字档案服务的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/010=leh
- 志愿服务平台的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/ihw=283
- 便民维修服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/ttt=5ls
- 乡村教育资源的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/576
- 开源技术交流的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/hjt
- 小区停车协商的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/VTq
- 非遗课堂体验的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/327=dds
- 乡村公共文化的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/iio=524
- 读书会组织从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AFapp-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/JBX=K8b
- 读书会组织的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/980
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/jep
- 社区科普课堂的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/c0I
- 农产品品牌传播的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/892=bdd
- 城市应急科普的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/fxe=413
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/5Ph=mx4
- 社区设施共享的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/125
- 便民维修服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/tfu
- 公共场所导视中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/OjS
- 传统节日科普的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/178=tzc
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/bmu=168
- 居民健康教育的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%90%8D%E8%B4%AFapp-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/pbr=Bk7
- 城市应急科普的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/180
- 小微企业服务的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/fxv
- 邻里共享空间的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/RwG
- 数字政务体验的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/236=xuk
- 城市绿道建设的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/zmj=910
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%90%8D%E8%B4%AFapp-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/V1f=RRK

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
