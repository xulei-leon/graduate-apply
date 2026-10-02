# graduate-apply

本仓库维护 HY 的 2027 年秋季研究生申请数据库，记录可核实的项目要求、导师匹配、截止日期和申请状态。项目条目应让后续维护者直接判断申请资格、所需材料、研究匹配度及待确认事项。

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
| 申请方向 | Physics PhD、Physics Master、Data Science Master |

科研描述及其证据边界见 [research-background.md](research-background.md)，完整个人资料见 [background.md](background.md)。

## 目录与进度

| 位置 | 用途 |
|------|------|
| [physics-phd/](physics-phd/) | 美国、新加坡 direct-entry Physics PhD 项目与匹配导师；目标至少 40 个项目/导师记录 |
| [physics-master/](physics-master/) | Physics Master 本轮38项候选：加拿大8、澳大利亚5、美国10、法国5、德国5、瑞士5；其余地区及扩展档案保留，不计本轮 |
| [ds-master/](ds-master/) | DS / Analytics / Applied Statistics / ML 硕士学校档案与地区索引；50项，覆盖9地区：美国15所，其他各不超过5项；含资格缺口和来源待核项 |
| [application/phy-master-plan/](application/phy-master-plan/) | 物理硕士38项地区候选总览、PDF、事实快照与来源访问审计 |
| [application/ds-master-plan/](application/ds-master-plan/) | DS硕士综合调研、跨项目比较、美国15所分层推荐与申请策略 |
| [guides/](guides/) | 搜索及国家差异参考资料 |
| [targets.md](targets.md) | 目标地区及申请优先级 |
| [AGENTS.md](AGENTS.md) | 来源顺序、字段标准、匹配判断与建档流程 |

目标数量是最低覆盖要求，不能替代资格和来源核实。DS 档案与索引已同步建立，但候选不等于申请资格已确认；完整报告见 [全球DS硕士调研](application/ds-master-plan/DS_Masters_Global_Survey_20261002.md)，美国部分见 [15所分层推荐与申请比较](application/ds-master-plan/USA_DS_Masters_15_20261002.md)。

## 加拿大硕士申请规划

分析前提：国际学生、GPA 按 3.0/4.0、接受自费、预算不作为限制，目标为至少取得一个加拿大硕士 offer。

- [物理、天文及 Applied Physics 申请规划](physics-master/Canada_Academic_Physics_Masters.md)
- [加拿大DS、数据分析与相邻硕士扩展规划](application/ds-master-plan/Canada_Data_Science_Masters.md)；本次全球候选池的加拿大五项见 [DS索引](ds-master/README.md)，与历史扩展名单分开计数。

规划中的候选不等于已核实申请资格，也不等于已完成项目条目。

## 法国物理硕士申请材料

本轮法国按Physics学科全国前五选择Paris-Saclay、PSL、Sorbonne、IP Paris、Grenoble；English M1、法语门槛、研究实习和2027日历分开记录。Grenoble按本次范围保留为原排名规则例外，但法语未解决则暂缓申请。Paris Cité联合PPM不与Sorbonne重复计数。旧[法国英语筛选分析](physics-master/France_Physics_Masters.md)保留为历史；最新要求与候选计数见[物理硕士索引](physics-master/README.md)和[地区候选总览](application/phy-master-plan/Physics_Masters_Regional_Overview_20261002.md)。

## 建档规则

1. 按官方项目页、官方招生页、导师或实验室页等顺序核实信息；不要将第三方汇总页作为主要证据。查询外部公开来源时直接使用 HTTPS 请求，不使用 webservice。
2. 先建立每个硕士项目或博士导师的独立 Markdown 文件，再更新对应目录的 `README.md` 索引；两处关键事实、地区计数和目标计数须一致。
3. 每条记录保留可见的官方来源 URL 与最后核实日期。无法核实的要求、招生人数、资助或导师招募状态明确标记为待确认。
4. 分开记录事实与判断：录取要求和截止日期来自来源；High/Medium/Low 匹配度及 Safe/Match/Reach 难度是基于证据的申请评估。
5. 非加拿大硕士须满足最新 QS 综合或相关学科前 100，或美国 US News 综合或相关学科前 50；加拿大硕士按资格、研究匹配、导师及资助情况筛选。博士仅保留接受本科直博的美国和新加坡项目。
6. 代码发现优先使用 codebase-memory-mcp 图谱；仅在检索非代码文件、字符串或图谱信息不足时使用文本搜索。不要自动启用 superpower skill，除非用户明确要求。

正式条目应回答：能否申请、需要什么、匹配程度如何、哪些事实尚待跟进。完整字段和流程以 [AGENTS.md](AGENTS.md) 为准。
