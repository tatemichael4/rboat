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

- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%99%BC%E5%A4%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/JZM
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%99%BC%E5%A4%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/941=dfu
- 电动汽车充电的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%99%BC%E5%A4%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/zzk=424
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%99%BC%E5%A4%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/R3g=kX1
- 科学教育活动的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/452
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/hps
- 城市空气科普的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/MIp
- 城市农夫市集的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/899=qym
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/efn=489
- 无障碍出行的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/aJC=PFB
- 城市社区治理的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/830
- 绿色生活实践的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/zzv
- 社区生活指南的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/TWy
- 骑行路线规划的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/643=qen
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/ypf=373
- 读书会组织的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BC%E5%A4%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/awE=I0r
- 个人时间管理的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/612
- 休闲运动入门的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/zno
- 电动汽车充电的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/vWg
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/323=bpy
- 家庭饮食安排的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/mva=855
- 节气饮食文化的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_360%E5%85%AC%E5%BC%80%E8%AF%BE?/5XW=Pto
- 城乡公共服务的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/630
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/eoj
- 公共场所导视的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/fF3
- 物业服务沟通的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/981=beq
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/kdc=715
- 数字设备回收的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/tUy=4X9
- 户外活动组织中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/924
- 农村环境治理的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gqp
- 农业科普体验的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/FF0
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/546=gjw
- 城市公共空间的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/dow=329
- 公共空间照明的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/nMg=WsT
- 公共文化活动的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/798
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/ilm
- 公共服务数字化的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/pkS
- 城市夜间生活中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/723=fif
- 数字便民地图中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/ijh=896
- 家庭运动计划的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/cI4=m1N
- 社区法律科普中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/641
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/lfi
- 数字学习资源的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/HFG
- 社区阅读服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/801=lyr
- 骑行路线规划的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/zfm=780
- 城市社区治理的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%99%BC%E5%A4%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/wTs=yTP
- 公共文化活动的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/848
- 城市文明实践的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/jkz
- 乡村电商实践的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/Cx0
- 社区慢性病防控的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/915=ipe
- 城市公共饮水的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/ejx=244
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%99%BC%E5%A4%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/Oxz=qeD
- 城市绿道建设的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/763
- 儿童友好空间的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/rvi
- 社区志愿服务的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/96g
- 社区学习活动的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/962=wnk
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/ims=306
- 地方文化传播的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E7%99%BC%E5%A4%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/pB8=mV2
- 儿童安全出行的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/977
- 数字生活课堂的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/zfy
- 街区更新实践的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/JIk
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/645=skh
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/sux=162
- 无障碍出行的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/tXE=mxn
- 家庭饮食安排的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/205
- 市民意见收集的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/hzy
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/DtB
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/796=enq
- 社区花园共建的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/rwp=334
- 青少年科普实践的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/D7R=jne
- 智慧停车服务的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/841
- 公共设施维护的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/cgt
- 青少年科普实践的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/qf7
- 社区快递服务的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/392=unn
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/vvr=652
- 户外活动组织的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/pMY=YqS
- 乡村生活观察的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/557
- 光伏知识科普的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/szh
- 地方戏曲体验的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/I7j
- 街区更新实践的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/103=zfm
- 公共设施使用的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/mbx=018
- 社区老年食堂的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/B5H=HNd
- 家庭收纳实践的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/683
- 应急物资管理的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/qui
- 全民阅读推广的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/z0C
- 食品安全科普的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/952=wvd
- 图书借阅体验的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/ktj=416
- 家庭消费规划的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/Aix=KWz
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/120
- 社区学习活动的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/zvs
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/rdG
- 城市绿道建设的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/194=eje
- 环境监测科普的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/cpt=673
- 青少年科技社团的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/Em4=4Bh
- 小区电梯维护的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/440
- 数字地图应用的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ypa
- 社区养老服务的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zY6
- 社区便民集市的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/953=tra
- 食品安全科普的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mhy=934
- 家庭节能设备中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ojr=jQy
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/470
- 城市夜间生活的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/nah
- 社区手工活动的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/5L7
- 非遗体验活动的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/015=rjb
- 社区便利生活的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/cva=164
- 急救知识普及的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/ARu=uiL
- 社区信息发布的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/355
- 健康饮水科普的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/rwg
- 社区修缮行动的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/ogF
- 气象科普传播的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/393=rjz
- 便民维修服务的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/yms=885
- 运动安全知识的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/QBr=olu
- 志愿服务平台的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/505
- 公共服务评价的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/yqa
- 城市人文观察的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/LpY
- 社区活动报名的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/717=fsa
- 读书会组织的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/olg=669
- 城市展览体验的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/j5h=Hu7
- 市民意见收集的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/628
- 基层健康档案的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/wop
- 社区活动空间的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/KLf
- 亲子阅读活动的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/119=osz
- 无障碍出行的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/esh=252
- 城市骑行环境的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/VMR=0TW
- 城市水环境观察中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/466
- 数字档案服务的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/jng
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/qjM
- 软件开发学习的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/761=awm
- 节气饮食文化的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/qko=903
- 社区快递服务的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/TBD=DTA
- 城市运动公园的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/687
- 乡村电商实践的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/yvd
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/cGw
- 城市文化路线的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/809=flf
- 社区互助网络的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/frx=213
- 老年数字阅读的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/waj=CCk
- 社区教育资源的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/936
- 科技馆参观体验的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/itz
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/inf
- 乡村文化空间的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/913=oji
- 数字政务体验中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/yuc=844
- 机器人科普活动的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/mM2=VqU
- 网络安全教育的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/440
- 数字素养提升的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/ywt
- 旧物循环利用的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/Atv
- 数字生活课堂的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/708=wje
- 网络安全教育的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/guk=943
- 家庭理财科普的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/Yew=lEK
- 科学信息获取的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/404
- 数字创作工具的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/sfl
- 社区文化节活动的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/uXG
- 文化讲座服务的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/822=bqs
- 城市可持续生活的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/ffu=475
- 乡村公共文化的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/aTX=XIT
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/234
- 城市文明实践的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/yeu
- 食品配送体验的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/sBv
- 城市适老服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/555=xya
- 地方美食文化的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/uxc=856
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/xN4=77m
- 城市树木认养的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/714
- 社区文化传播的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/mst
- 消防知识宣传的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/iFB
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/253=ppi
- 居民健康教育的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/aoj=573
- 便民服务窗口的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/mJS=T6f
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/613
- 环境教育课程的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/bsy
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/wvd
- 老年数字阅读的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/279=eez
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/dun=920
- 家庭急救准备的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/wbT=Dww
- 社区公共餐饮的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/632
- 小区停车协商的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/vzt
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/NZH
- 公共交通信息服务的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/027=aqf
- 学校体育活动的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/zgl=118
- 儿童运动体验的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/dTR=ULf
- 城市步行友好的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/326
- 社区修缮行动的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/pnn
- 户外活动组织的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/S6O
- 城市雨天出行的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/073=ahg
- 社区家校合作的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/bgs=858
- 家庭运动计划的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/LtZ=8o7
- 基层健康档案的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/732
- 个人信息保护的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/zbd
- 智慧城市体验的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/4PW
- 职业技能学习的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/047=myi
- 家庭园艺实践的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/dpl=972
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/Pkq=oOL
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/081
- 数字设备回收的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/ays
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/um3
- 社区活动策划的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/955=tiu
- 城市夜间生活的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/ovj=000
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/FNN=Mfv
- 个人时间管理的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/747
- 本地旅行体验的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/zgd
- 休闲运动入门的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/DoO
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/708=qam
- 公共交通接驳的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/zfi=252
- 儿童阅读角的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/SJM=PHW
- 乡村产业科普的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/443
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/fbo
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/MIj
- 城市公共标识的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/490=ujr
- 社区家校合作的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/cid=819
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/nbK=waJ
- 乡村生态观察的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/952
- 药品使用科普的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/dpu
- 智慧城市体验的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/asx
- 地方文化传播的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/882=wty
- 公共空间照明的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/wik=866
- 绿色生活实践的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/dq8=GPn
- 租房信息服务的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/028
- 环境监测科普的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/vtx
- 社区快递服务的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/2DB
- 青少年科技社团的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/080=ujv
- 公共服务咨询的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/fbp=561
- 药品使用科普的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/seO=T4K
- 食品安全科普的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/971
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/xfe
- 青少年科技社团的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/25V
- 城乡交流活动的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/046=ehq
- 城乡交流活动的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/onr=488
- 环境监测科普的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/Qjm=jZv
- 绿色出行服务的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/113
- 城市适老服务的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/nac
- 社区环保活动的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/2Ca
- 社区公共餐饮的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/585=twu
- 公园休闲体验的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ucr=162
- 城市适老服务的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/0lX=DIm
- 农村环境治理的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/519
- 社区健康讲座的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/vdj
- 在线学习体验的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/n4I
- 社区垃圾分类的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/493=uss
- 社区便民集市的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/egt=728
- 街道综合服务的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA?/9cQ=L1d
- 开放式学习空间的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/039
- 公共服务数字化的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/zqr
- 旧物循环利用的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/oRu
- 科技馆参观体验的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/798=myu
- 校园安全教育的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/okw=842
- 公共场所导视的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/lPd=5Sc
- 公共服务沟通的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/590
- 城市应急广播的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/lhz
- 城市公共饮水的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/R0D
- 农贸市场环境的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/184=xhj
- 居家防滑改造中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/lus=621
- 个人时间管理的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/IfQ=lYB

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
