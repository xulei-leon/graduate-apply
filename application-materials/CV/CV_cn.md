# Hongyi Xu

University of Toronto · hyi.xu@mail.utoronto.ca

## 教育背景

**University of Toronto · Physics Specialist（本科在读）**
2023 年 9 月至今；预计毕业：2027 年 6 月

相关已修课程：Advanced Classical Mechanics、Quantum Mechanics I、Electricity & Magnetism、Thermal Physics、Practical Physics I / II；Advanced Calculus、Linear Algebra I / II、Ordinary Differential Equations；Introduction to Computer Programming、Introduction to Computer Science。

## 研究兴趣

以计算物理为主要研究兴趣，关注数值方法与统计推断在物理模型检验和参数约束中的应用。具体兴趣包括：

- 粒子物理：运动学特征分析、统计推断与不确定性评估。
- 暗物质与宇宙学：暗物质晕的数值建模及其观测约束。

希望在硕士阶段进一步学习计算物理方法，并加强相关物理理论训练。

## 项目经历

### 模拟 Higgs 四轻子事件的特征归因与信号强度推断

2026 年 5 月至今；指导教授：Mario Campanelli，University College London

**使用 MLP 分类、似然推断与特征归因，研究运动学输入如何影响模拟 Higgs 四轻子事件的信号强度约束。**

- 设计特征组比较：处理 ATLAS 公开的模拟 H → ZZ* → 2e2μ 信号与背景样本，将 19 个运动学变量分为四组；按物理事件组划分数据，以五个随机种子训练并比较 15 种非空组合的 MLP 分类器。
- 构建统一的 pyhf profile-likelihood 推断流程，用名义 68% 信号强度区间宽度比较不同输入，并通过 exact Shapley attribution 分解四组特征对区间宽度的贡献。
- 进一步开展 200 次 event-group bootstrap 和条件覆盖率诊断，检查有限模拟样本带来的不确定性与区间校准。
- 项目代码：https://github.com/hyi03/HiggsML
- 第一作者手稿（正在写作）：Kinematic feature attribution for signal-strength inference in simulated H → ZZ* → 2e2μ events。

### MaNGA 星系运动学与暗物质晕参数推断

2025—2026 年；个人独立完成项目

**使用贝叶斯建模与群体推断，研究 MaNGA 盘星系暗物质晕的质量—浓度关系。**

- 在旋转曲线质量分解中发现，仅用优化方法求取单个最优解，难以体现晕质量与浓度之间的简并及参数不确定性。
- 围绕这一问题，学习并应用 PyMC 贝叶斯建模与 MCMC 后验采样，刻画晕质量与浓度的相关性；检查先验预测、先验敏感性与采样诊断，评估参数约束对数据和先验的依赖。
- 对筛选后的 620 个盘星系开展群体分析，通过先验校正的重要性采样，将单星系联合后验样本用于推断 concentration–mass relation 的斜率、归一化与内禀散布；结合倾角敏感性检验与 PSIS 诊断，评估模型假设和重加权稳定性对结果的限制。
- 项目主页：https://hyi03.github.io/manga-dm。
- 第一作者手稿（已完成）：[Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper-preview)

### 银河系暗物质晕模型比较

2021—2022 年；高中阶段，校外导师指导项目

**使用旋转曲线拟合，比较三种银河系暗物质晕模型的拟合表现。**

- 使用 Python 对导师提供的银河系运动学数据进行最小二乘拟合，并以旋转曲线的 RMSE 比较 NFW、Einasto 和 Isothermal 晕模型。

## 技能

- 科学计算：Python 数据处理与可视化、曲线拟合、残差分析；PyMC、Bayesian MCMC、后验与参数不确定性分析。
- 机器学习：在 Higgs 模拟分析项目中学习并应用 MLP 分类、特征组比较与 exact Shapley 归因。
- 科研写作：写作 MaNGA 论文；撰写 LaTeX 实验报告和技术文档。
- 语言：中文母语；在英语授课的 University of Toronto 接受本科教育。
