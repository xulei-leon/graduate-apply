# Alison Lister：论文推荐与邮件联系点

最后核查：2026-09-28。推荐 **1 篇首读 + 1 篇选读**。两篇都是 ATLAS Collaboration 成果，均核对到 Alison Lister 署名；这不能确定她本人负责哪部分，也不是组内课题或名额承诺。申请人计划后续阅读，当前不标记为已读。已更新[英文邮件](cover_letter_email_en.md)与[中文邮件](cover_letter_email_cn.md)，首封只引用第一篇，保持主题集中。

## 首读：Weakly supervised anomaly detection for resonant new physics in the dijet final state using proton-proton collisions at √s = 13 TeV with the ATLAS detector

- 作者：ATLAS Collaboration；作者表有 A. Lister，单位为 UBC。
- 发表：Physical Review D 112, 072009，2025-10-22。
- DOI：https://doi.org/10.1103/2yq5-vj59
- 摘要与版本：https://arxiv.org/abs/2502.09770
- 开放 PDF：https://arxiv.org/pdf/2502.09770
- 本轮正文依据：INSPIRE 提供的出版版全文文本及出版页；出版版 PDF：https://inspirehep.net/files/6fa3047630b80b9880a2a75e8f4d8315

**为什么最适合先读：** 这篇的“分类器选择 → 背景估计 → profile likelihood → 验证”与你 Higgs 项目中从 MLP 到 pyhf、bootstrap 和覆盖率诊断的经历最接近。它提供一个具体例子：分类器表现之后，还要检查用于物理结论的统计流程。

| 原文中可核实的内容 | 位置 | 与你背景的连接及边界 |
|---|---|---|
| 用 SALAD / CURTAINS 构造背景，再训练弱监督分类器，并比较不同喷注特征集合 | §V B–C | 对应你对输入组合的兴趣；你尚未完成这些背景方法或弱监督训练，不写成已有经验 |
| 分类器不同初始化形成 ensemble，相关不确定性被传递到计数及背景拟合 | §V C 2、§V D 2 | 与你五种子比较和 MC 不确定性意识相连；不能把 ensemble 波动等同于完整 MC bootstrap |
| 使用 profile-likelihood 检验，拟合实现采用 pyhf；每个 signal region 内的质量直方图计数在该检验中合并为一箱 | §V D 3 | **邮件直接联系点**：分类器选择如何进入下游统计推断；本文主要做局部显著性与限制，你的课题研究信号强度区间，不是同一个评价目标 |
| 使用 nonclosure correction，并用三类测试样本验证；最低质量信号区未通过验证，未进入最终结果 | §V D 4、§V E、Appendix B–C | **最值得学的判断**：分析能运行不代表该区域的统计解释可靠；背景相关偏差要单独检查 |

以上事实见[出版版原文](https://inspirehep.net/files/6fa3047630b80b9880a2a75e8f4d8315)。文章没有显著局部 excess；不要把它写成新物理发现。也不要将论文中的 nonclosure 修正直接套作你项目已完成的覆盖率校准。

**阅读顺序：** Abstract 与分析流程 → §V D 2–4（误差、似然、nonclosure）→ §V E / Appendix C（验证）→ 再补 §V B–C 的背景与分类器方法。第一遍可略过作者表和探测器细节。

阅读时重点回答：分类器可能学到哪些背景偏差？哪些随机性进入了最后的拟合？为什么一个 signal region 应因验证失败而被排除？你的当前 bootstrap 和覆盖率诊断分别检查了哪些不同问题？

**已写入邮件：** 点出分类器选择、pyhf profile-likelihood 和背景偏差验证的关系；拟议一个尚未实施的小规模模拟任务，检查分类器选择和背景建模偏差对拟合结果的影响。邮件称“ATLAS 论文，您参与署名”，不写“您设计的 SALAD / CURTAINS 方法”。

## 选读：Transforming jet flavour tagging at ATLAS

- 作者：ATLAS Collaboration；已核对 Alison Lister 署名。
- 发表：Nature Communications 17, 541 (2026)；arXiv 初版 2025，本轮读取 v2，2026-01-26。
- DOI：https://doi.org/10.1038/s41467-025-65059-6
- 摘要与版本：https://arxiv.org/abs/2505.19689
- 开放 PDF：https://arxiv.org/pdf/2505.19689v2

**为什么选读：** 它适合在读完统计流程论文后，了解更复杂事件表征如何接受物理验证。GN2 采用低层径迹信息、transformer 和辅助训练目标，超出你当前 MLP 项目，但可以从“哪些输入与训练目标提供信息、性能对模拟模型是否稳健”切入，不必先掌握完整网络实现。

优先阅读的具体内容：

1. **Fig. 1（PDF 第 3 页）与 Methods 的网络说明**：主任务是 jet flavour tagging，另有 track-origin / vertex-grouping 任务。理解这些辅助任务如何引入与物理相关的训练信息；不要把辅助任务视为你现有 Shapley 归因的同一种方法。
2. **Results 中 Robustness against generator modelling variations 与 Table 1**：作者在不同生成器设定下比较效率，考察复杂模型是否增加生成器依赖。这可延伸你对“名义性能改善能否在输入分布改变后保留”的兴趣。
3. **Algorithm performance in collision data 与 Fig. 4（PDF 第 7 页）**：区分 simulation 性能与校准到碰撞数据后的性能，理解效率与误标率修正。论文的真实数据验证不是你现有 open-MC 项目已经具备的证据。

上述依据来自[arXiv v2 原文](https://arxiv.org/pdf/2505.19689v2)。目前不在首封信同时加入第二篇，避免把模型架构、数据校准和信号强度推断三个方向挤在一起。若读后更关注模型稳健性，可用它替换首封的论文段，或留作导师回复后的讨论。
