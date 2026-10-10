# Matthew Dolan：近期论文、课题查询与套磁准备

**Last-verified：2026-10-06。** 对应 [letter.md](letter.md) 与 [Melbourne 导师档案](README.md)。首选导师为 **Professor Matthew Dolan**，School of Physics, University of Melbourne；目标为 **2027 Master of Science (Physics)**。研究匹配 **High**，录取难度 **Unknown**：具体成绩等效、项目和指导容量未确认。邮件为未发送草稿，contact status 保持 **not contacted**。

本说明参照 [McGill 阅读笔记](../01-mcgill-jim-cline/paper_reading_notes.md) 的结构。英文邮件沿用 [Cline 信件](../01-mcgill-jim-cline/letter.md) 的身份介绍、具体论文兴趣、三项研究经历、硕士目标与招生询问顺序，以当前 [英文 CV](../../CV/CV_en.md) 为个人经历依据。申请人的论文阅读与复现进度未确认，因此信中只表达对具体问题的兴趣。

## 1. 检索范围与近期论文

本轮直接通过 HTTPS 查询研究中心官方个人页、INSPIRE 作者索引和 arXiv 原文。先按姓名检索，再核对作者标识 **M.J.Dolan.1 / INSPIRE 1056030**、Melbourne affiliation 与 ORCID **0000-0003-3420-8718**，避免与其他 Dolan 作者混淆。作者索引用于发现论文，以下内容和版本信息以 arXiv 原始记录为依据。

截至核查日，按初次提交时间排序，本次检索到的最新预印本为 **Towards Measuring the CP-Violating Phase with Atmospheric Neutrinos**（2026-05-16）。这不代表已排除所有尚未被索引的新稿。论文的初版、修订和期刊发表年份分开记录，不能把 2024 年 arXiv 编号直接当作期刊发表年份。

| 论文 | 核实的日期 / 状态 | 主要内容与用途 |
|---|---|---|
| **Towards Measuring the CP-Violating Phase with Atmospheric Neutrinos** — John F. Beacom, Nicole F. Bell, Matthew J. Dolan, Stephan A. Meighen-Berger, Ho Man Yim | 初版 2026-05-16；v2 2026-06-18；本轮 arXiv 页未列期刊信息 | 利用 sub-GeV atmospheric neutrinos 的 up-down ratio 约束 δCP，计入探测效应并减少部分系统误差。**最新工作补充阅读**，可了解其可观测量设计与物理推断方向；不是 collider ML 论文。https://arxiv.org/abs/2605.16721 |
| **Irreducible Constraints on Hadronically Interacting Sub-GeV Dark Matter** — Peter Cox, Matthew J. Dolan, Avirup Ghosh | 初版 2025-12-23；v2 2026-04-17；v2 注明修正数值错误并更新图，结论不变 | 以 low-energy chiral effective theory 连接暗物质的强子作用与不可避免的电磁作用，组合 BBN、freeze-in 与 meson-decay 约束。用于了解当前暗物质现象学主线。https://arxiv.org/abs/2512.20825 |
| **Photonic Freeze-In** — Peter Cox, Matthew J. Dolan, Frederick J. Hiskens | 初版 2024-12-23；v2 2026-07-06；Phys. Rev. D 113, 115031 (2026) | 光子湮灭产生暗物质，讨论低 reheating temperature 和直接探测、SN1987A、LHC 检验。用于了解近期发表的研究；本轮只核摘要与版本信息。https://arxiv.org/abs/2412.17308 |
| **New Limits on Light Dark Matter-Nucleon Scattering** — Peter Cox, Matthew J. Dolan, Joshua Wood | 初版 2024-08-22；v2 2025-12-16；Phys. Rev. D 112, 115021 (2025) | 以 BBN、freeze-in 与 rare kaon decays 限制轻暗物质散射；是上一轮档案中的研究入口，本次补正期刊年份。https://arxiv.org/abs/2408.12144 |
| **Quark-versus-gluon tagging in CMS Open Data with CWoLa and TopicFlow** — Matthew J. Dolan, John Gargalionis, Ayodele Ore | 初版 2023-12-06；v2 2025-08-07；JHEP 08 (2025) 024 | 比较模拟与真实数据上的 fully-supervised / weakly-supervised jet tagging；**首读与当前邮件唯一引用论文**。https://arxiv.org/abs/2312.03434 |

