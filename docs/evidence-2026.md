# 为什么这样设计：2026 年的研究依据

> 这套模型的核心判断——"AI 落地是组织问题，不是技术问题"——最早来自一线操盘经验。
> 2026 年下半年，几份大样本研究陆续发布，结论高度一致。这里把它们和模型的每一个设计对应起来。
>
> 说明：以下为对公开报告的转述与概括，数字以原报告为准，链接附后。

---

## 一、"最短板定级"——为什么不取平均

**研究信号**
- 麦肯锡《The state of AI in 2026》：AI 已经进入近九成企业的至少一个职能，但能说出 AI 对利润有正贡献的仍只有约 37%，与上一年几乎持平；拿到显著回报的"高绩效者"始终只有约 6%。
- BCG《2026 Applied AI Index》：约一半公司已经从 AI 拿到价值，但其中只有 7.5% 属于"future-built"（最成熟），其余是"正在规模化"。

**对应设计**
普及率高、回报集中，说明大多数组织**不是整体都差，而是卡在某一处**。平均分会把这一处抹平；最短板定级把它点出来。

---

## 二、维度 03「场景与流程」——重新设计，而不是贴上去

**研究信号**
- 麦肯锡 2026：高绩效者里接近四分之三从根本上重新设计了工作流，其他公司约四分之一。高绩效者也更可能事先定义"什么时候 AI 产出必须过人"。
- 微软《2026 Work Trend Index》：提出人和 AI 协作的几种方式（问答、探索、委派、协作），建议**按任务选方式**，而不是一味追求 agent 自主度最大化；并建议先定义结果，再决定人机怎么分工。

**对应设计**
- L2 的定义里加入"把 AI 贴在旧流程上"——这不算进流程。
- L3 要求"先定结果、再分人机"。
- L4 要求"有意识地选人机协作方式"。
- 证据闸门要求 HITL 率记录。

---

## 三、维度 01「一号位与方向」——收拢，并且进 P&L

**研究信号**
- BCG 2026：future-built 公司把资金集中成单一多年期项目的比例是落后者的 3.5 倍（61% vs 17%），并集中在更少、更高价值的工作流上；95% 的 future-built 公司用 P&L 或业务 KPI 衡量 AI，直接在 P&L 中追踪的公司拿到约三倍的 AI 价值。
- 微软 2026：经理当众使用 AI，能明显提升团队对 AI 价值的感知和对 agent 的信任；但只有约四分之一的 AI 用户认为领导层在 AI 上清晰一致。

**对应设计**
- L3 加入"聚焦 3–4 条核心流程"。
- L4 加入"跨年度统一项目 + P&L/KPI 口径"。
- 证据闸门要求"一号位近一个月 ≥3 次可见亲自使用"。

---

## 四、维度 04「人才与能力」——编制规划与返工税

**研究信号**
- BCG 2026：future-built 公司里一半以上在做"agent 时代的战略编制规划"（哪些岗位该存在），落后者不到五分之一；预计 AI 专职岗位占比会在几年内大幅上升。
- Workday《Beyond Productivity》（2026.1）：AI 省下的时间里接近四成被返工吃掉；最受返工之苦的是 25–34 岁员工；大多数组织不到一半的岗位职责针对 AI 做过更新。

**对应设计**
- L2 加入"省下的时间被返工吃掉"。
- L3 的判据是"写 spec"——事先定义要什么、什么算做完，这是降低返工最直接的能力。
- L4 加入"编制规划按人机分工来做"。
- L5 加入"保住新人成长为专家的路径"（认知公地的悲剧）。

---

## 五、维度 05「激励与文化」——奖励尝试，管好节省的时间

**研究信号**
- 微软 2026：大多数 AI 用户担心掉队，但只有极少数人说自己在结果还不稳时尝试重构工作会被奖励。研究建议"奖励重构，即使早期结果不稳"。
- 微软 2026：组织因素对 AI 成效的解释力约是个人因素的两倍。
- Workday 2026：企业更倾向把 AI 节省再投入到技术而不是员工发展；相当一部分公司直接把节省的时间变成更多工作量。

