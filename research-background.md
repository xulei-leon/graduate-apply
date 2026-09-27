# 科研背景与申请叙事

最后核对：2026-09-27。第二课题依据 2026-09-26 论文草稿及 test05 证据索引更新；本次未重新运行实验或独立验证统计结论。

## 两段科研的共同主线

申请人的研究主线是计算物理：从复杂物理数据中建立模型、推断参数，并检验不确定性和结果可靠性。

| 课题 | 物理问题 | 方法 | 当前证据 |
|---|---|---|---|
| MaNGA 暗物质晕 concentration–mass relation | 由星系运动学约束暗物质晕结构 | Python、PyMC 5、Bayesian MCMC、群体参数推断 | 第一作者手稿准备提交 arXiv；已有公开项目主页，状态沿用既有档案 |
| Higgs 四轻子运动学特征归因 | 不同运动学输入如何影响模拟 H → ZZ* → 2e2μ 的信号强度 μ 推断 | MLP、特征组消融、pyhf profile likelihood、exact Shapley attribution、event-group bootstrap、覆盖率诊断 | 已有论文草稿和完整 test05 名义计算及评估结果；结论仍属探索性 |

两段工作通过统计推断、科学计算和不确定性分析相连。第一课题是暗物质天体物理；第二课题是 Higgs 模拟分析，不应描述为暗物质探测、BSM 模型构建或宇宙学理论研究。第二课题使用频率学派 profile-likelihood 区间，不应统称为 Bayesian MCMC。

## 第二课题：可核实的内容

论文原题：*Kinematic feature attribution for signal-strength inference in simulated H → ZZ\* → 2e2μ events*。

| 字段 | 内容 |
|---|---|
| 指导关系与时间 | 沿用既有记录：与 UCL 物理教授一对一合作，2026 年 5 月开始；草稿的作者、机构和联系信息仍是占位符，不能据此补出导师姓名 |
| 核心问题 | 分类性能较好的运动学表征，是否也能在固定推断流程中得到更窄的信号强度区间？哪些特征组对该流程的表现有贡献？ |
| 数据 | ATLAS 2020 open data collection 中两份 13 TeV Monte Carlo 样本：signal DSID 345060 `ggH125_ZZ4lep`；background DSID 363490 `llll`；不使用真实碰撞数据 |
| 分析范围 | 恰好 2e2μ，105 ≤ m4ℓ < 140 GeV，名义积分亮度 10 fb⁻¹；只包含上述信号与背景，不代表完整实验分析 |
| 输入 | 共 19 个变量：A 单轻子运动学 8 个；B 双轻子运动学 4 个；C 四轻子整体运动学 2 个；D 角变量 5 个 |
| 分类模型 | MLP，hidden widths 64/64/32，LayerNorm、SiLU、dropout、AdamW；15 个非空特征组组合 × 5 个训练种子，共 75 个网络，加 constant-score reference |
| 质量处理 | 分类器排除显式 m4ℓ 输入，但没有证明 mass independence 或完成 mass decorrelation；执行的 likelihood 是 105–140 GeV 单质量箱，非空组合使用两个 score 类别 |
| 推断与归因 | pyhf 0.7.6、T1 有限模板统计近似、Asimov 68% profile-likelihood interval width W68；exact Shapley decomposition、24 个条件交互和 105 对非空子集比较 |
| 可复现设计 | 按物理事件组划分 training / validation / calibration / template / assessment；固定结果快照、产物身份及哈希；signed yields 与优化用绝对权重分开处理 |
| 评估 | 五个种子共享 MC；200 次 event-group bootstrap 固定已训练网络；model-self、assessment 和 T2 条件 pseudo-experiment 覆盖率诊断 |
| 稿件状态 | 2026-09-26 草稿已有方法、结果、图表及证据索引；作者排序、个人任务分工、投稿/接收状态未确认，永久外部归档待完成 |

旧档案中的 JetClass top tagging、PET / OmniLearn、jet foundation models 属于此前记录，不能继续充当当前论文的课题、数据或模型描述；本稿也不支持将数据效率、迁移学习或基础模型训练列为已完成成果。

## 已有结果及表述边界

在 μ=1 的名义 T1 Asimov 比较中，以下 W68 为五个训练种子的中位数；相对基线的缩减先逐种子计算再取中位数。

| 表征 | 变量数 | W68 | 相对 constant-score reference 的名义缩减 |
|---|---:|---:|---:|
| Constant-score reference | 0 | 1.66372 | — |
| BC | 6 | 1.51162 | 9.14% |
| AC | 10 | 1.51524 | 8.92% |
| ABCD | 19 | 1.53593 | 7.68% |

