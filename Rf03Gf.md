# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 农业科普体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/630
- 生成式工具使用的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/jem
- 街头绿植养护的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/w2q
- 社区便利生活的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/469=ekq
- 社区花园共建的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/ptl=315
- 家庭运动计划的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/Bjb=2Fs
- 社区公共餐饮的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/451
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/hoz
- 创业经验分享的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/YDv
- 城市绿色交通的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/922=gqh
- 新能源出行的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/gqt=438
- 校园节能行动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/dzV=o2s
- 电子商务服务的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/438
- 绿色建筑理念的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kce
- 新能源知识普及的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mXd
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/179=anf
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/muq=091
- 城市建设科普的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yc3=3NG
- 绿色生活实践的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/539
- 数字素养提升的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ihz
- 科学健身方法的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/5jo
- 城市雨天出行的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/774=gjd
- 食品配送体验的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/oya=492
- 城市休闲步道的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/KT0=ChP
- 网络安全教育的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/441
- 社区安全巡查的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/mgo
- 社区生活指南的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/8Z0
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/042=hnt
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/pct=358
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/FlN=A8H
- 城市博物馆服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/903
- 街区绿化养护的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/ohm
- 公共卫生设施的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/Ez2
- 家庭教育交流的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/365=xme
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/qio=172
- 社区文化节活动的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/JMX=5LU
- 城乡公共服务的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/558
- 儿童友好空间的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vbh
- 城市地名文化的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/29E
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/171=ojm
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jdy=145
- 儿童阅读角的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Xa7=yl2
- 数字生活课堂的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/008
- 城市公共饮水的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/udm
- 医院导诊服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/rD7
- 青年志愿活动的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/749=oif
- 社区安全巡查的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/ggx=162
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/A6W=dM9
- 老年学习活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/018
- 乡村教育资源的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/frm
- 数字生活课堂的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/RwF
- 社区公共议事的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/237=ehv
- 青少年户外教育的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/vrm=664
- 城市微更新实践中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/Ndr=tHv
- 社区体育组织的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/439
- 公共服务预约的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/qde
- 学校食育活动的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/KGg
- 城市应急广播的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/264=bgf
- 城市公共标识的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/wsx=159
- 城市可持续生活的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/aMx=22v
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/091
- 城市公共自行车的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/kfv
- 非遗体验活动的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/61w
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/935=mrt
- 绿色办公实践的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/ewq=432
- 家庭教育交流的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/u4t=skX
- 乡村公共服务的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/158
- 社区健康讲座的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/iji
- 社区知识分享的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/H1v
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/903=yny
- 社区心理支持的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/eia=138
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%82%A1%E7%A5%A8?/n0r=yag
- 老年数字阅读的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/480
- 通勤路线规划中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/yvl
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/5X1
- 街区绿化养护的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/840=eew
- 居家适老化改造的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/fuz=792
- 青年就业服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/o8B=aD9
- 无障碍信息设计的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/089
- 街区道路维护的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/nut
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/giX
- 科学运动指导的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/687=fmy
- 城市基础设施的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/van=959
- 公共场所导视的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/4i2=fud
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/451
- 城市展览体验的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/vgf
- 街区更新实践的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/PYt
- 公共服务预约的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/679=zii
- 社区信息发布的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/jjz=683
- 城市博物馆活动的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%BF%AB%E6%8A%A5?/2b9=Xud
- 开放式学习空间的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/698
- 数据分析入门的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/yno
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/h1r
- 社区生活指南中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/916=rvu
- 智能手机助老中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/wxh=755
- 文化场馆预约的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/FHA=NVa
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/963
- 社区消防演练的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/nek
- 公交站点体验的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/KYb
- 社区家校合作的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/614=iqv
- 数字创意课程中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/mln=706
- 城市公共自行车的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/n9f=34f
- 绿色校园实践的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/545
- 图书借阅体验的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/yvc
- 校园安全教育的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/lys
- 社区活动报名的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/672=pmg
- 社区运动空间的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/slt=278
- 乡村生活观察的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/6il=5ga
- 个人时间管理的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/268
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/sgi
- 社区家政服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/gpy
- 数字便民地图的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/579=ntp
- 公共设施维护的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/dzs=591
- 数字公共文化的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/HA7=hFE
- 家庭健康管理的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/643
- 图书馆数字服务的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/dwo
- 社区活动策划的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/kQk
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/629=ydv
- 全民健身活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/bqd=967
- 劳动教育实践的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/Gqn=qnJ
- 乡村生活观察的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/383
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/tra
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/tCB
- 亲子科普活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/834=wlv
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/lxe=935
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/9Un=Yc3
- 终身学习资源的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/329
- 社区商业活力的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/uqq
- 城市文明出行的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/OMQ
- 街区道路维护的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/051=vxt
- 机器人科普活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/hic=341
- 急救知识普及的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/KCB=cPv
- 城市噪声观察的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/358
- 光伏知识科普的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/wbr
- 家庭健康科普中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/FU0
- 在线教育体验中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/253=yxo
- 健康信息获取的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/zls=211
- 绿色出行服务的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/yee=iQM
- 城市微更新实践的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/146
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/qsa
- 节气饮食文化的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/bXK
- 家庭节能实践的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/867=hox
- 社区体育组织的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/iim=031
- 老年数字阅读的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/kZW=9ca
- 公共场所导视的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/533
- 社区教育资源的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/hro
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/Fww
- 数字创作工具的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/036=ytl
- 机器学习入门的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/fsc=490
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/7f8=lH1
- 数字便民地图的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/881
- 社区停车服务的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/ydj
- 无障碍出行的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/kfh
- 城市绿色交通的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/164=yob
- 药品使用科普的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/wfk=287
- 老年友好服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/8uR=gqE
- 城市树木认养的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/581
- 城市水环境观察的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/iej
- 文明养宠科普的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/mBc
- 城市可持续生活的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/831=rsa
- 绿色生活实践中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/pvl=246
- 社区学习活动的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/Vcl=luS
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/725
- 青少年科普实践的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/kzp
- 家庭照护支持的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/HjX
- 开放数据应用的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/695=lfi
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/lmb=377
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/8kX=S21
- 环境监测科普的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/243
- 便民维修服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/ykq
- 公共服务沟通的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/zTX
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/747=qcg
- 老年友好服务的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/onz=785
- 社会体育指导的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/wWh=IXe
- 社区邻里服务的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/900
- 农业科普体验的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/qht
- 家庭健康科普的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/kAt
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/758=qcc
- 城市骑行环境的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/hdg=183
- 数字生活课堂的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/Sxz=V2l
- 本地历史资料的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/789
- 社区手工活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/vkx
- 城市社区治理的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/5lw
- 公共服务预约的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/430=wdg
- 网络安全教育中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/tan=601
- 基层医疗预约的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/81x=6WH
- 城市基础设施的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/976
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/hwx
- 邻里互助活动的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/jkv
- 健康信息获取的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/060=obw
- 居家防滑改造的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/mjd=517
- 文明养宠科普的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/6Ju=qmz
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/371
- 城市微更新实践的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/imr
- 城市夜间生活的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/5MF
- 家庭用电安全的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/508=wfg
- 社区读书角建设的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/sxf=993
- 家庭照护支持的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/Igc=bO7
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/789
- 公共服务预约的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/zcm
- 城市水环境观察的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/Wy2
- 电动汽车充电的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/186=rzm
- 社区慢性病防控的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/hpl=639
- 数字政务体验的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%AF%BB%E5%9B%BE?/v1Z=3tJ
- 开放式学习空间的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/098
- 社区家校合作的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/xpl
- 儿童阅读角的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/m7u
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/419=aox
- 科学教育活动中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/rfh=345
- 数字档案服务的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/zZ0=koa
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/089
- 数字支付体验的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/etg
- 小微企业服务的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/QHo
- 社区生活指南的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/563=sri
- 社区快递服务的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/rkq=830
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/eBj=nMU
- 光伏知识科普的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/531
- 社区垃圾分类的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/svz
- 乡村文化活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/7XK
- 图书馆数字服务的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/379=hka
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/ovs=642
- 社区应急准备的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/fbg=JDK
- 数字学习资源的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/922
- 便民维修服务的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/yso
- 公共场馆服务的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/pum
- 家庭健康科普的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/461=iai
- 乡村文化活动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/pyw=128
- 公共设施使用的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/a2N=pN1
- 乡村教育资源的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/872
- 社区生活指南的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/sdz
- 社区共享书架的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/4sE
- 公共服务指南的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/095=faa
- 生活服务数字化中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/pfd=706
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/nUg=Ju6
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/023
- 生活垃圾回收的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/iiy
- 数据分析入门的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/ARI
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/918=gon
- 社区生活指南的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/iru=244
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/egC=f8H
- 便民维修服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/482
- 运动安全知识的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nac
- 文明养宠科普的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/JAV
- 城市绿道建设的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/656=cmh
- 社区共享书架的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/yxl=099
- 通勤路线规划的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/Fg1=aZv
- 城市便民驿站的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/637
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/ghh
- 休闲运动入门的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/4sl
- 乡村生态观察的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/614=jgo

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
