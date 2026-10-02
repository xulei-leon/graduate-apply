# Hongyi Xu

University of Toronto · hyi.xu@mail.utoronto.ca

## 教育背景

**University of Toronto**
Honours Bachelor of Science (HBSc), Physics Specialist（本科在读）
2023 年 9 月至今；预计毕业：2027 年 6 月

相关已修课程：Advanced Classical Mechanics、Quantum Mechanics I、Electricity & Magnetism、Thermal Physics、Practical Physics II；Introduction to Computer Programming、Introduction to Computer Science、Computational Physics(正在修读)。

## 研究兴趣

主要研究兴趣为计算物理，尤其关注计算方法、统计推断与机器学习在物理研究中的应用。

## 研究经历

### 模拟 Higgs 四轻子事件的特征归因与信号强度推断

2026 年 5 月至今；指导教授：Mario Campanelli，University College London

**研究不同运动学输入对模拟 Higgs 四轻子事件信号强度约束的影响，比较分类性能与物理参数推断表现。**

- 设计特征组比较方案，处理 ATLAS 公开的模拟 H → ZZ* → 2e2μ 信号与背景样本，将 19 个运动学变量分为四组；按物理事件组划分数据，在五个随机种子下训练并比较全部 15 种非空组合的 MLP 分类器。
- 构建统一的 pyhf profile-likelihood 推断流程，以名义 68% 信号强度区间宽度评估不同输入，并用 exact Shapley 归因分解各特征组的贡献；观察到分类 AUC 与区间宽度的排序不完全一致。
- 开展 200 次 event-group bootstrap 和条件覆盖率诊断，评估有限模拟样本带来的不确定性与区间可靠性；现有结果仍属探索性，尚不能据此确认经校准的推断精度提升。

第一作者手稿（准备中）：Kinematic feature attribution for signal-strength inference in simulated H → ZZ* → 2e2μ events。

项目代码：https://github.com/hyi03/HiggsML

### MaNGA 星系运动学与暗物质晕参数推断

2025—2026 年；独立完成研究分析

**结合星系旋转曲线建模与贝叶斯群体推断，研究 MaNGA 盘星系暗物质晕的浓度—质量关系。**

- 在旋转曲线质量分解中应用 PyMC 建模与 MCMC 后验采样，刻画单星系暗物质晕质量与浓度之间的简并，量化参数不确定性。
- 对筛选后的 620 个盘星系开展群体分析，通过先验校正的重要性采样，将单星系联合后验样本用于推断浓度—质量关系的斜率、归一化与内禀散布。
- 通过先验预测检查、先验敏感性检验与采样诊断评估参数约束；结合倾角敏感性检验和 PSIS 诊断，检查模型假设及后验重加权稳定性对群体推断的影响。

第一作者手稿（已完成，尚未投稿）：[Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper/Local_Concentration__Mass_Relation_from_MaNGA.pdf)（PDF）

项目主页：https://hyi03.github.io/manga-dm/

### 银河系暗物质晕模型比较

2021—2022 年；高中阶段，校外导师指导项目

- 使用 Python 对导师提供的银河系运动学数据进行最小二乘拟合，以旋转曲线的 RMSE 比较 NFW、Einasto 和 Isothermal 三种暗物质晕模型的拟合表现。

## 技能

- 编程与工具：Python、PyMC、pyhf、LaTeX。
- 统计方法：Bayesian MCMC、重要性采样、profile likelihood、bootstrap、后验与覆盖率诊断。
- 机器学习：MLP 分类、特征组比较、exact Shapley 归因。
- 语言：中文母语；在英语授课的 University of Toronto 接受本科教育。
