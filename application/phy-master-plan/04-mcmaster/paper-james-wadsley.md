# James Wadsley：论文推荐与邮件联系点

最后核查：**2026-10-03**。推荐 1 篇首读论文；助手已核查作者与开放原文，申请人后续阅读，不标为已读或已复现。对应 [英文咨询信](letter.md)。

## 首读：Dwarf diversity in ΛCDM with baryons

- 作者：Akaxia Cruz、Alyson Brooks、Mariangela Lisanti、Annika H. G. Peter、Robel Geda、Thomas Quinn、Michael Tremmel、Ferah Munshi、Ben Keller、James Wadsley；Wadsley 为合著者。
- 年份与版本：2025 年预印本，arXiv v1，2025-10-13；所读摘要页未列 journal reference，不自行标为已发表。
- 摘要、作者、版本：https://arxiv.org/abs/2510.11800
- 开放原文：https://arxiv.org/html/2510.11800v1
- PDF：https://arxiv.org/pdf/2510.11800v1
- **题名差异：** 摘要页写 *Dwarf diversity in ΛCDM with baryons*；所读 HTML 正文写 *Galaxy size and rotation curve diversity in ΛCDM with baryons*。邮件使用摘要题名；两者同为 2510.11800，不当作两篇论文。

**为什么适合你：** 旋转曲线、暗物质晕与模型假设是 MaNGA 项目的直接延伸。本文从物理模拟解释多样性；你的工作从观测曲线推断晕参数。阅读的重点是两者如何可比，以及简化质量模型可能遗漏哪些重子物理。

## 原文内容与经历连接

| 原文可核实内容 | 位置 | 与个人背景的联系及边界 |
|---|---|---|
| 使用 Marvel / Marvelous Massive Dwarf 高分辨率模拟，考察星形成与反馈的影响 | §II Simulations、§VI | 你的先验和模型敏感性训练可帮助设计比较；尚未运行 ChaNGa 或完成 subgrid physics 开发 |
| 与 SPARC 观测比较；模拟曲线有质量分布与引力等不同定义，设置内区分辨率限制 | §III、§IV.2 Rotation Curves | 连接观测旋转曲线质量分解；不能把所有模拟速度定义当作观测视线旋转速度 |
| 既能形成慢上升曲线，也能保留紧致星系及快上升曲线，并比较尺寸—恒星质量关系 | §V.1–V.3 | 不只看某一曲线的好拟合，还要检查总体多样性及其他观测量 |
| 比较反馈模型与紧致星系形成，讨论现有模型的限制 | §VI–VIII | 邮件联系点：模型改变如何影响对晕结构的解释；不是已排除所有替代暗物质理论 |

本文原文指出主要结果并非通过构造 mock HI observations 得到。阅读时须区分模拟的物理结构、曲线定义、观测测量效应和你自己的拟议参数恢复测试，不能将这些混为一项已完成分析。

## 建议阅读顺序

1. Abstract、§VIII：先理解同时重现旋转曲线及尺寸多样性的目标。
2. §V 的结果图：区分快／慢上升曲线，比较尺寸—恒星质量散布。
3. §III–IV.2：核对观测样本、曲线定义、中心与可用半径，避免把分辨率以下的模拟当作可靠真值。
4. §II 与 §VI：列出反馈、星形成、分辨率等差异，再回到 §VII 看解释边界。

读完应能回答：慢上升曲线是否只由 DM core 决定？重子分布怎样影响曲线？为什么拟合模拟曲线也可能恢复出有偏的晕质量／浓度？

## 已写入邮件与待讨论任务

邮件连接 MaNGA 的质量—浓度简并与模型敏感性，提出**尚未实施、待讨论**的起步想法：对模拟输出构造简化旋转曲线拟合，比较不同重子结构下的参数恢复。先确认可用输出、可比的速度定义与 MSc 范围，不承诺复现全部宇宙学模拟。

信中明确希望学习 galaxy formation 与 numerical hydrodynamics；没有把 Python 经验扩写成 SPH、C++ 或并行计算熟练。Fall 2027 名额和经费仍待导师确认。

## 其他来源

- 官方研究概况：https://experts.mcmaster.ca/people/wadsley
- 通用 MSc / PhD 联系邀请：https://physics.mcmaster.ca/people/ （James Wadsley 条目）
- 个人背景：[CV_en.md](../../CV/CV_en.md)
- 项目与资格：[README.md](README.md)
