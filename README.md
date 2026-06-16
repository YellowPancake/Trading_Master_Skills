# Trading Master Skills · 投资大师认知蒸馏 Skills

> 把投资大师的**认知操作系统**（心智模型 + 决策启发式，而非语录堆砌）蒸馏成可复用的 Claude Code / AI Agent Skill。
> Distilled *cognitive operating systems* of legendary investors — mental models & decision heuristics, not quote-dumps — as reusable AI agent skills.

23 位大师/流派，每个都是一份结构统一、可直接喂给 AI Agent 的投资方法论底座。源自 **InvestAgents**（多门派自我进化投资 Agent 生态）项目的内部蒸馏。

---

## ⚠️ 免责声明（请先读）

本仓库是基于**公开信息**对投资风格的**第三方提炼**，**非任何本人授权或确认**。所有内容**仅用于 AI/研究/教育**与投资风格观察，**不构成任何投资建议**。部分风格（如卡脖子小盘、短线游资）**极度激进、高风险，不可照搬**。任何真实投资决策风险自负。A股流派一律以**风格档**呈现（不指向具体在世人物）。

---

## 📜 大师 / 流派清单

### 美股 `skills/us/`（11 位真人 + 1 位新锐）

| Skill | 原型 | 风格内核 |
|------|------|------|
| `buffett_value` | Warren Buffett | 宽护城河 + 安全边际 + 永久持有 |
| `munger_quality` | Charlie Munger | 多元思维模型 + 逆向 + 质量优先 |
| `lynch_growth` | Peter Lynch | 六类公司分类 + PEG + tenbagger |
| `graham_deepvalue` | Benjamin Graham | 深度低估 + 烟蒂 + NCAV + 安全边际 |
| `soros_macro` | George Soros | 反身性 + 盛衰循环 + 不对称下注 |
| `dalio_allweather` | Ray Dalio | 全天候 + 风险平价 + 分散圣杯 |
| `druckenmiller_macro` | Stanley Druckenmiller | 流动性驱动 + 高确信集中重仓 |
| `marks_contrarian` | Howard Marks | 第二层思维 + 周期定位 + 防御 |
| `livermore_trend` | Jesse Livermore | 顺势 + 关键点突破 + 金字塔加仓 |
| `simons_quant` | Jim Simons | 数据驱动 + 多因子 + 去情绪纪律 |
| `wood_disruption` | Cathie Wood | 颠覆性创新 + Wright's Law + 5年视角 |
| `serenity_chokepoint` | Serenity（白毛股神）| 卡脖子 + AI 半导体上游小盘隐形冠军 |

### A股 `skills/cn/`（2 位真人 + 9 个风格档）

| Skill | 原型 | 风格内核 |
|------|------|------|
| `duanyongping_value` | 段永平（大道无形我有形）| 本分 + 买股票就是买公司 + 能力圈 |
| `liyien_aihardware` | 李一恩 | AI 硬件主线龙头 + 确定业绩爆发 + 拿着别动 |
| `baima_quality` | 风格档 | 核心资产白马龙头 + 高 ROE + 长期持有 |
| `track_growth` | 风格档 | 高景气赛道 + 自上而下选赛道选龙头 |
| `macro_cycle` | 风格档 | 宏观周期 + 美林时钟 + 板块轮动 |
| `youzi_trend` | 风格档 | 短线情绪 + 龙头战法 + 量价（高风险）|
| `rotation` | 风格档 | 行业比较 + 景气切换 + 相对强弱 |
| `factor_quant_cn` | 风格档 | 多因子打分 + 分散 + 纪律调仓 |
| `dividend_yield` | 风格档 | 高股息 + 派息可持续 + 防御 |
| `lowval_dividend` | 风格档 | 低 PE/PB + 安全边际 + 价值回归 |
| `contrarian_left` | 风格档 | 弱者体系 + 赔率思维 + 左侧逆向 |

---

## 🧬 蒸馏方法论（每个 Skill 的统一结构）

借鉴业界优秀实践（提取认知 OS、承认内在张力、来源分级、证伪前置），每个 skill 含 12 节：

1. **世界观 / 投资信仰** — 第一性的底层信念
2. **心智模型** — 该大师的核心 mental models（表格化）
3. **决策启发式** — 可执行的判断规则
4. **分析框架 / 检查清单** — 选股/分析的具体步骤
5. **选股筛选器** — ✅ 正向命中 + 🚩 风险红旗
6. **仓位 / 风控 / 持有纪律**
7. **卖出 / 退出逻辑**
8. **内在张力 / 边界** — 诚实写出矛盾，拒绝脸谱化
9. **表达风格 DNA**
10. **输出契约** — 结论分档 → 事实基底 → 判据 → 风险 → 估值/情景档 → **证伪条件** → 来源分级
11. **与 Agent 系统集成**
12. **免责声明**

**核心原则**：提取**可复用的认知框架**，不是语录；**承认大师的内在矛盾**（如巴菲特"永久持有"却清仓航空、木头姐 ARKK 的巨幅回撤），避免理想化失真；关键数据**来源分级**（一手/管理层声称/推断/推测）；每个结论都给**证伪条件**。

---

## 🚀 用法

1. **Claude Code Skill**：把对应 `.md` 放进你的 skills 目录，在对话里触发"用 XX 的视角分析……"。
2. **Agent 人格底座**：作为投资 Agent 的方法论 prompt 注入到调研/决策环节。
3. **研究 / 对照**：理解不同流派如何看同一只票，做风格对照。

---

## 🔗 来源

源自 [InvestAgents](https://github.com/YellowPancake) 项目——让每个人都能养一群自我进化、不同风格的投资大师 Agent。本仓库是其方法论蒸馏层的开源分享。

## 📄 License

[MIT](LICENSE) · 代码/文本可自由使用，但请保留免责声明，且**不得作为投资建议传播**。
