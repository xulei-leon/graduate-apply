# ANU 比较报告：官方来源访问与证据边界

日期：2026-10-03。所有网页通过 Python requests 直接 HTTPS 请求读取，HTML 用 BeautifulSoup 提取正文，PDF 用 PyMuPDF 提取；未调用 webservice。

对应报告：[18 个重点项目与 ANU 的比较](Physics_Masters_vs_ANU_PhD_Analysis.md)。HTTP 200 只表示收到响应；验证码、错误页与内容受限不能当作招生／培养规则核实。

## 关键结论的来源对应

| 核查事项 | 读到的内容及采用方式 |
|---|---|
| ANU 普通版 | NSCAA 2027 列 6 units research course；ASTR8001 课程列 6–24 units、先修与 permission code。报告区分最低要求与获批的实际研究量。 |
| ANU Advanced | VSCAA 2027 明细为 ASTR8010 36 units，加 ASTR8001 6 和 ASTR8030 6，合计 48 units research training；转轨页概括口径与详细组成同时保留。 |
| Northwestern | Standard thesis 可为深入阅读或研究项目；不能由 thesis 名称推断原创成果。 |
| UT Austin | 现行 /graduate/programs/physics-ma/ 列 MA、30 hours、thesis 与平均完成时间；系 admissions 确认 master-only 且无 Master 资助。是否为本人可执行 degree plan 仍须确认。旧 areas-of-study 路径返回 404。 |
| Queen’s / McMaster | Queen’s 导师页明确 Fall 2027 有 1–2 个 MSc/PhD 岗位；McMaster 导师页列计算天体、模拟与并行计算。岗位不等于个人接收。 |
| Western | Physics MSc 的培养规则取自系手册；Barmby 研究取自 faculty 页。当前本地 Barmby 申请材料是 Astronomy MSc，不与 Physics MSc 合并。 |
| 法国 M1 | PPM 官方联办目录列 3 个月 internship；Saclay 列 3 ECTS research project 和 6 ECTS internship。未核到指定 M2，结论均有后续路线条件。 |
| Heidelberg / KIT / UZH / EPFL | 分别核实一年含准备及论文的研究阶段、第三学期方法准备加第四学期 thesis、6/10 个月 thesis 选项、课程期间研究参与及最后 4–6 个月 thesis。 |
| Alberta / Melbourne | Alberta 研究生主页 403，导师目录可读；Melbourne handbook 响应 200 但为验证页面，study 页 403。培养结构仍待核。 |

## 逐页访问记录

