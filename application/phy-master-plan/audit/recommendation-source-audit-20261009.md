# 重点硕士推荐信来源核查｜2026-10-09

用途：支持[19校推荐信使用方案](../Physics_Masters_Recommendation_Plan.md)。本轮通过 Python `urllib.request` 直接发送 HTTPS GET，启用默认 TLS 验证，读取正文；没有使用 webservice。HTTP成功本身不等于核实要求。只核与推荐配置相关的字段，不把整份学校档案追溯标为全部重核。

**本轮 Last-verified / last-attempted：2026-10-09。** 年度日期、旧年公告、来源冲突与访问失败分别保留。正文未含数量时不写成0封。所有链接为公开官方来源。

## 本轮直接核查

| 学校 / 来源 | 请求结果及具体确认 | 对使用方案的影响 |
|---|---|---|
| UT Austin | HTTP 200；3封，最多审阅3封；收信宽限为截止后1日历周。申请提交及缴费后触发推荐人链接。https://physics.utexas.edu/academics/admissions | P+B+C；内部提前完成，不默认使用宽限。年度12-01与Fall2027入口仍按时间表口径复核 |
| McGill | HTTP 200；2位熟悉本人工作的instructors；机构抬头、签字、日期；September admission年度12-15。https://www.physics.mcgill.ca/grads/application.html | P+B；符合身份及真实学术了解仍需本人确认 |
| EPFL | HTTP 200，跳转至现行admission-2路径；3位联系信息，至少收到2封；信件由了解本人工作的professors出具，由推荐人在线提交；信件截止为申请截止后1周；一学年仅允许一次硕士申请、一个项目。https://www.epfl.ch/education/admission/master-admission-criteria-application/online-application/ | P+B保证两封；第三位需合格，C不能因推测职称而直接计入；首轮/次轮不重复申请。当前地址：https://www.epfl.ch/education/admission/admission-2/master-admission-criteria-application/online-application/ |
| NYU GSAS | HTTP 200；3封，推荐人应了解本人学术资格、学习、科研或工作；通过申请系统提交。https://gsas.nyu.edu/nyu-as/gsas/admissions/arc/letters-of-recommendation.html | P+B+C；12-30节点引用既有时间表，未据本页重核全部日期 |
| Northwestern 独立MS | HTTP 200；项目How to Apply明确至少2封，推荐人须为熟悉本人工作的professors。页面仍为Fall2026，June30,2026截止。https://physics.northwestern.edu/graduate/master-degree/admissions.html | P+B；项目专属来源比仅用TGS最低更直接；2027窗口仍未知，另预留额度，不套PhD |
| Northwestern TGS | HTTP 200；最低2封，部分项目可增额，全部系统提交。https://www.tgs.northwestern.edu/admission/application-procedures/application-requirements/letters-of-recommendation.html | 支持“至少2”口径，最终仍查具体portal |
| Queen’s SGSPA | HTTP 200；研究型申请2份近期学术推荐，原则上由近期指导/授课的professors出具；其他来源需项目接受。https://www.queensu.ca/grad-postdoc/grad-studies/apply | P+B；不默认泛泛非学术推荐符合常规要求 |
| Queen’s applicants | HTTP 200；January7前获下一学年September入学full consideration；滚动审理并建议早申请，申请需推荐信。https://www.queensu.ca/physics/grad-studies/applicants | 年度规则，按2027-01-07准备；内部2026-12-15完成，不能理解为2027专属新公告 |
| Queen’s admission requirements | 首次TLS handshake超时；重试HTTP200，得到学位及英语条件正文，本页未定位推荐数量/January7。https://www.queensu.ca/physics/grad-studies/admission-requirements | 推荐数量和日期分别使用上两页，不能把此页HTTP200当作确认全部字段 |
| McMaster | HTTP 200；校级至少2位熟悉学术工作的instructors，部分项目需3位；eReference。https://gs.mcmaster.ca/how-to-apply/ | 暂预算B+C，Physics具体人数继续查portal；01-31/04-30引用既有时间表 |
| Western how-to | HTTP 200；录入/更新推荐人信息后2小时内发邮件；学校收集在线推荐，不需纸质信；未定位Physics固定人数。https://physics.uwo.ca/graduate/future_students/how_to_apply.html | B+C只为两位预算，不能称已核必须2封；准备好后才输入推荐信息，避免过早自动邀请 |
| Western admission requirements | HTTP 200；明确国际生March1,2027，含推荐信与成绩单；滚动发offer，宜早申请。https://physics.uwo.ca/graduate/future_students/admission_requirements.html | 01-31为内部目标，03-01为官方项目节点；Astronomy改轨时另核 |
| IP Paris HEP M1 | HTTP 200；2份academic references，推荐人直接在线添加。https://www.ip-paris.fr/en/education/graduate-programs/masters-science/physics-program/master-year-1-high-energy-physics | P+B；2027轮次仍引用时间表的待公布状态，不把往年推算当新公告 |
| PSL项目页 | HTTP 200；取得ICFP项目正文，本次文本检索未定位推荐信要求；不能仅据该页宣布已重核数量。https://psl.eu/en/education/master-s-degree-physics | 推荐信要求采用ENS专页 |
| ENS ICFP专页 | HTTP 200；M1需2 Letters of Reference；M1栏明确2026-11-26开窗、2027-01-22申请及收信共同截止；同段标题为2026/2027，M2仍列2026日期。https://www.phys.ens.fr/fr/formations/master-icfp | 采用01-22做保守准备，内部01-10；保留与旧PSL2026周期及仓库01-23参考的来源标签差异，开窗后核实际M1批次 |
| Paris-Saclay M1 General Physics | HTTP 200；必交材料未列推荐信，列Referring contact information，括注compulsory for non-international applicants；不能把联系信息等同于2封入学信。页面申请期为2026-01-01至2026-07-06。https://www.universite-paris-saclay.fr/en/education/masters-degree/physique-fondamentale-et-applications/m1-general-physics | 普通申请0次基础预留，2027要求以portal为准；旧年日期不直接改成2027 |
| Paris-Saclay国际硕士奖学金 | HTTP 200；受邀者如适用须填2位references，推荐人在线评价；页面仍列2026截止。https://www.universite-paris-saclay.fr/en/admission/bourses-et-aides-financieres/international-masters-scholarships-program | 获邀请且符合条件才触发B追加+C；不套成普通入学必须2封，不等待普通入学最后截止再争奖学金 |
| LMU Astrophysics申请 | HTTP 200；信件可选、不必交，可直接由推荐人发送1封或更多，申请人递交的信不接受。https://www.physik.lmu.de/en/studies/study-programs/applying-to-a-masters-program/ | 基础不占强信；有实质强信及额度时再考虑；官网指定地址按执行时正文核对 |
| Alberta | HTTP 403，无法读取当前招生核心正文。https://www.ualberta.ca/en/physics/graduate-studies/admissions.html | 资格、窗口、推荐要求及人数继续待核；暂不激活额度 |
| Melbourne | HTTP 403，无法读取当前核心入学要求。https://study.unimelb.edu.au/find/courses/graduate/master-of-science-physics/entry-requirements/ | 2027 intake及推荐清单待核；暂不激活额度；EOI表与推荐信分开 |

