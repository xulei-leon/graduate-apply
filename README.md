# graduate-apply

本仓库维护 HY 的 2027 年秋季研究生申请数据库，记录可核实的项目要求、导师匹配、截止日期和申请状态。项目条目应让后续维护者直接判断申请资格、所需材料、研究匹配度及待确认事项。

**当前执行状态（2026-10-20）：博士申请工作已按用户要求暂停，待明确恢复后继续。** 暂停博士项目搜索、招生核查、套磁、文书、推荐信配置及递交准备；既有材料保留。当前申请工作集中于物理硕士与数据科学硕士，周复盘及后续规划按此范围执行。

## 申请人概况

| 项目 | 当前记录 |
|------|----------|
| 本科 | University of Toronto，Physics；预计 2027 年 6 月毕业 |
| GPA | 3.0/4.0 |
| GRE | 317（Q 166） |
| 英语考试 | 本科为英语授课；具体项目是否豁免 TOEFL/IELTS 需逐项核实 |
| 科研一 | MaNGA 暗物质晕 c–M 关系，PyMC 5 与 Bayesian MCMC；第一作者手稿已准备提交 arXiv，尚未确认投稿 |
| 科研二 | 2026 年 5 月起与 UCL 物理教授一对一合作，研究模拟 H → ZZ* → 2e2μ 事件的运动学特征归因与信号强度推断；已有 2026-09-26 草稿，结果仍属探索性，作者顺序及投稿状态待确认 |
| 方法经验 | Python、PyMC 5；第二课题中本人完成 MLP、pyhf profile likelihood、exact Shapley attribution、MC bootstrap 与覆盖率诊断相关工作 |
| 申请方向 | Physics Master、Data Science Master；Physics PhD 已暂停（2026-10-20） |

科研描述及其证据边界见 [research-background.md](research-background.md)，完整个人资料见 [background.md](background.md)。

## 目录与进度

| 位置 | 用途 |
|------|------|
| [physics-phd/](physics-phd/) | 已暂停；保留美国、新加坡 direct-entry Physics PhD 项目与匹配导师档案，原至少40条覆盖目标暂不推进 |
| [physics-master/](physics-master/) | Physics Master 本轮39所学校记录：加拿大12、澳大利亚2、美国10、法国5、德国5、瑞士5；其余地区及扩展档案保留，不计本轮 |
| [ds-master/](ds-master/) | DS及用户指定CS转专业/计算科学硕士档案；原全球池50项，加美国扩展7份/5校（1项停招）及加拿大McMaster CSE 1份，加NYU四项，共62份研究档案、9地区；美国26份/20校、加拿大6份；含资格与排名待核项 |
| [application/phy-master-plan/](application/phy-master-plan/) | 物理硕士39所学校地区候选总览、PDF、事实快照与来源访问审计 |
| [application/ds-master-plan/](application/ds-master-plan/) | DS硕士综合调研、美国15校快照、美国七项、加拿大McMaster及NYU四项扩展档案、四校五项目和NYU总览（含官方来源） |
| [country-differences.md](country-differences.md) | 国家差异参考资料 |
| [targets.md](targets.md) | 目标地区及申请优先级 |
| [AGENTS.md](AGENTS.md) | 来源顺序、字段标准、匹配判断与建档流程 |

目标数量是最低覆盖要求，不能替代资格和来源核实。DS 档案与索引已同步建立，但候选不等于申请资格已确认；完整报告见 [全球DS硕士调研](application/ds-master-plan/DS_Masters_Global_Survey_20261002.md)，美国部分见 [15所分层推荐与申请比较](application/ds-master-plan/USA_DS_Masters_15_20261002.md)。

2026-10-21：[NYU计算物理与计算科学五项目分析](application/ds-master-plan/NYU_Computational_Masters_20261021.md)比较既有Physics MS与新增Scientific Computing、GSAS Mathematics、Tandon Mathematical Sciences、Data Science四份档案。新增4份后DS/CS/计算科学目录62份、美国26份/20校；Physics仍39所。具体2027招生与费用缺项保留待核。

2026-10-19：[CS / DS与计算科学四校五项目总览](application/ds-master-plan/CSDS_Master_Overview.md)汇总Chicago、USC两项、Brown及加拿大McMaster CSE，包含培养定位、论文科研、费用与关键官方证据。Brown的GPA≥3.4为最强优先偏好，按Reach处理；Chicago/USC核心资格待核；McMaster为High/Unknown，先核GPA、导师与招生细则。历史50项PDF/JSON不包含扩展；独立项目档案数量仍按目录表统计。

## 加拿大硕士申请规划

分析前提：国际学生、GPA 按 3.0/4.0、接受自费、预算不作为限制，目标为至少取得一个加拿大硕士 offer。

- [物理、天文及 Applied Physics 申请规划](physics-master/Canada_Academic_Physics_Masters.md)
- [加拿大DS、数据分析与相邻硕士扩展规划](application/ds-master-plan/Canada_Data_Science_Masters.md)；原全球池加拿大五项及新增McMaster CSE档案见 [DS索引](ds-master/README.md)，与历史扩展名单分开计数。

规划中的候选不等于已核实申请资格，也不等于已完成项目条目。

## 法国物理硕士申请材料

本轮按用户指定保留PSL、IP Paris、Sorbonne、Paris-Saclay、Paris Cité五校，选择英语入口；Paris Cité为用户范围例外。Sorbonne与Paris Cité的联合PPM不计两次独立申请。详见[法国五校分析](physics-master/France_Physics_Masters.md)、[当前学校索引](physics-master/README.md)和[地区候选总览](application/phy-master-plan/Physics_Masters_Overview.md)。

## 建档规则

1. 按官方项目页、官方招生页、导师或实验室页等顺序核实信息；不要将第三方汇总页作为主要证据。查询外部公开来源时直接使用 HTTPS 请求，不使用 webservice。
2. 先建立每个硕士项目或博士导师的独立 Markdown 文件，再更新对应目录的 `README.md` 索引；两处关键事实、地区计数和目标计数须一致。
3. 每条记录保留可见的官方来源 URL 与最后核实日期。无法核实的要求、招生人数、资助或导师招募状态明确标记为待确认。
4. 分开记录事实与判断：录取要求和截止日期来自来源；High/Medium/Low 匹配度及 Safe/Match/Reach 难度是基于证据的申请评估。
5. 非加拿大硕士须满足最新 QS 综合或相关学科前 100，或美国 US News 综合或相关学科前 50；加拿大硕士按资格、研究匹配、导师及资助情况筛选。博士仅保留接受本科直博的美国和新加坡项目。
6. 代码发现优先使用 codebase-memory-mcp 图谱；仅在检索非代码文件、字符串或图谱信息不足时使用文本搜索。不要自动启用 superpower skill，除非用户明确要求。

正式条目应回答：能否申请、需要什么、匹配程度如何、哪些事实尚待跟进。完整字段和流程以 [AGENTS.md](AGENTS.md) 为准。

## 本周复盘（2026-10-17）

[申请进展、截止日期与下周计划](application/weekly-reviews/2026-10-17.md)。该周快照记录两份条件录取：[ANU Astronomy and Astrophysics](offers/ANU.md)、[Sydney Master of Computer Science](offers/USYD.md)；原Sydney DS申请被拒。物理候选39校／19优先／8冲刺，DS当时50份；2026-10-19扩展后当前研究档案数见上方目录表。录取、候选、已提交与资格核实分别记录。
