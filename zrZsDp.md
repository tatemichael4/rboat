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

- 城市运动公园的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%9B%9B%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/46A
- 个人信息保护的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%9B%9B%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/806=ivz
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%9B%9B%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/iht=531
- 人工智能科普的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%9B%9B%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/j3g=jnR
- 校园节能行动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/059
- 城市公共艺术的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/naw
- 户外活动组织的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/oab
- 社区志愿服务的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/620=mnw
- 传统手工艺体验的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/jfy=942
- 基层健康服务的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96-APP_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/EhG=dbz
- 乡村文化活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/937
- 社区便民服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/wvj
- 骑行路线规划的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/GxV
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/830=jtm
- 城市展览体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/xpa=000
- 地方美食文化的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/mRE=p5U
- 乡村教育资源的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/945
- 城乡公共服务的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/bij
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/7tf
- 社区垃圾回收的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/984=uje
- 科学观察活动的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/ads=156
- 社区设施共享的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/gYe=dwd
- 青少年编程学习的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/428
- 老年友好服务的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/qhs
- 新能源知识普及的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/aH5
- 家庭环保行动的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/962=etb
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/xox=609
- 家庭教育交流的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%9B%9B%E4%B8%96-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/t6c=nDC
- 公共设施使用的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/570
- 物业服务沟通的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/jfr
- 家庭用电安全的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/qrS
- 社区心理支持的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/517=hls
- 老年人文化生活的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/gjn=790
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/Qlh=tT8
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/106
- 绿色建筑理念的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/asc
- 青年志愿活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/KJ7
- 药品使用科普的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/987=kwi
- 数字学习资源的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/hfu=615
- 社区活动策划的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/D85=FRN
- 公共空间导览的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/175
- 节能生活方式的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/ahw
- 便民维修服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/pjr
- 社区消防演练的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/075=krn
- 线上办事服务中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/vhi=588
- 青年职业探索的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/mHV=17Y
- 社区科普课堂的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/440
- 城市社区治理的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/rua
- 城市体育设施的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/p0N
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/278=onf
- 城市步行环境的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/bvt=115
- 城市空气科普的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/iXl=ui1
- 智慧城市体验的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/467
- 城市夜间生活的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/buv
- 城市噪声观察的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/mXQ
- 青少年心理健康的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/100=ucb
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/pbu=452
- 城市慢跑路线的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/hsv=YFR
- 社区便民集市的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/631
- 乡村生活观察的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/hir
- 基层服务创新的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/7aj
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/443=ysp
- 社区协商议事的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/izv=827
- 生成式工具使用的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E7%9B%9B%E4%B8%96-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/LqV=6Qp
- 数字素养提升的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/956
- 公交站点体验的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/nhk
- 公共服务沟通的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/jpt
- 居家适老化改造的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/226=jhz
- 老年友好服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ghr=380
- 绿色校园实践的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E4%B8%96-%E5%AE%98%E6%96%B9_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/KDx=IQE
- 城市夜间照明的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/739
- 街区更新实践的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/hmh
- 公共场所导视的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/u1d
- 便民信息查询的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/346=aai
- 图书馆活动策划的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/zen=470
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/nvG=rEj
- 绿色办公实践的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/458
- 城乡交流活动的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/iow
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/XQ2
- 家庭节能实践的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/998=pmz
- 图书借阅体验的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/equ=596
- 读书会组织的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/BSc=RF2
- 家庭用电安全的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/314
- 节日文化体验的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/esy
- 城市公共艺术的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/0dp
- 小区电梯维护的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/045=oig
- 学校体育活动的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/ber=763
- 社区商业活力的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/fEo=QpV
- 街道综合服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/904
- 农业科普体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/pox
- 灵活就业交流的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/DXl
- 本地消费场景的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/193=xvr
- 无障碍出行的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/kdf=534
- 农产品消费体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/dK9=nfR
- 街区更新实践中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/904
- 校园阅读活动的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/vwt
- 社区消防演练的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/OXW
- 节能家电使用的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/985=gqg
- 数字生活课堂的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/jww=105
- 线上办事服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%9C%B0%E4%BA%A7?/Ftq=u3w
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/271
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/voh
- 社区活动策划的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/Wbc
- 城市应急科普的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/485=usb
- 城市博物馆服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/lhc=442
- 创业经验分享的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/kBd=Zxn
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/137
- 家庭消费规划的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/kyo
- 儿童户外活动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/3YU
- 社区手工活动的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/445=jlh
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/bgs=647
- 周末休闲规划的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/jWK=Psx
- 社区花园共建的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/274
- 读书会组织的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/szp
- 老年数字阅读的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/bhe
- 数字学习资源的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/548=gmw
- 社区家政服务的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/xqy=015
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/Csz=fDP
- 农村环境治理的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/632
- 城市慢行系统的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/puv
- 社区心理支持的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/uQg
- 城市微更新实践的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/356=wsh
- 数字艺术创作的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/ums=748
- 校园节能行动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%AE%9E%E5%BD%95?/D1R=GBj
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/078
- 老年人文化生活的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/stj
- 家庭网络使用的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/IAl
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/029=acp
- 老年友好服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/met=421
- 社区读书角建设的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/WcQ=KA4
- 农贸市场环境的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/349
- 儿童友好空间的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/wql
- 社区环保活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/vRR
- 软件开发学习的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/487=tip
- 文化场馆预约的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/ahw=851
- 线上阅读资源的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/bNw=oKa
- 城市博物馆活动的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/751
- 乡村产业科普的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/rmf
- 城市社区治理的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/6M0
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/599=cmt
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/dbu=879
- 青少年户外教育的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%88%9B%E6%8A%95?/zJN=flz
- 环境监测科普的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/167
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/npo
- 社区信息发布的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/whu
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/601=fbm
- 青少年科技社团的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/dfb=956
- 社区艺术活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/XWi=LHu
- 志愿服务平台的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/571
- 绿色出行服务的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/axp
- 社区家政服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pfI
- 文化场馆预约的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/978=vjw
- 乡村文化活动的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uoz=492
- 社区垃圾回收的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/s84=iaK
- 运动安全知识的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/129
- 校园节能行动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/yxy
- 科学信息获取的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/O3D
- 生活垃圾回收的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/285=ovk
- 绿色消费选择的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/zka=111
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/W0s=uEH
- 老年人文化生活的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/161
- 儿童安全出行的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/obf
- 新能源出行的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/JDG
- 校园阅读活动的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/544=jpk
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/mbw=324
- 机器人科普活动的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/oeh=IfH
- 农产品消费体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/003
- 家庭运动计划的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/mfg
- 乡村产业科普的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/ZOU
- 老年友好服务的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/339=aka
- 物业服务沟通的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/shf=299
- 社区互助网络的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/cJ6=1Ka
- 生活技能分享的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/869
- 家庭园艺实践的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/jys
- 节日文化体验的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/pWc
- 城市展览体验的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/450=sye
- 学校食育活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/fqh=373
- 数字支付体验的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/pUp=Eli
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/588
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/fjn
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/zPy
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/616=qwe
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/hum=163
- 社区科普课堂的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/gcC=5Q2
- 街道综合服务的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/591
- 节日文化体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/irh
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/XU2
- 智能手机助老的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/944=qgn
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/krr=674
- 急救知识普及的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%94%90%E8%AF%84?/jL5=p71
- 城市展览体验的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/238
- 职业技能学习的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/pvo
- 传统手工艺体验的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/VNN
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/322=emk
- 开放数据应用的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/quu=346
- 社区托育服务中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/Q87=1x6
- 社区健康讲座的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/353
- 城市人文观察的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/arj
- 传统节日科普的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/tgz
- 城市基础设施的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/323=cvs
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gqw=645
- 城市生活记录的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bVZ=v2u
- 市民热线服务的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/834
- 在线学习体验的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/qpt
- 终身学习资源的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/9wI
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/380=fah
- 新能源出行的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/wjz=487
- 城市应急广播的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%99%BE%E7%A7%91?/x4b=g0G
- 物业服务沟通的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/467
- 公交站点体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/mnk
- 传统节日科普的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/gFg
- 职业技能学习的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/167=hvq
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/lbp=184
- 社区环保活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/xXB=mKv
- 地方文化传播的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/908
- 乡村公共文化的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/pzj
- 低碳社区实践的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/Y7a
- 家庭养老规划的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/745=qhp
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/nwq=990
- 节日文化体验的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/ODW=1Qt
- 城市可持续生活的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/220
- 文明养宠科普的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/inf
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/P4H
- 家庭照护支持的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/398=nnh
- 城市社区治理的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/thq=970
- 社区活动空间的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/HIH=zmC
- 家庭运动计划的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/668
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/sex
- 科学运动指导的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/OLP
- 数据分析入门的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/455=ywk
- 公共空间安全的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/ppt=437
- 老旧小区改造的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/yYK=z7L
- 绿色出行服务的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/742
- 基层服务创新的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/sao
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/24H
- 节能家电使用的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/353=wcc
- 市民意见收集的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/dse=612
- 消防知识宣传的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/T3j=klL
- 城市体育设施的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/401
- 社区公共议事的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/ahs
- 药品使用科普的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/7bE
- 小微企业服务的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/758=ozt
- 跨代沟通活动的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/qun=840
- 远程协作工具的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/xvk=rRN
- 社区志愿服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/633
- 青年职业探索的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/fdx
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/1H5
- 社区手工活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/958=uww
- 儿童阅读角中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/nzl=393
- 公共交通接驳的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/OTb=Ew3

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