| 官方 URL | HTTP | 提取正文字符数 | 使用边界 |
|---|---:|---:|---|
| https://programsandcourses.anu.edu.au/2027/program/NSCAA | 200 | 17923 | 正文已取得；所核字段及限制见比较报告 |
| https://www.mcgill.ca/gradapplicants/program/physics-msc | 200 | 3673 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physics.mcgill.ca/grads/program.html | 200 | 5982 | 正文已取得；所核字段及限制见比较报告 |
| https://gs.mcmaster.ca/program/physics-and-astronomy/ | 200 | 42891 | 正文已取得；所核字段及限制见比较报告 |
| https://www.queensu.ca/physics/grad-studies/msc-degree-overview | 200 | 2113 | 正文已取得；所核字段及限制见比较报告 |
| https://www.ualberta.ca/en/physics/graduate-studies/index.html | 403 | 553 | 访问受限；未核到所需正文 |
| https://physics.uwo.ca/graduate/current_students/Graduate%20Student%20Handbook.html | 200 | 50616 | 正文已取得；所核字段及限制见比较报告 |
| https://handbook.unimelb.edu.au/2026/courses/mc-sci-phy | 200 | 82 | 仅取得验证／错误／极短响应；不作为核心事实来源 |
| https://physics.utexas.edu/academics/admissions | 200 | 19032 | 正文已取得；所核字段及限制见比较报告 |
| https://bulletin.wustl.edu/grad/artsci/degrees/physics-ma/ | 200 | 3218 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physics.northwestern.edu/graduate/master-degree/index.html | 200 | 5706 | 正文已取得；所核字段及限制见比较报告 |
| https://physics.northwestern.edu/documents/nu-pa-masters-handbook-03.20.25.pdf | 200 | 34655 | 正文已取得；所核字段及限制见比较报告 |
| https://www.tgs.northwestern.edu/admission/academic-programs/explore-programs/physics.html | 200 | 7786 | 正文已取得；所核字段及限制见比较报告 |
| https://bulletins.nyu.edu/graduate/arts-science/programs/physics-ms/ | 200 | 6785 | 正文已取得；所核字段及限制见比较报告 |
| https://psl.eu/en/education/master-s-degree-physics | 200 | 7143 | 正文已取得；所核字段及限制见比较报告 |
| https://sciences.sorbonne-universite.fr/en/study/degree-seeking/masters/master-fundamental-physics-and-applications | 200 | 5273 | 正文已取得；所核字段及限制见比较报告 |
| https://www.universite-paris-saclay.fr/en/education/masters-degree/physique-fondamentale-et-applications/m1-general-physics | 200 | 41346 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physik.lmu.de/en/studies/study-programs/msc-astrophysics/ | 200 | 4783 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physik.uni-heidelberg.de/studium/master | 200 | 3026 | 正文已取得；所核字段及限制见比较报告 |
| https://www.sle.kit.edu/english/vorstudium/master-physics.php | 200 | 20831 | 正文已取得；所核字段及限制见比较报告 |
| https://www.epfl.ch/education/master/programs/physics/ | 200 | 2920 | 正文已取得；所核字段及限制见比较报告 |
| https://www.uzh.ch/en/studies/programs/master/physics.html | 200 | 1339 | 正文已取得；所核字段及限制见比较报告 |
| https://programsandcourses.anu.edu.au/2027/program/NSCA | 200 | 390 | 仅取得验证／错误／极短响应；不作为核心事实来源 |
| https://handbook.unimelb.edu.au/2026/courses/mc-sci-phy/course-structure | 200 | 82 | 仅取得验证／错误／极短响应；不作为核心事实来源 |
| https://catalog.utexas.edu/graduate/areas-of-study/natural-sciences/physics/degree-requirements/ | 404 | 924 | 路径不存在；仅作路径探索记录，不支持事实 |
| https://www.physik.uni-heidelberg.de/studium/master?lang=en | 200 | 2833 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physik.uzh.ch/en/study/Study-Degree-Programmes/Master.html | 200 | 3446 | 正文已取得；所核字段及限制见比较报告 |
| https://science.anu.edu.au/study/masters/master-science-astronomy-astrophysics | 200 | 6520 | 正文已取得；所核字段及限制见比较报告 |
| https://programsandcourses.anu.edu.au/2027/course/ASTR8001 | 200 | 7587 | 正文已取得；所核字段及限制见比较报告 |
| https://catalog.utexas.edu/graduate/areas-of-study/natural-sciences/physics/ | 404 | 872 | 路径不存在；仅作路径探索记录，不支持事实 |
| https://physics.utexas.edu/academics/graduate-degree/degree-requirements | 404 | 94 | 路径不存在；仅作路径探索记录，不支持事实 |
| https://odf.u-paris.fr/fr/offre-de-formation/master-XB/sciences-technologies-sante-STS/physique-fondamentale-et-applications-K2VO0C50/master-physique-fondamentale-et-applications-m1-parcours-paris-physics-master-JS1XR1EO.html | 200 | 5830 | 正文已取得；所核字段及限制见比较报告 |
| https://www.queensu.ca/physics/people-search/kristine-spekkens | 200 | 2059 | 正文已取得；所核字段及限制见比较报告 |
| https://experts.mcmaster.ca/people/wadsley | 200 | 1616 | 正文已取得；所核字段及限制见比较报告 |
| https://apps.ualberta.ca/directory/person/mariecci | 200 | 3632 | 正文已取得；所核字段及限制见比较报告 |
| https://physics.uwo.ca/people/faculty_web_pages/barmby.html | 200 | 3117 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physics.mcgill.ca/~jcline/ | 200 | 5430 | 正文已取得；所核字段及限制见比较报告 |
| https://programsandcourses.anu.edu.au/2027/program/VSCAA | 200 | 18456 | 正文已取得；所核字段及限制见比较报告 |
| https://www.epfl.ch/schools/sb/sph/en/master/ | 200 | 1270 | 正文已取得；所核字段及限制见比较报告 |
| https://www.physik.uni-heidelberg.de/studium/msc?lang=en | 200 | 2505 | 正文已取得；所核字段及限制见比较报告 |
| https://catalog.utexas.edu/graduate/programs/ | 200 | 10234 | 正文已取得；所核字段及限制见比较报告 |
| https://physics.utexas.edu/academics/graduate | 404 | 94 | 路径不存在；仅作路径探索记录，不支持事实 |
| https://handbook.unimelb.edu.au/2025/courses/mc-sci-phy/course-structure | 200 | 83 | 仅取得验证／错误／极短响应；不作为核心事实来源 |
| https://study.unimelb.edu.au/find/courses/graduate/master-of-science-physics/what-will-i-study/ | 403 | 58 | 访问受限；未核到所需正文 |
| https://catalog.utexas.edu/graduate/programs/physics-ma/ | 200 | 1863 | 正文已取得；所核字段及限制见比较报告 |
| https://as.nyu.edu/nyu-as/as/departments/physics/programs/graduate/physics-graduate-admissions-faq.html | 200 | 18204 | 正文已取得；所核字段及限制见比较报告 |
| https://physics.uwo.ca/graduate/future_students/financial_info.html | 200 | 2129 | 正文已取得；所核字段及限制见比较报告 |

## 本地背景来源

- [原 18 校重点清单](Physics_Masters_Overview.md)：定义比较范围。
- [最新英文 CV](../CV/CV_en.md)、[科研背景](../../research-background.md)：用于个人方法背景与申请材料的证据边界。
- [加拿大导师材料索引](README.md)：识别具体导师和 Western 项目名称差异；公开导师页已在本次重新读取。

未查到可比的毕业去向或升博成功率统计。全部个人收益、相对 ANU 的强弱和申请优先建议均为基于上述事实的分析，未伪装为官方统计。

**Last-verified / last-attempted：2026-10-03。**