## 只引用既有档案，本轮未重新访问

以下事实依据项目档案的2026-10-02推荐要求记录及后续仓库备注，**不标为本轮已在线核实**；实际执行前查2027 portal。

| 学校 | 继承状态 | 官方来源 / 本地记录 |
|---|---|---|
| Sorbonne / Paris Cité联合PPM | 项目专属推荐人数、渠道待核，不能推断免推荐；两校记录不重复预算 | https://master.physique.sorbonne-universite.fr/fr/candidatures-inscription.html ；[Sorbonne档案](../../../physics-master/Sorbonne_Master_FundamentalPhysics.md) |
| Heidelberg | 既有公开清单未列推荐信固定数量；未列不等于已确认0封 | https://www.physik.uni-heidelberg.de/studium/master?lang=en ；[项目档案](../../../physics-master/Heidelberg_MSc_Physics.md) |
| KIT | 既有公开清单未列推荐信固定数量；未列不等于已确认0封 | https://www.sle.kit.edu/english/vorstudium/master-physics.php ；[项目档案](../../../physics-master/KIT_MSc_Physics.md) |
| UZH | 既有公开清单未列推荐信固定数量；未列不等于已确认0封 | https://www.physik.uzh.ch/en/study/Study-Degree-Programmes/Master/admission.html ；[项目档案](../../../physics-master/UZH_MSc_Physics.md) |

名单以[总览](../Physics_Masters_Overview.md)最新Summary为准；排期参照[时间表](../Physics_Masters_Timeline.md)，Queen’s年度January7和ENS页面明确January22另作上述证据补充。推荐效果、P/B/C与申请人的关系、国内实际职务与容量、增额价格不由官方网页推断，待本人确认。来源核查不等于导师联系、招生办公室回复或推荐人承诺。

## UBC新增重点冲刺补核（2026-10-09）

用户将UBC加入重点冲刺，8校各保留P/B。直接HTTPS访问Physics MSc官方页HTTP200；正文确认需3份references，下一批次application open dates and deadlines尚未配置。因此配P＋B＋C，日期保留待公布，不推断B所在学校能影响录取；Astronomy路径如最终采用须另核。官方URL：https://www.grad.ubc.ca/prospective-students/graduate-degree-programs/master-of-science-physics 。本轮仅重核这两项，不追溯重核全部UBC资料。
