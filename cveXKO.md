# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 家庭环保习惯的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/710
- 无障碍出行的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/xtf
- 社区生活指南的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/LBu
- 街头绿植养护的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/705=vbs
- 学校体育活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/vaf=552
- 社区休闲设施的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8II_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/ziI=X1d
- 租房信息服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/326
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/qnn
- 旧物循环利用的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/MPo
- 老年人日常照护的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/323=dle
- 公园亲子设施的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/ttr=229
- 儿童安全出行的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/Raq=hYt
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/000
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/azj
- 公共服务数字化的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/qnN
- 学校体育活动的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/261=jyt
- 课后服务体验的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/obk=958
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eix%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/PEu=Zlq
- 城市应急科普的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/786
- 家庭志愿活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/mcw
- 智能手机助老的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/rRl
- 公交站点体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/863=aab
- 城市共享单车的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/flc=457
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E1.0_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/mGz=hro
- 数字资源检索的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/241
- 城市生活服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/bvy
- 公共空间照明的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/r9b
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/489=but
- 青少年户外教育的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/xvl=497
- 绿色办公实践的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E.apk%E5%BD%A9%E7%A5%9E%E8%80%81%E7%89%88_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/pAp=1Ra
- 城市文明实践的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/416
- 校园安全教育的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/ram
- 社区活动空间的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/E4C
- 城市慢跑路线的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/622=xkq
- 在线教育体验的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/iwr=678
- 社区文化节活动的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9E1_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/IJG=lrf
- 医院导诊服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/691
- 地方旅游导览的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/gbd
- 信息无障碍体验的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/KKQ
- 老年人日常照护的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/858=xor
- 城市夜间生活的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/nje=680
- 城市绿色交通的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3APP%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/xXy=xtr
- 口袋公园建设的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/406
- 社区商业活力的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/qka
- 社区环保活动的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/a0u
- 城市步行友好的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/199=inc
- 学校食育活动的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/xli=468
- 食品安全科普的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3APP%E6%8C%82%E6%9C%BA_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/6Ui=DxR
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/527
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/qlr
- 社区科普课堂的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/7ET
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/023=qzk
- 数字艺术创作的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/cws=647
- 城市微更新实践的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/0pf=Hsc
- 地方旅游导览中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/135
- 数字政务体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/lzu
- 城市农夫市集的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/5mn
- 社区商业活力的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/585=lgj
- 儿童安全出行的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/oxb=198
- 公共文化活动的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/hz0=PJw
- 校园阅读活动的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/250
- 小区电梯维护的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/mvu
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/m3L
- 地方旅游导览的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/197=qga
- 急救知识普及的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/rch=399
- 社区设施共享的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/aF2=s1T
- 社区公共议事的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/595
- 家庭安全提示的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/lvm
- 科学观察活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/Cb9
- 公共文化活动的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/306=rpt
- 开放数据应用的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/mkv=364
- 城市骑行环境的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_360%E6%A1%A3%E6%A1%88?/8EP=QSz
- 食品配送体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/511
- 城市适老服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/aox
- 城市慢跑路线的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/gdD
- 数字创意课程中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/578=jyz
- 智能家居应用的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/tho=806
- 健康信息获取的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/MXL=uW1
- 社区儿童活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/765
- 家庭饮食安排的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/mmy
- 小区停车协商的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/HQh
- 老年人日常照护的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/174=ryx
- 乡村公共阅读的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/ajd=090
- 城市博物馆活动的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/U64=zdY
- 光伏知识科普的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/655
- 老年学习活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/qtl
- 社区故事采集的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/12f
- 农产品消费体验的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/212=ttc
- 数字便民地图的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/epm=204
- 户外活动组织的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_360%E6%B3%95%E5%BE%8B?/g0x=eGV
- 便民服务地图的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/764
- 老年学习活动的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/tyf
- 生活垃圾减量的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/A2T
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/112=hzk
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/teq=678
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/Cdc=kZA
- 社区设施共享的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/767
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/lvb
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/QKU
- 数字公共文化的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/131=big
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/xxh=998
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/3LO=NHt
- 城市农夫市集的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/225
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/iyf
- 公共设施使用的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/9kn
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/039=eiq
- 城市住房服务中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/xym=192
- 社区协商议事的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/BMb=1BO
- 创业经验分享的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/592
- 乡村产业科普的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/qui
- 智慧城市体验的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/a2e
- 社区消防演练的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/285=wft
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/zxs=223
- 农业科普体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/A0Q=d8N
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/616
- 地方文化传播的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/eba
- 乡村公共文化中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/6n8
- 乡村教育资源的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/815=mri
- 职业技能学习的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/qzk=404
- 社区故事采集的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/Lh1=odQ
- 城市夜间照明的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/194
- 乡村电商实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/rju
- 家庭健康管理的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/8IB
- 在线教育体验的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/151=qgh
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/skl=541
- 智慧停车服务的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/5XA=VOm
- 社区安全巡查的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/098
- 社区环保活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/yvz
- 青少年心理健康的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/HTE
- 老年学习活动的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/120=mjf
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/ttw=171
- 老旧小区改造的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/mXe=mZ4
- 乡村教育资源的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/739
- 城市运动公园的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/jng
- 地方文化传播的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/neM
- 药品使用科普的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/749=jde
- 乡村教育资源的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/omt=921
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/VvC=buf
- 社区公共卫生中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/846
- 家庭用电安全的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ixl
- 城市基础设施的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/4Sv
- 农村环境治理的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/203=izh
- 科学教育活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/jcx=152
- 城市公共艺术的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%8D%93%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/VkI=WUB
- 日常摄影记录的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/508
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/pbt
- 城市公共空间的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/kzA
- 低碳社区实践的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/842=chd
- 农贸市场环境的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/hxw=817
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_3%2B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/7UW=NPp
- 城市共享单车的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/749
- 家庭养老规划的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/kjk
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/eRN
- 城市噪声观察的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/095=dek
- 家庭环保行动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/kwa=168
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/ekv=O3y
- 全民健身活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/599
- 老年智能设备的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/ffd
- 消防知识宣传的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/JcJ
- 小区电梯维护的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/716=jfk
- 农村环境治理的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/hmr=075
- 基层健康档案的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/QrV=sAv
- 乡村生活观察的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/119
- 城市文明实践的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/pbe
- 儿童阅读角的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/RYx
- 数字阅读服务的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/291=ibu
- 社区修缮行动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/bjv=835
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/CCT=OSy
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/695
- 社区活动策划的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/jxw
- 应急物资管理的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/VqC
- 读书会组织的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/267=zpu
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/aqm=006
- 电子商务服务的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/hFX=cB7
- 节约用水实践的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/261
- 青年职业探索的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/smm
- 街区更新实践的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/eiA
- 创业经验分享的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/507=oha
- 公共服务评价的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/fuh=124
- 公交无障碍服务的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/cXv=0hc
- 社区便利生活的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/876
- 地方旅游导览的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/acr
- 亲子阅读活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/ibu
- 城市公共空间的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/583=svg
- 周末休闲规划的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/mzm=213
- 青少年户外教育的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/HVf=yRX
- 社区家政服务的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/279
- 街区道路维护的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/fcq
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/D9j
- 新能源知识普及的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/289=hka
- 老年人出行服务的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/nvl=145
- 绿色出行服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/RGn=msq
- 公共空间照明的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/923
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/atc
- 社区活动策划的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/niO
- 青少年户外教育的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/450=ype
- 健康饮水科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/vmt=650
- 社区志愿服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%BD%AF%E4%BB%B6%E5%95%86%E5%BA%97%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/3IA=mwV
- 社区协商议事的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/283
- 公共空间休憩的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/ggb
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/HjO
- 城市共享单车的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/214=huw
- 城市骑行环境的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/oqo=736
- 城市公共自行车的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/Avk=j3M
- 社区菜市场服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/404
- 节约用水实践的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/vhi
- 城市公共厕所的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/iLA
- 地方旅游导览的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/104=ywp
- 科技馆参观体验的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/yxy=402
- 节假日出行安排的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/VNA=lVV
- 智能手机助老的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/805
- 公共文化活动的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/ubi
- 农产品品牌传播的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/2cQ
- 社区文化节活动的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/152=pqn
- 就业技能培训的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/wvk=346
- 城市适老服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/aGH=wKm
- 城市体育设施的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/709
- 公共空间安全的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/tpo
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/oMb
- 家庭教育交流的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/913=pic
- 全民阅读推广的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/umx=879
- 公共空间休憩的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB3appios_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/Jfi=8J9
- 公交站点体验的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/866
- 软件开发学习的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/qzz
- 社区家校合作的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/sQb
- 城市公共饮水的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/366=tzi
- 社区停车服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/hvs=471
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%BE%8E%E6%B9%83?/hJV=8gw
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/496
- 公园亲子设施的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/kpz
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/3aX
- 人工智能科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/836=kbu
- 生成式工具使用的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/cxf=427
- 社区运动空间的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/X57=gc0
- 节假日出行安排的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/162
- 乡村文化活动的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/iqp
- 生活服务数字化的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/hj7
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/225=usc
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/bvu=250
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/RIy=d7d
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/498
- 乡村生态旅游的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/cfr
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/hXu
- 社区手工活动的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/043=uvk
- 远程协作工具的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/tpe=895
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/k8O=76z
- 城市公共座椅的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/503
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/wfb
- 城市游园体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/de7
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/500=twt

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
