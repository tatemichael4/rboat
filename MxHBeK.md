# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 公共空间照明的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/498
- 社区体育组织的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/qhs
- 社区艺术活动的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/rF8
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/455=xyy
- 社区文化传播的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/pnp=304
- 家庭用电安全的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_132cc%E5%BD%A9%E7%A5%A8-app_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/wjY=ONh
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/879
- 校园节能行动的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/quz
- 青年志愿活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/nnD
- 新能源出行的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/648=byg
- 骑行路线规划的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/emt=504
- 社区协商议事的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/GPW=KPf
- 节日文化体验的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/547
- 生成式工具使用的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/idd
- 社区停车服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/b6V
- 生活服务数字化的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/922=qyd
- 家庭用电安全的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rba=959
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/sLZ=x1h
- 老年人日常照护的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/373
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/odp
- 数字资源检索的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/Rgf
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/505=fub
- 社区读书角建设的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/hjd=037
- 医院导诊服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/xPd=6PU
- 城市雨天出行的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/797
- 数字创意课程的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/eqv
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/F99
- 乡村生活观察的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/198=ktg
- 社区活动策划的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/wlq=491
- 小区公共照明的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1368%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/e8b=o3J
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/217
- 租房信息服务的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/xwa
- 社区文化传播的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/80W
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/567=ime
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/ckn=631
- 城市社区治理的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_829%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/95a=Sg7
- 街区绿化养护的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/941
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/awr
- 绿色快递包装的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/Xlj
- 城市游园体验的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/282=lsb
- 街区道路维护的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/fif=269
- 科学信息获取的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E4%BA%B2%E5%AD%90?/9S2=lPw
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/006
- 社区老年食堂中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/kyn
- 公共设施使用的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/4cj
- 传统手工艺体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/399=pni
- 家庭运动计划的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/dms=846
- 志愿服务平台的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7070%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/O5m=ZTm
- 城市公共标识的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/951
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/rdh
- 儿童运动体验的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/Ra8
- 城市雨天出行的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/926=vqk
- 社区养老服务的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/hgt=174
- 数字创意课程的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/qtY=FZg
- 居家防滑改造的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/682
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/sfo
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/dEY
- 城市雨天出行的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/667=eil
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/bjs=176
- 街头绿植养护的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/6BB=7wc
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/238
- 电动汽车充电的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/jkf
- 家庭理财科普的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/G7y
- 软件开发学习的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/074=nsm
- 城乡交通衔接的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/dzf=591
- 健康信息获取的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/Nh5=PmW
- 社区商业活力的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/423
- 社区修缮行动的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/hhy
- 气象科普传播的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/5CF
- 社区公共卫生的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/845=ljo
- 家庭志愿活动的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/hnl=188
- 线上办事服务的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/vRb=N33
- 开源技术交流的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/578
- 城市文明出行的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/yem
- 数字支付体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/uhR
- 新能源出行的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/538=htn
- 家庭网络使用的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/wwv=460
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/zfc=XXO
- 社区便民集市的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/958
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/cdq
- 在线学习体验的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/Eek
- 科学信息获取的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/972=fuy
- 邻里互助活动的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/gfh=763
- 家庭健康科普的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_160%E5%A8%B1%E4%B9%90-Welcome%E5%A4%A7%E5%8E%85_360%E6%8E%A2%E5%BA%97?/TGe=E3J
- 城市骑行环境的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/294
- 图书借阅体验的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/tde
- 家庭运动计划的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/6us
- 乡村公共文化的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/727=uhc
- 数字课堂应用的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/zll=988
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E6%97%A7%E7%89%88%E6%9C%AC_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/gz7=aoa
- 电子商务服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/266
- 数据分析入门的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/fqc
- 远程协作工具的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/1Ej
- 电动汽车充电的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/806=url
- 急救知识普及的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/tbt=314
- 城市噪声观察的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/nmn=9KN
- 数字设备回收的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/784
- 城市生活服务的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/pld
- 老年人文化生活的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/lrq
- 科普展览体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/338=rks
- 公共服务数字化的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/xih=227
- 社区体育组织的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_160%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/nFo=Soi
- 家庭消费规划的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/823
- 数字便民地图的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/mbo
- 街区道路维护的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/n9m
- 城市生活记录的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/575=nxs
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/cnm=695
- 信息无障碍体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8ios%E7%89%88_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/KJm=Js7
- 便民服务窗口的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/052
- 社区设施共享的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/pud
- 农业科普体验的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/zCG
- 社区交通安全的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/791=cik
- 城市共享单车的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/oim=873
- 亲子阅读活动的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_998%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/wLM=Evu
- 市民热线服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/093
- 城市住房服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/tol
- 基层服务创新的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/mXW
- 城市空气科普的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/586=jvh
- 家庭网络使用的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/doi=489
- 乡村产业科普的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8208%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/aAF=OuF
- 公共卫生设施的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/622
- 数字艺术创作的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/oys
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/3N7
- 校园社团活动的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/611=bsv
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/tht=576
- 居家适老化改造的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%93%AA%E9%87%8C%E5%8F%AF%E4%BB%A5%E7%8E%A9%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/2pi=LeL
- 节约用水实践的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/157
- 城市公共自行车的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/zea
- 街区小店体验的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/Fho
- 绿色建筑理念的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/207=mby
- 周末休闲规划中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/iqx=831
- 老年数字阅读的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8welcome123%E4%B8%AD%E5%BF%83%E7%89%88_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/9tI=Urt
- 城市文明出行的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/134
- 家庭园艺实践的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/apy
- 跨代沟通活动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/qiJ
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/314=puo
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/osz=002
- 社区家政服务的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_con9055%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/l1H=LEQ
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/841
- 科学健身方法的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/xya
- 城市展览体验的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/Ua2
- 农贸市场环境的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/265=jdb
- 地方美食文化的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/aze=083
- 生活服务数字化的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/iRe=jPH
- 开放数据应用的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/570
- 社区垃圾分类的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/kuq
- 校园节能行动的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/nYO
- 小微企业服务的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/575=qtc
- 公共交通信息服务的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/dup=920
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_9055%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/oiD=chH
- 农贸市场环境的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/644
- 城乡交通衔接的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/dxl
- 老年数字阅读的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/JCI
- 租房信息服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/216=iqz
- 绿色消费选择的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/ngj=199
- 线上阅读资源的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_9055%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/00O=tcV
- 家庭教育交流的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/371
- 家庭节能实践的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/dsv
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/a5X
- 文化场馆预约的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/708=phf
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/uqz=996
- 生活垃圾回收的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_555cn%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/Fz3=4Zm
- 科普展览体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/609
- 公交无障碍服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/fxu
- 家庭环保习惯的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/jhz
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/403=rnw
- 邻里互助活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/nes=512
- 城市生活记录的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_9055%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/M04=jMi
- 数字生活课堂的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/238
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/dkd
- 社区文化节活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/9GC
- 城市骑行环境的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/966=ogr
- 公共交通信息服务的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/zds=098
- 数字阅读服务的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_3956%E5%BE%B7%E5%BD%A9%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/ov0=r5v
- 电动汽车充电的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/244
- 家庭饮食安排的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/qfq
- 气象科普传播的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/SCD
- 社区休闲设施的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/333=ilv
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/ccl=860
- 电动汽车充电的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_5833%E5%90%89%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/Kku=21Y
- 公共场馆服务的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/847
- 家庭运动计划的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/rqk
- 家庭运动计划的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/1NS
- 绿色生活实践的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/962=zka
- 城市社区治理的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/imm=344
- 城市人文观察的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/4Me=Fgi
- 电子商务服务中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/038
- 城市骑行环境的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/hfq
- 公共场馆服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/Ini
- 健康信息获取的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/247=npi
- 城市微更新实践的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/adv=155
- 数字创作工具的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9VIP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/Hgb=Q9R
- 社区公共卫生的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/440
- 绿色出行服务的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/qdh
- 青年志愿活动的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/CxP
- 本地旅行体验的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/553=mix
- 社区安全巡查的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/qdb=112
- 居家适老化改造的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/LC4=sNi
- 地方民俗记录的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/360
- 家庭健康管理的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/qly
- 老年友好服务的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/x5y
- 青少年编程学习的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/706=kna
- 家庭理财科普的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/epv=134
- 小微企业服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_5833%E5%BD%A9%E7%A5%A8welcome_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/X9J=SEy
- 城市夜间照明的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/331
- 社区故事采集的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/nqi
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/sX1
- 社区共享书架的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/664=dpi
- 数字政务体验的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/gdq=294
- 城市住房服务的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/SlX=PXH
- 家庭教育交流的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/936
- 街区更新实践的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/eve
- 社区垃圾回收的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/R6p
- 地方文化传播的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/293=qss
- 基层服务创新中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/wzu=489
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%A5%E5%BD%A9%E7%BD%9145556-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/EnK=Yc7
- 生活垃圾减量的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/803
- 社区故事采集的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/aya
- 城市文明出行的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/nEM
- 城市游园体验的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/085=foc
- 公共设施维护的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/lju=460
- 公共场所导视的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/5KQ=Q0a
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/620
- 社区体育组织的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/cfx
- 节日文化体验的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/qE0
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/665=gza
- 社区修缮行动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/akb=818
- 城市农夫市集的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%A5%A5%E5%90%89%E5%BD%A95833%E6%9C%80%E6%96%B0%E7%89%88%E5%8A%9F%E8%83%BD_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/NX7=GAW
- 乡村公共文化的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/640
- 开源技术交流的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/ues
- 读书会组织的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/Esv
- 安全出行教育的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/917=rvq
- 城市体育设施的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/udh=531
- 社区宠物管理的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/JGs=d7V
- 居家防滑改造的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/551
- 公共设施使用的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/igx
- 乡村文化活动的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/R8V
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/969=qyd
- 农产品消费体验的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/agk=871
- 农村环境治理的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/CHP=wlS
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/409
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/yfk
- 儿童运动体验的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/KaO
- 公共服务沟通的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/465=mxz
- 软件开发学习的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/fao=392
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_800cc%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/FZD=dst
- 全民健身活动的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/263
- 家庭消费规划的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/kiu
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/OiW
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/577=qyn

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
