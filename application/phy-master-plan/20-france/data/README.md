# 法国分析数据与来源

五校统计核查日期：2026-10-07。市场概览底表原核查日期：2026-10-06。所有来源通过直接 HTTPS 取得。

## 五校物理硕士国际生五年统计

对应[统计报告](../Five_Universities_Physics_Master_International_2020_2025.md)，期间为 2020—2021 至 2024—2025。

| 文件 | 内容 |
|---|---|
| [five-universities-physics-international-2020-2025.csv](five-universities-physics-international-2020-2025.csv) | 25 个学校—年度记录；M1／M2 国际流动注册数，以及新生、名额、申请、offer、录取率缺失状态 |
| [five-universities-physics-sise-source-20261007.json](five-universities-physics-sise-source-20261007.json) | 官方完整 80 行分组响应，20 行独立年度国际汇总，28 行组件汇总，数据集年份与 IP Paris 检索响应 |
| [five-universities-physics-query-manifest.json](five-universities-physics-query-manifest.json) | 直接 HTTPS 查询、实时字段、国际定义、25 行结构化数据、独立列出的 General Physics 2026—2027 总容量 |
| [five-universities-physics-estimates-20261007.json](five-universities-physics-estimates-20261007.json) | 历史人数范围取整及 Hcéres 比例情景；记录每项假设，不作为官方名额或招生结果 |
| [five-universities-physics-source-audit-20261007.json](five-universities-physics-source-audit-20261007.json) | 五校 Hcéres PDF URL、查阅页码、文件 SHA256、IP Paris 年报 URL 和访问缺口 |

数值为空或 JSON `null` 表示未核实，不表示零；`stock` 表示在校注册存量，不是新招人数。国际在校口径为 SISE `mobilite_intern="M"`、`sect_disciplinaire="02"`、`diplome="MAS_M_MAS_AUT"`，汇总 `effectif_sans_cpge`。IP Paris 未取得同口径数据；官方主表不以 Hcéres 的 40%—60% 国际生比例补成确数；应用户要求，另在估算 JSON 中计算情景范围。新生、申请、offer 与录取率官方字段均保持缺失。

原始页面、评估 PDF 和年报在仓库 `tmp/france-five-research-20261007/`；它们不作为额外分析文档展示。

官方入口：

- https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-sise-effectifs-d-etudiants-inscrits-esr-public/
- https://data.enseignementsup-recherche.gouv.fr/api/explore/v2.1/catalog/datasets/fr-esr-sise-effectifs-d-etudiants-inscrits-esr-public/records
- https://www.hceres.fr/fr/recherche
- https://www.ip-paris.fr/en/about/facts-and-figures/annual-reports

## 市场概览底表

对应保留的[法国留学市场概览](../france-study-market-20261006.md)。

- `annual-students.csv`：全国及中国籍在校规模；早期全国数保留约值。
- `china-stock-series.json`：中国籍在校历年来源记录。
- `chinese-study-visas.csv`：中国学生法国学习签证数量，非录取／新生人数。
- `chinese-university-degree-levels-2024-2025.csv`：大学中国学生 Licence／Master／Doctorat 分类。
- `university-foreign-master-students.csv`：大学外国籍硕士阶段在校规模。
- `mon-master-national-2024-2025.csv`、`mon-master-national-aggregates.json`、`mon-master-2025-non-alternance-disciplines.json`：概览中的全平台参考，均不是国际生统计。

官方入口：

- https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-effectifs-d-etudiants-etrangers-france/
- https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-mon_master/
- https://ressources.campusfrance.org/publications/mobilite_pays/fr/chine_fr.pdf
- https://www.campusfrance.org/system/files/medias/documents/2025-09/20250905_CP_rentree_campusfrance_VDEF.pdf

## 历史来源数据

旧的四份分析正文已删除。既有来源底表仍留存以便追溯，不作为新报告的五校国际招生数据：

- `physics-master-admissions-by-year.csv`、`physics-master-admissions-by-mention.csv`、`physics-master-projects-2024-2025.csv`、`physics-master-query-manifest.json`：2023—2025 Mon Master 总体条目与 offer，不能筛出国际生。
- `physics-master-sise-enrollment-2022-2025.csv`、`physics-master-international-enrollment-2022-2025.csv`、`physics-international-stock-source-20261007.json`、`physics-master-international-query-manifest.json`：此前全国公立物理分类的在校统计，不是五校细分招生。

国际项目全体人数不等于国际生人数，联合项目不重复汇总，中国单一国籍字段仍未核实。