主选论文虽不是最新初版，但在 2025 年发表，且与申请人的 Higgs ML 评价问题更接近。最新中微子论文单列为补充，另三篇暗物质工作作为研究背景，不把所有论文塞进首封信。

## 2. 主选论文与原文定位

- 摘要、作者、版本及期刊记录：https://arxiv.org/abs/2312.03434
- 本轮读取的 v2 全文：https://arxiv.org/html/2312.03434v2
- PDF：https://arxiv.org/pdf/2312.03434v2
- DOI：https://doi.org/10.1007/JHEP08(2025)024

**核心问题：** 在真实数据没有逐事件 quark/gluon 标签时，如何训练、评价分类器？在模拟中表现最好的方法，是否仍在真实数据上最好？作者使用 CMS 2011 年公开数据中的 Z+jet 与 dijet 混合样本，分别富集 quark 和 gluon jets，比较监督学习、CWoLa 与 TopicFlow。

| 原文位置 | 应读的内容 | 与申请人工作的联系 / 边界 |
|---|---|---|
| Introduction；Section 1 | jet substructure 的模拟失配动机，以及 Z+jet / dijet 数据选择 | 可联系模型评价的物理适用性；该文使用真实 CMS 数据，申请人当前 Higgs 研究只使用 ATLAS public MC |
| Sections 2.1–2.3 | CWoLa、jet topics、TopicFlow；混合分布与潜在类别之间的关系 | 需要学习 weak supervision 与 normalizing flows；现有 MLP / Shapley 经历不等于已掌握这些方法 |
| Section 4.1；Fig. 5–7；Table 4 | sample independence、mutual irreducibility，以及 S/T/R 三种 quark-fraction 假设 | 与“假设如何影响结论”的工作习惯相连；三种 fractions 是模型假设下的估计，不是真值标签 |
| **Section 4.3；Fig. 9；Table 5** | 在 MC 与 data-derived 评价之间，fully-supervised 与 Data CWoLa 的优劣排序反转；三种 mixture-fraction 方案下排序一致 | **当前邮件的具体切入点**。申请人发现的是 AUC 与 signal-strength interval width 排序不总一致，两者不是同一种反转机制 |
| Section 4.3；Fig. 10 | TopicFlow 生成样本平滑 SIC 曲线；比较统计波动与类别比例假设带来的变化 | 可联系有限样本下评价是否稳定；生成更多样本不等于获得更多独立实验信息 |
| Section 4.1 与 Section 5 | 论文将结果视为探索性的 estimates；不确定性以统计项为主，未完整评估系统误差，也未量化 sample-independence 违背的影响 | 不可写成弱监督普遍优于监督学习，或已解决完整实验系统误差 |

**最值得掌握的结果：** Table 5 中 Fully Supervised 的 MC AUC 为 0.768，高于 Data CWoLa 的 0.707；在 Data (S) 下，两者分别为 0.658 和 0.730。Data (T)/(R) 也保留这两者的排序反转。不同 fractions 会改变绝对评价值，而在文中三种设置下，分类器排序保持稳定。这些结果属于文中数据选择、分类器和假设，不是通用性能保证。

首封信不必引用数值，申请人应能解释 Fig. 9 中横纵轴、S/T/R 的含义和 data-derived 性能如何估计。

## 3. 与 Higgs / MaNGA 经历的具体连接

| 本人已做工作 | 可以自然提出的后续问题 | 不应声称的经历 |
|---|---|---|
| 在模拟 H → ZZ* → 2e2μ 中比较 MLP 特征组，并通过 pyhf 评价信号强度区间 | 分类性能、数据来源与物理推断目标如何共同决定模型选择？ | 没有做过该文的 CMS quark/gluon 测量，也没有据现有项目确认 simulation-to-data domain shift |
| exact Shapley、event-group bootstrap、conditional coverage diagnostics | 有限样本和建模假设怎样影响比较结果的稳定性与区间可靠性？ | 尚未完成完整实验系统误差预算，不能称已获得校准的精度提升 |
| MaNGA 的 PyMC 晕参数与群体 c–M 推断 | 可展示统计建模、不确定性传播与科学计算经验 | 宏观晕推断不等于 chiral EFT、freeze-in、QCD 或粒子直接探测经验 |

