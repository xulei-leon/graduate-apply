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

兴趣段连接后验不确定性、相关噪声与群体应用。研究段提出**尚未实施、待讨论**的简化模拟检验：改变星系不对称性、噪声水平与相关尺度，观察后验及可靠性。它是可讨论的入门方向，不是已获批的 thesis，也不假定能立即取得 WALLABY 的完整分析环境。

末段回应官方 Fall 2027 招生公告，同时询问 MSc 的具体课题与经费；不把 1–2 个 MSc / PhD 岗位写成已保证申请人名额。阅读后可加入一个真实问题，例如是否应先量化中心偏移，再解释噪声后验的群体应用。

## 其他来源

- 官方导师与 Fall 2027 招生：https://www.queensu.ca/physics/people-search/kristine-spekkens
- 院系流程与年度截止：https://www.queensu.ca/physics/grad-studies/applicants
- 个人背景：[CV_en.md](../../CV/CV_en.md)
- 项目与资格：[README.md](README.md)
