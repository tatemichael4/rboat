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

- 生活垃圾减量的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/449
- 旧物循环利用的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/qvl
- 家庭环保行动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/beY
- 公园无障碍服务的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/097=may
- 信息无障碍体验的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/oom=475
- 城市适老服务的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/3XX=S6x
- 儿童户外活动的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/963
- 小微企业服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/oxp
- 家庭理财科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/hbq
- 市民热线服务的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/479=jei
- 绿色办公实践的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/lvj=824
- 无障碍信息设计的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/UQZ=98J
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/465
- 街区道路维护的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/gfg
- 休闲运动入门的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/lpa
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/723=cub
- 绿色建筑理念的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/zmf=676
- 公共空间休憩的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/H0b=fYc
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/947
- 老年学习活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/crj
- 公交无障碍服务的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/Q2k
- 文化讲座服务的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/566=gsy
- 通勤路线规划的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/gyp=911
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/fcu=D3X
- 城市公共座椅的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/508
- 家庭照护支持的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/yhp
- 职业技能学习的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/hPO
- 便民信息查询的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/632=sxb
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/tph=846
- 应急物资管理的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/BCp=4nK
- 城市运动公园的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/358
- 乡村教育资源的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/hfn
- 线上办事服务中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/n9h
- 校园节能行动的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/723=bum
- 城市公共艺术的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/xlj=982
- 数字艺术创作的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/Fu7=qud
- 城市公共标识的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/329
- 光伏知识科普的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/qmd
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/LlL
- 本地旅行体验的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/431=kmq
- 邻里共享空间的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/jht=615
- 社区体育组织的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/Anr=B5N
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/670
- 社区设施共享的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/pfv
- 健康饮食教育的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/jsW
- 文明养宠科普的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/275=eww
- 青少年编程学习中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/ykf=349
- 智能手机助老的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/Nua=CEa
- 社区共享书架的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/470
- 社区健康讲座的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/fef
- 便民服务地图的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/QEr
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/642=wpa
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/auw=960
- 儿童友好空间的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/Mwc=qTD
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/947
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/jux
- 户外活动组织的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/06S
- 乡村产业科普的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/653=ikg
- 地方旅游导览的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/dcf=735
- 周末休闲规划的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/giK=5pV
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/616
- 骑行路线规划的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/jjp
- 社区文化节活动中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/TM1
- 公共服务数字化的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/574=enr
- 公共设施维护的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/dwx=023
- 运动安全知识的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/npZ=K7n
- 基层服务创新的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/753
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/khr
- 社区体育组织的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/uJQ
- 城市博物馆服务的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/457=cxr
- 公共服务预约的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/crh=613
- 本地消费场景的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/2nG=lDa
- 基层医疗预约的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/276
- 个人信息保护的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/txx
- 本地消费场景的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/nlD
- 公共场所导视的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/662=mtz
- 乡村文化活动的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/dhh=963
- 数字素养提升的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/uGF=Awe
- 社区故事采集的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/195
- 社区老年食堂的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/ato
- 传统手工艺体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/ZMN
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/460=fxr
- 节气饮食文化的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/fiz=982
- 邻里共享空间的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/1eK=ogG
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/279
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/dsg
- 社区手工活动的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/Sw5
- 社区养老服务的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/795=vzm
- 数字资源检索的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/dpf=649
- 食品安全科普的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/AEr=7Sz
- 城市空气科普的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/208
- 乡村文化空间的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/yfi
- 物业服务沟通的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/XIy
- 数字政务体验的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/843=nli
- 户外活动组织的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/kiv=907
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/ON0=bd9
- 本地消费场景的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/527
- 社区安全巡查的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/rnr
- 家庭运动计划的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/Hg8
- 城市便民驿站的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/866=idu
- 社区活动策划的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/foo=210
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/YNv=XbH
- 绿色出行服务的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/961
- 城市基础设施的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/zss
- 家庭安全提示的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/4jP
- 物业服务沟通的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/541=qqg
- 公共场馆服务的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/hsg=227
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/blv=cS8
- 个人数据管理的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/128
- 公共交通接驳的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/gti
- 老年学习活动的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/em2
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/441=zuk
- 生活技能分享的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/wqk=577
- 开放数据应用的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/JxL=kfH
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/697
- 社区故事采集的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/acv
- 社区应急准备的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/9K7
- 无障碍出行的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/565=vyv
- 城市地名文化的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/mom=859
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/nTh=LKS
- 全民健身活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/505
- 社区手工活动的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/rzy
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/VfY
- 图书借阅体验的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/681=uaf
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/teo=855
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/py3=EHd
- 公共空间照明的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/229
- 社区活动策划的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/ugp
- 生活垃圾回收的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/9aS
- 社区法律科普的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/223=vbm
- 校园社团活动的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/ttl=997
- 数字公共文化的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/wWW=umH
- 生活垃圾减量的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/458
- 家庭教育交流的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/xmp
- 家庭消费规划的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/Owk
- 社区科普课堂的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/431=qlq
- 青少年户外教育中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/yyk=096
- 环境监测科普的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/D91=FLZ
- 公共设施使用的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/078
- 安全出行教育的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/gjf
- 社区法律科普的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/UXk
- 社区文化传播的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/095=rpv
- 乡村公共服务的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/oxk=925
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/KFa=ySe
- 图书馆活动策划的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/549
- 乡村文化活动的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/tne
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/xyR
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/331=eeg
- 社区交通安全的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/kss=489
- 新能源知识普及的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/7Q1=5D4
- 公交站点体验的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/990
- 城市树木认养的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/ito
- 城市游园体验的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/2Xj
- 远程协作工具的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/497=knk
- 社区法律科普的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/wnk=298
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/jZE=kHa
- 远程协作工具的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/161
- 城乡交通衔接的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/omv
- 城市微更新实践的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/9JD
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/310=ziy
- 数字便民地图的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/uky=592
- 生成式工具使用的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/Pwt=e8h
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/375
- 小区公共照明的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/hmh
- 社区读书角建设的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/JFw
- 通勤路线规划中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/137=zro
- 家庭科学教育的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/tge=899
- 社区设施共享的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/oWn=bwq
- 地方文化传播的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/937
- 公共服务沟通的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/lis
- 家庭运动计划的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/8rn
- 传统手工艺体验的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/169=abc
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/fww=972
- 儿童友好空间的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/GbD=aZc
- 物业服务沟通的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/726
- 社区知识分享的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/zhn
- 本地旅行体验的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/vMH
- 职业技能学习的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/276=bqt
- 社区健康讲座的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/ufx=816
- 环境监测科普的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/M3f=0Jx
- 本地旅行体验的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/045
- 街道综合服务的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/pdi
- 城乡交通衔接的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/qpR
- 居民健康教育的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/437=uig
- 青少年科普实践的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/fvc=869
- 基层健康服务的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP_360%E5%9B%BE%E9%89%B4?/0xW=lOI
- 城市生活记录的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/655
- 农产品消费体验的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/jdh
- 家庭运动计划的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/iF4
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/783=szm
- 线上阅读资源的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/zvc=812
- 全民阅读推广的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/q69=Okr
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/531
- 城市公共标识的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/oqa
- 社区便民服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/CcZ
- 社区教育资源的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/581=jnz
- 电动汽车充电的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/lsk=752
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/2RW=rq0
- 小区停车协商的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/595
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/cul
- 儿童友好空间的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/R4t
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/555=cby
- 个人时间管理的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/tpu=921
- 城市夜间照明的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/gwl=KJn
- 老年人文化生活的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/252
- 城市公共自行车的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/agr
- 家庭阅读计划的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/mVh
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/277=tcd
- 绿色消费选择的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/sog=243
- 科学教育活动的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/7Ij=DC7
- 口袋公园建设的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/394
- 家庭环保行动的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/qya
- 数字生活课堂的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/VvJ
- 老年人出行服务的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/833=zbv
- 社区环保活动的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/kiv=184
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/YCz=LGe
- 基层医疗预约的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/037
- 城市休闲步道的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/yua
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/DtS
- 社区科普课堂的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/431=xrh
- 数字创作工具的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/jfc=027
- 骑行路线规划的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/XgM=JXK
- 小微企业服务的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/967
- 居家防滑改造的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/etg
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/yfU
- 绿色快递包装的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/615=cvg
- 公共服务咨询的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/ayn=557
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/gDA=oed
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/278
- 数字支付体验的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/drm
- 社区公共卫生的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/RMK
- 数字阅读服务的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/498=ykv
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/qzh=117
- 社区互助网络的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/SyN=XtR
- 课后服务体验的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/934
- 社区应急准备的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/gam
- 老年智能设备的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/8HD
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/400=zps
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/puh=986
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E7%AB%9E%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/iem=SGs
- 街区小店体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/278
- 人工智能科普的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/kkt
- 药品使用科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/nR7
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/188=lrl
- 数字素养提升的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/kcb=666
- 社区共享书架的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/BSF=HiC
- 智慧停车服务的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/096
- 公共设施使用的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/pfw
- 社区家校合作的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/8mD
- 社区体育组织的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8D%83%E4%BA%BF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/828=ack

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