邮件以 Higgs 为主、MaNGA 为补充。Higgs 手稿按当前 CV 写 **first-author manuscript in preparation**，不声称已投稿或发表；代码地址沿用 CV：https://github.com/hyi03/HiggsML 。本轮未重新审计代码或运行分析，也未独立核验作者顺序。旧研究背景档案中的待确认作者信息不用于覆盖较新的 CV 表述。

## 4. 课题查询：已经公开的方向与可询问的 MSc 题目

研究中心官方个人页确认 Dolan 在 Melbourne，从事 dark matter phenomenology 与新的 collider analysis methods，并列联系邮箱 **matthew.dolan@unimelb.edu.au**。该页发布时间较早，因此具体近期活动再由上述 2025–2026 论文支撑。

- 官方个人介绍：https://www.centredarkmatter.org/all/matthew-dolan
- 2026 中微子论文作者栏也列同一邮箱：https://arxiv.org/html/2605.16721v2

原 [README](README.md) 所引 2026 Physics Research Prospectus（印刷页 12）记录 collider machine learning 方向，但本轮该 PDF 与大学个人页访问受限，未把旧摘录当成本轮重新读取。**本轮未核到 Dolan 已公布的 2027 MSc 具体题目、空缺数或个人经费承诺。** 以下是基于原文提出的沟通方向，均需导师确认能否纳入 MSc。

| 优先级 | 适合询问的题目范围（个人提议） | 已核研究依据 | 可用基础与需补内容 |
|---|---|---|---|
| **1** | Collider ML 的评价稳定性：有限样本、混合比例与模型假设变化如何影响 classifier ranking | 主选论文 Fig. 9–10；Section 5 的 sample dependence 后续方向 | 可迁移多种子比较、bootstrap 与评价流程；需补 jet physics、weak supervision、样本定义与相关 QCD 知识 |
| **2** | 在导师认可的 Higgs / collider 算例中，比较 classification metrics 与物理参数约束，并研究 nuisance parameters 的作用 | 官方 collider analysis methods 方向，以及申请人当前 Higgs 工作；**不是该论文已经执行的 pyhf / Shapley 项目** | 有 MLP / profile likelihood 基础；具体过程、simulation tools、系统误差模型与理论先修需商定 |
| **3** | 中微子可观测量的敏感度与理论误差传播，例如 up-down ratio 的假设如何影响 δCP 约束 | 最新 2026 论文对 flux / cross-section uncertainties 和未来优化的明确讨论 | 统计推断方法可迁移；需先学习 neutrino oscillations、通量与探测响应。仅作为非天体粒子物理备选 |

最新中微子论文的摘要与正文指出：up-down ratio 减少部分共同归一化误差，其 cos δCP 敏感度与 T2HK 的主要 sin δCP 敏感度互补；要实现预测能力仍需改进低能大气中微子通量、微分截面等理论不确定性。原文 Fig. 3 是预期灵敏度，不是实验已完成的 δCP 测量。不能因为该文使用 likelihood 就声称其采用 pyhf 或与申请人的 Higgs 推断完全相同。

暗物质 EFT / freeze-in 可以了解，但目前不是最适合首封信的能力切入点；尚无经核实的相关场论研究经验。未确认个人 grant 的当前有效期或可用于 MSc 的金额；论文致谢或研究中心资助不能视为学生 funding offer。

## 5. 建议阅读顺序与讨论准备

1. **主选论文摘要、Introduction、Section 5。** 用自己的话解释为什么 MC 性能不足以代表真实数据性能。
2. **Fig. 9、Table 5、Section 4.3。** 说明两种分类器的排序怎样改变；区分 AUC、SIC 和申请人自己的 profile-likelihood interval width。
3. **Table 4、Section 4.1、Section 2。** 理解 S/T/R 假设、sample independence 与 mutual irreducibility；不要只记算法名称。
4. **Fig. 10 和 Section 5 的后续方向。** 解释有限统计、生成模型平滑与系统误差之间的区别。
5. **补充读 2026 中微子论文摘要、Fig. 2–3、Conclusions and Next Steps。** 了解导师最新推断问题；初次邮件不必同时讨论中微子与 jets。