BC 和 AC 在五个同种子比较中均比 ABCD 的名义区间更窄。Exact Shapley 的名义结果中 B、C 贡献最大，D 为负；AUC 与区间宽度的排序不完全一致。80/80 nominal、36/36 evaluation units 和 200/200 bootstrap replicas 均数值有效。

上述结果只支持把 BC、AC 作为后续研究的紧凑输入候选：

- BC/AC 相对 ABCD 的 95% MC 配对宽度差范围均跨零，不能声称统计显著优于全输入；D 的 Shapley MC 范围也跨零，负名义贡献不等于角变量没有物理信息。
- μ=1 时 BC、AC、ABCD 的 assessment 68% 条件覆盖率中位数分别为 0.658、0.638、0.646，均低于 0.68；数值拟合成功不等于区间已校准。
- 阈值选择尚未通过 selection-aware coverage validation，assessment access review 非独立，pseudo-experiment 比较使用人工耦合；运行登记为 `exploratory_posthoc`，`primary_claim_eligible=false`。
- 单质量箱未解析 Higgs 质量峰，9.14%/8.92% 是相对包容计数基线的名义缩减，不能表述为相对精细质量谱拟合的测量精度提升。
- 只使用受限 MC 样本；独立物理/数值验证、signed-template 近似的适用性验证仍待完成。这不是 ATLAS/CMS 合作组的测量或发现。

## 用于申请的描述

简短中文简介：

> 多伦多大学物理本科生，研究兴趣集中于计算物理与数据驱动的参数推断。已有 MaNGA 暗物质晕贝叶斯建模经验，并在 UCL 教授指导的第二课题中研究模拟 Higgs 四轻子事件的运动学特征归因，将机器学习分类与信号强度似然推断、不确定性和覆盖率诊断联系起来。

硕士申请宜强调希望系统加强数值方法、统计建模、科学机器学习与研究实践；博士申请需围绕导师的具体问题说明方法联系。暗物质/星系动力学方向以第一课题为主要证据；collider ML、统计粒子物理和 inference-aware evaluation 方向以第二课题为主要证据。对纯理论暗物质模型、量子方向或生成模型的匹配不能仅凭“计算粒子物理”标签升级。

以下英文可作为 SOP 的课题级描述；个人贡献须另行确认，不能把论文全部方法自动归为申请人独立完成：

> Since May 2026, I have worked one-on-one with a University College London physics professor on a computational particle-physics project studying kinematic feature attribution for signal-strength inference in simulated H → ZZ* → 2e2μ events. The current manuscript compares all fifteen nonempty combinations of four physically motivated feature groups using five MLP training seeds per combination, a common profile-likelihood analysis in pyhf, and exact Shapley attribution. Compact inputs yield narrower nominal intervals in the reported comparison, but finite-Monte-Carlo uncertainty and coverage diagnostics do not establish a calibrated precision gain. This project connects machine-learning evaluation with the reliability of physical parameter inference.

可用于 CV 的课题级要点（使用个人动作动词前核实分工）：

- Research project: kinematic feature attribution for Higgs signal-strength inference using ATLAS open simulated samples.
- Methods: exhaustive feature-group comparisons with MLP classifiers, profile-likelihood intervals in pyhf, exact Shapley attribution, and event-group bootstrap and conditional coverage diagnostics.
- Output: manuscript draft with exploratory numerical results; authorship order and submission status to be confirmed.

提交前仍需确认：申请人亲自完成的 2–3 项任务、导师姓名、作者顺序、导师对公开材料的许可及推荐意愿。不能由现有草稿推断第一作者身份、独立完成全部分析、已投稿或强推荐已落实。

## 研究作品与来源

第一课题公开主页：https://hyi03.github.io/manga-dm/ 。主页属于研究作品证据，不等同于预印本或期刊发表。第二课题公开主页仍待建立；沿用原计划，公开前由导师确认可公开范围。

本次来源均为用户指定的本地材料，非公开论文链接：

- [论文源码（2026-09-26）](D:/code/HiggsML/paper/latex/main.tex)
- [结果数值宏](D:/code/HiggsML/paper/latex/generated/numbers.tex)
- [结果证据索引](D:/code/HiggsML/paper/result-evidence.md)
- [固定快照身份](D:/code/HiggsML/paper/selected-snapshot.json)
- [构建与归档状态说明](D:/code/HiggsML/paper/README.md)

这些来源支持课题内容与草稿报告的结果；UCL 指导关系和开始时间来自既有申请档案，MaNGA 课题状态本次未重新核实。
