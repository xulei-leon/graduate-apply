# Hongyi Xu

hyi.xu@mail.utoronto.ca · https://github.com/hyi03

## 研究兴趣

计算物理与高能物理；统计推断；贝叶斯建模；机器学习在粒子物理与天体物理研究中的应用。

## 教育背景

**University of Toronto**，2023 年 9 月—2027 年 6 月（预计）
学位与专业：Honours Bachelor of Science (HBSc), Physics Specialist，加拿大多伦多

**部分已修课程：** Advanced Classical Mechanics；Advanced Physics Lab；Electricity & Magnetism；Thermal Physics；Electromagnetic Theory；Quantum Mechanics I；Introduction to Computer Programming；Introduction to Computer Science。

**部分在修课程：** Computational Physics；Quantum Mechanics II；Nonlinear Physics；Introduction to High Energy Physics；Time Series Analysis；Relativistic Electrodynamics；Statistical Mechanics。

## 研究经历

### Higgs 四轻子信号强度推断中的特征归因

2026 年 5 月至今

研究项目，指导教授：Mario Campanelli，University College London · 远程

- 使用 ATLAS 公开的 H → ZZ* → 2e2μ 信号与背景模拟样本，研究运动学特征选择如何影响模拟 Higgs 四轻子事件的信号强度推断。
- 设计 19 个运动学变量的系统比较方案，将其分为四个特征组，在五个随机种子下使用 MLP 分类器评估全部 15 种非空组合；构建统一的 pyhf profile-likelihood 流程，比较分类性能与物理参数约束。
- 应用 exact Shapley 归因、200 次 event-group bootstrap 重采样和条件覆盖率诊断，评估特征贡献与推断可靠性；发现分类器 AUC 与信号强度区间宽度并不总是倾向于相同的特征输入。

手稿：第一作者手稿（准备中）；项目代码：https://github.com/hyi03/HiggsML

### MaNGA 星系运动学与暗物质晕参数推断

2025—2026 年

独立研究

- 使用 Python 和 PyMC，为筛选后的 620 个 MaNGA 盘星系开发旋转曲线质量分解流程，将单星系后验与暗物质晕浓度—质量关系的群体推断相结合。
- 应用 MCMC 和先验校正的重要性采样，推断该关系的斜率、归一化与内禀散布，同时刻画暗物质晕质量与浓度之间的简并及参数不确定性。
- 通过先验预测检查、先验敏感性分析、采样诊断、倾角敏感性检验和 PSIS 诊断评估结果的稳健性；在固定测光倾角的假设下，得到所选星系样本的浓度—质量关系呈较弱负斜率（α = −0.093），子样本检验表明倾角不确定性是主要限制因素。

手稿：第一作者手稿（已完成，尚未投稿）：[Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper/Local_Concentration__Mass_Relation_from_MaNGA.pdf)（PDF）

项目主页：https://hyi03.github.io/manga-dm/

## 技术技能

- 编程与工具：Python、PyMC、pyhf、LaTeX。
- 统计方法：贝叶斯推断、MCMC、重要性采样、profile likelihood、bootstrap、后验预测检查、PSIS 诊断。
- 机器学习：MLP 分类、特征组比较、Shapley 归因。
- 语言：中文（母语）；英语（正在攻读英语授课的本科学位）。