后续交流可准备三个问题，每次选择与导师回复最相关的一项：

- 是否有 MSc 可完成的 collider ML 项目，允许系统检查模型评价对有限样本和建模假设的敏感性？
- 若从 jets 或其他 collider 过程入手，入组前最需要补足哪些理论课程和软件工具，谁提供日常指导？
- 是否适合把分类器的选择与后续物理参数约束联系起来，或组内已有更明确的研究问题供 MSc 学生开展？

这些问题旨在确认研究范围与指导条件，不预设导师承诺接收或同意开展申请人当前题目的延续。

## 6. 邮件措辞、入学时间与申请流程

当前邮件用论文中的 **simulation/data classifier ranking reversal** 建立兴趣，再用本人 **AUC/interval-width comparison** 说明相关思考，并明确二者是不同问题。研究目标是 computational particle physics、collider phenomenology 与 statistical inference，不沿用 McGill 的 DDO 154 / core–cusp 叙述。

- **时间：** 预计 2027 年 6 月毕业；信中写 **2027 entry**，未擅自选择 March 或 July。此前档案列 March / July intake；若按现有毕业时间安排，应先确认 mid-year intake 是否可行及其材料截止，再确定具体月份。
- **附件：** 沿用基础信的 “My CV is attached.”；实际发送时附当前英文 CV。尚未附上附件，也未发送。成绩单沿用本批暂缓安排，导师要求时再补。
- **Supervisor Form：** 本轮读取目录内 [MSc-Physics-Supervisor-Form_2026_v3.docx](MSc-Physics-Supervisor-Form_2026_v3.docx) 正文。文件标题为 *Master of Science (Physics) Supervisor Expression of Interest (EOI) Form*，明确申请前无需先安排项目或落实导师；录取后由潜在导师联系讨论，通常在申请截止后一至两周开始。表格要求分别排序至少四位 Teaching and Research 导师与至少四个不重复研究领域，分配不保证满足偏好。
- **来源冲突：** 既有 README 从招生网页摘录了申请前直接联系导师的要求；本地 2026 v3 表格则明确无需预先落实。本轮网页和远程表格均返回 403，无法在线确认哪份适用于 2027。应保留冲突并以届时项目说明或院系答复确认，不能将套磁写成必须索取预先签字的步骤。主动咨询研究适配仍有价值。

本轮只读表格，未填写或提交；也不因为至少四位导师已列出，就认为至少四个研究领域要求已经满足。

## 7. 来源与核查范围

**2026-10-06 成功通过 HTTPS 读取：**

- 研究中心个人页：https://www.centredarkmatter.org/all/matthew-dolan
- 作者索引查询：https://inspirehep.net/api/literature?q=a%20M.J.Dolan.1&sort=mostrecent&size=10
- 主选论文摘要及全文：https://arxiv.org/abs/2312.03434 ；https://arxiv.org/html/2312.03434v2
- 最新工作摘要及全文：https://arxiv.org/abs/2605.16721 ；https://arxiv.org/html/2605.16721v2
- 其他三篇摘要、版本与期刊信息：https://arxiv.org/abs/2512.20825 ；https://arxiv.org/abs/2412.17308 ；https://arxiv.org/abs/2408.12144

**本轮访问受限，未据拦截页确认正文：**

- 大学个人页：https://findanexpert.unimelb.edu.au/profile/717664-matthew-dolan （HTTP 200 但正文为 Incapsula 拦截）
- 研究组页：https://physics.unimelb.edu.au/research/research-areas/theoretical-particle-physics （403）
- 2026 Research Prospectus：https://science.unimelb.edu.au/__data/assets/pdf_file/0005/4037072/2026-Physics-ResearchProspectus-FINAL.pdf （403）
- Entry requirements：https://study.unimelb.edu.au/find/courses/graduate/master-of-science-physics/entry-requirements/ （403）
- Supervisor Form 远程链接：https://matrix-cms.unimelb.edu.au/__data/assets/word_doc/0023/437810/MSc-Physics-Supervisor-Form_2026_v3.docx （403；正文核查使用用户目录中已有的本地副本，未在线核验其与当前服务器文件完全一致）

本轮不重新核定学费、资助、成绩等效或 2027 正式截止日期；这些待确认项保留在 [README](README.md)。