**对应设计**
- L2 加入"省下的时间直接变成加活"。
- L4 加入"早期结果不稳也被奖励"和"节省时间有计划地再投入"。
- L5 强调"考核结果，不考核使用次数"。

---

## 六、维度 06「治理与韧性」——先装刹车，再给自主权

**研究信号**
- BCG 2026：42% 的公司预计 2030 年前让 agent 不经人工审批自主行动，但目前只有约 5% 具备整套控制；BCG 列出的控制包括清晰的监督与回滚闸门、安全、审计、成本护栏、明确的 agent 归属等，并指出控制做得好的公司从 agent 拿到的价值约是控制薄弱者的三倍。
- 麦肯锡 2026：约五分之一受访者表示 AI 运营成本（含 token 成本）已经在约束使用。
- 中国信通院"2026 智能体十大关键词"把"智能体可信""智能体全栈评估"列为重点方向；信通院同年启动了覆盖 AI 系统的可观测性评估。

**对应设计**
- L3 加入"致命三要素"检查。
- L4 加入 owner、可观测、可审计、可回滚、成本护栏、状态外置。
- L5 保留本模型独有的三项韧性测试（换模型 / 换供应商 / 单点故障）——这是国内企业处境与海外框架差异最大的地方。

---

## 七、第 0 问「工作基质」——本模型独有

**研究信号**
主流框架（包括上面几份报告背后的方法论）几乎都默认协作发生在 IM/协作套件里。这在硅谷成立，但在大量中国大型组织里，真正的决策发生在会议、文档和审批流中。

**对应设计**
在六维之前加一道**不打分的定位题**。它不评判高低，只决定 agent 该嵌在哪、观摩该在哪发生。这是本模型相对海外同类框架的本土差异化点。

---

## 八、证据闸门——只测正在发生的事

**研究信号**
多份 2026 年的成熟度指南都强调：成熟度模型应该测量正在发生的事，而不是计划或愿景；并建议按团队/部门分别测量，而不是只给一个全公司混合分。

**对应设计**
- 自评 L3 及以上必须勾选证据，否则按 L2 计；结果图会同时显示"自评"和"计分"。
- 页面提示按部门/团队分别测。
- 每次复测配合 [`honest-metrics.md`](./honest-metrics.md) 里的四个数。

---

## 来源

- McKinsey & Company, *The state of AI in 2026: On the road to ROI* (2026.8) — https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai
- BCG, *The Formula for Agentic AI Value* / 2026 Applied AI Index (2026.9) — https://www.bcg.com/publications/2026/the-formula-for-agentic-ai-value
- BCG 新闻稿 (2026.9.30) — https://www.bcg.com/press/30september2026-ai-starting-to-pay-off-companies-generate-value
- Microsoft, *2026 Work Trend Index* (2026.6) — https://news.microsoft.com/source/asia/2026/06/08/2026-work-trend-index-report-reveals-how-frontier-firms-are-rebuilding-the-operating-model-for-the-age-of-ai/
- The Neuron 对 2026 Work Trend Index 的解读 — https://www.theneuron.ai/explainer-articles/microsofts-2026-work-trend-index-your-employees-figured-out-ai-your-company-didnt/
- Workday, *Beyond Productivity: Measuring the Real Value of AI* (2026.1) — https://newsroom.workday.com/2026-01-14-New-Workday-Research-Companies-Are-Leaving-AI-Gains-on-the-Table
- 中国信通院"2026 智能体十大关键词" — https://www.secrss.com/articles/91447
- Larridin, *AI Maturity: The Complete Enterprise Guide (2026)* — https://larridin.com/solutions/ai-maturity-the-complete-enterprise-guide-2026

---

*会灵那 / wilingna · 20 年 HR 与组织设计 · 专做 AI 在企业里的真落地*
