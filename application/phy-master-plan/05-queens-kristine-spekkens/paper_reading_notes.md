# Kristine Spekkens：论文推荐与邮件联系点

最后核查：**2026-10-03**。推荐 1 篇首读论文；助手已核查作者与开放原文，申请人后续阅读，不标为已读或已复现。对应 [英文咨询信](letter.md)。

## 首读：Bayesian Galaxy Asymmetry

- 作者：Mathieu Perron-Cormier、Kristine Spekkens、Nathan Deg、Lawrence M. Widrow、Marcin Glowacki；Spekkens 为共同作者。
- 年份与版本：2026；arXiv v1，2026-09-22。摘要页列 related DOI；本包不依据 DOI 单独推定具体期刊卷期或上线日期。
- 摘要、作者、版本：https://arxiv.org/abs/2609.26472
- 开放原文：https://arxiv.org/html/2609.26472v1
- PDF：https://arxiv.org/pdf/2609.26472v1
- Related DOI：https://doi.org/10.3847/1538-4357/aea97a

**为什么适合你：** 本文用 Bayesian posterior 表达噪声观测下的真实星系不对称性，以便开展群体统计。你已有 MaNGA 的单星系后验到群体 c–M 推断经验，以及 Higgs 的 bootstrap 与覆盖率诊断，可以从“如何表达并验证测量不确定性”切入。

## 原文内容与经历连接

| 原文可核实内容 | 位置 | 与个人背景的联系及边界 |
|---|---|---|
| 推导 squared-differences asymmetry 的后验，从 uncorrelated Gaussian noise 开始 | §II、§II.1 | 连接显式噪声模型与后验；不是用 PyMC 直接重写旋转曲线模型 |
| 构造 flat asymmetry prior，再得到 posterior asymmetry distribution | §II.2–II.3 | 可用现有先验敏感性经验理解；flat asymmetry 不等于所有中间参数均取平坦先验 |
| 扩展至 correlated bins，并核查相应不确定性 | §II.4 | 连接 Higgs 的覆盖率诊断，但观测噪声相关与 event-group bootstrap 是不同问题 |
| 在 WALLABY 中与此前噪声校正结果比较，恢复低不对称性测量并提供不确定性 | §III Application to WALLABY | 邮件主要联系点：可靠个体测量如何支撑更大群体样本，不把可用样本增加当作所有参数精度同比改善 |
| 未全面处理中心不确定性及分辨率对真实不对称性的影响 | §II 开头、§IV Discussion and Conclusion | 噪声后验不是全部系统误差预算；不宣称可直接在任意 data cube 上无条件使用 |

内容来自上述原文。论文中的 Bayesian 与 coverage 内容确有方法重合，但不能据此声称你已经做过 HI cube reduction 或复现了相关噪声推导。

## 建议阅读顺序

1. Abstract、§IV：先区分测量不确定性、真实不对称性与未处理的系统误差。
2. §III 的 WALLABY 比较图：理解旧校正为何在低不对称性或低信噪比情况下失效。
3. §II.1–II.3：逐步写下似然、flat asymmetry prior、后验各自依赖什么；不要先跳到全部特殊函数细节。
4. §II.4 与验证部分：看相关噪声怎样改变有效信息量与区间可靠性，最后再读附录。

读完应能回答：噪声为什么会抬高不对称性估计？flat asymmetry prior 具体平坦在哪个量上？后验区间可靠能否说明中心位置和 beam smearing 已经无误？

## 已写入邮件与待讨论任务

兴趣段明确论文推断的是**单个星系不对称度的后验分布**，这些后验及其不确定性可以支持群体研究；不把它写成直接推断星系总体的真实不对称度分布。邮件希望进一步学习论文已有的相关噪声处理与后验可靠性检验，使用面向未来的学习表述，不标为申请人已经读懂或复现。

研究段将复现论文在合成数据上的验证明确为**尚未实施、待讨论的学习起点**，随后讨论与组内研究相关的下一步。论文 §II.4 已有 coverage test 与 mock cube 的不同噪声实现检验，因此不把复现包装为新课题，也不预先承诺能为组内数据找到扩展。

末段询问个人背景是否适合 Fall 2027 的 MSc 研究机会，并表达希望讨论可能课题与准备方式；不重复泛问是否招生，也不把 1–2 个 MSc / PhD 岗位写成独立的 MSc 配额或已保证申请人名额。经费与岗位余量仍待后续确认，当前邮件未直接询问经费。

## 其他来源

- 官方导师与 Fall 2027 招生：https://www.queensu.ca/physics/people-search/kristine-spekkens
- 院系流程与年度截止：https://www.queensu.ca/physics/grad-studies/applicants
- 个人背景：[CV_en.md](../../CV/CV_en.md)
- 项目与资格：[README.md](README.md)
