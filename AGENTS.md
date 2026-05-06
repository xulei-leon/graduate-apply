# AGENTS — 项目指南

## 项目概述

本项目的目的是帮助申请人 HY （多伦多大学物理专业，GPA 3.0）搜寻和整理研究生（硕士/博士）申请信息，用于申请 **2027年秋季** 入学。

### 申请人背景摘要

- **本科：** 多伦多大学，物理专业，GPA 3.0/4.0，大三在读（2024–2028）
- **GRE：** 317（Q 166）
- **TOEFL/IELTS：** 免考（英语授课大学）
- **科研：**
  - 科研一：暗物质晕 c–M 关系贝叶斯推断，使用 MaNGA 数据 + PyMC 5 做 MCMC。一作论文已完成，本周提交 arXiv 预印本，后续投稿期刊。导师为普林斯顿大学教授，商业班课项目，推荐信非强推。
  - 科研二：与 UCL 物理教授一对一科研，刚启动，课题未定。推荐信视表现而定。
- **技能：** Python（2门课 GPA 4.0），PyMC 5（贝叶斯 MCMC）
- **目标方向：** 计算物理（PhD + Master）& 数据科学（Master）混申
- **获奖：** 大学期间无获奖

## 搜索任务指南

当执行学校/导师搜索任务时，请遵循以下规范：

### 1. 信息来源优先级

1. **学校官方项目网页** — 最权威
2. **学校官方招生/ admissions 页面**
3. **导师个人 / lab 网站** — 查看研究方向、论文、funding
4. **项目 handbook / FAQ 页面**
5. **Graduate School 申请要求页面**
6. 第三方汇总站（如 US News、QS、thegradcafe 等）仅作参考

### 2. 硕士项目搜索要点

对每个硕士项目，需提取以下信息并填入对应文件夹 `physics-master/README.md` 或 `ds-master/README.md`：

| 字段 | 说明 |
|------|------|
| 国家 | 所在国家 |
| 学校 | 官方名称 |
| 项目名称 | 精确的项目全称 |
| 方向 | 计算物理 / 数据科学 / 其他 |
| GPA 要求 | 最低要求或平均水平 |
| GRE 要求 | 是否必需，有无最低分 |
| TOEFL/IELTS | 是否免考（本科英语教学） |
| 先修课要求 | 是否需要特定课程背景 |
| 招生人数/规模 | 总录取人数或项目规模 |
| 截止日期 | 主要截止日期（含奖学金截止） |
| 费用/奖学金 | 学费 + 是否有奖学金/TA/RA |
| 链接 | 官方项目页面 URL |
| 匹配度评估 | 高/中/低，说明理由 |
| 备注 | 其他注意事项 |

### 3. 博士项目搜索要点

对每个博士项目和导师，需提取以下信息：

#### 项目层面
- 项目名称、所属院系、学位类型（PhD）
- GPA / GRE / TOEFL 要求
- 招生规模
- 截止日期（含 fellowship 优先截止）
- 是否接受自费 / 是否有 guaranteed funding
- 链接

#### 导师层面
- 姓名、职称、所属院系
- **研究方向**（具体到子领域）
- **当前课题 / 基金项目**（查看 lab website / grants）
- **代表性论文**（近3年，关注方法与课题相关度）
- **是否招生**（lab website 通常有说明）
- **匹配度评估**（高/中/低）
  - 高：研究方向高度重合，申请人技能（PyMC/Bayesian/计算物理）直接相关
  - 中：方向相关，但不是最直接匹配
  - 低：方向关联度低
- **是否需要套磁**（是 / 否 / 不确定）
- **套磁状态**（未联系 / 已发送 / 已回复 / 积极 / 消极）

### 4. 匹配度评估标准

#### 高匹配
- 导师研究方向与申请人科研经历（暗物质、Bayesian inference、星系动力学、计算天体物理）高度重合
- 或者：导师使用 Bayesian / MCMC / PyMC 等类似方法学
- 或者：计算物理方向，且申请人 Python 技能直接可用

#### 中匹配
- 研究方向属于计算物理大类，但具体课题不同
- 数据科学方向，特别是与物理/科学计算结合的项目

#### 低匹配
- 方向差距大，且技能不相关

### 5. 输出格式

每个学校/导师创建一个单独的 `.md` 文件，命名规范：

- 硕士项目：`physics-master/学校名_项目名.md` 或 `ds-master/学校名_项目名.md`
- 博士项目：`physics-phd/学校名_导师姓.md`

同时在对应文件夹的 `README.md` 表格中汇总。

### 6. 文件更新规范

- 先阅读已存在的文件，避免重复
- 每次搜索后更新对应表格
- 套磁进展实时更新
- 截止日期临近的项目高亮标记

### 7. 数据科学硕士的特殊说明

- 数据科学硕士通常属于统计/计算机学院，也可能有专门的 Data Science Institute
- 优先找与国家地区匹配且接受物理背景的项目
- 关注是否有 "不限背景" 或 "STEM 背景均可" 的描述
- 注意先修课要求（如 CS 课程、统计课程等）

### 8. 关键日期提醒

- 申请季：2026年秋 – 2027年初（fall 2027 入学）
- 提前批次 / 奖学金截止通常在 12月–1月
- 建议在 2026年9月前完成套磁

### 9. GPA 3.0 竞争力定位

在不同国家的申请体系中，GPA 3.0 的竞争力不同：

| 国家 | 竞争力定位 | 说明 |
|------|-----------|------|
| **美国** | **偏低** | 研究型 PhD / Master 项目通常期望 3.3+。优势在于科研经历和论文可弥补 GPA 短板。建议扩大选校范围至排名 30–80 的学校 |
| **加拿大** | **中等** | U of T 本校 GPA 3.0 在加拿大体系内仍可申请大多数 Master 项目，但非保底 |
| **英国** | **中等偏低** | 英国要求学位等级（一等/二等一）。多伦多大学 3.0 约对应 UK 2:1（60–65%），**非 G5 学校**仍有竞争力 |
| **瑞士** | **中等** | ETH Zurich / EPFL 看重学术背景和课程匹配度，GPA 3.0 在边缘范围但可尝试 |
| **新加坡** | **中等** | NUS / NTU 对 U of T 出身认可度较高，GPA 3.0 可申，科研经历加分 |
| **香港** | **中等** | HKU / CUHK / HKUST 对 U of T 认可度高，GPA 3.0 在范围内 |
| **澳大利亚** | **中等** | 澳洲八大通常要求相当于澳洲 65%+ 的水平，U of T 3.0 在范围内 |

### 10. 分级分类标准 (Safe / Match / Reach)

搜索时对每个项目给出分类：

| 等级 | 定义 | GPA 参考范围 | 示例 |
|------|------|-------------|------|
| **Reach** | 录取率低或要求明显高于背景 | 项目平均 GPA > 3.5 | Ivy League + MIT/Stanford/Caltech 的 PhD 项目；G5 的强竞争项目 |
| **Match** | 背景在录取范围的中位或偏下 | 项目平均 GPA 3.0–3.5 | 排名 30–60 的美国物理 PhD；加拿大/澳洲/香港 Master；非 G5 英国 Master |
| **Safe** | 背景明显高于录取平均水平 | 项目平均 GPA < 2.8 或已知录取友好 | 低排名学校或录取率高的项目。**物理/DS Master 中很少存在"保底"，需谨慎判断** |

分类说明：
- 申请人 GPA 3.0 偏低，**不应过度依赖 "Safe" 分类**，即使分类为 "Safe" 也不能保证录取
- Reach/Match/Safe 应在学校对应的 `备注` 字段标注
- 分类应结合项目具体要求而非仅看排名
- 论文发表 + 科研经历可使 Match 升级为强 Match，或 Reach 降级为 Match

### 11. 信息提取 Checklist

搜索每个项目时，按以下路径查找各字段：

| 字段 | 查找位置 | 备注 |
|------|---------|------|
| GPA 要求 | Admissions → Requirements | 多数写最低要求（如 3.0/4.0）或"strong academic record"；英国看学位等级要求 |
| GRE 要求 | Admissions → Requirements / FAQ | 是否 required / recommended / waived for 2027 |
| TOEFL/IELTS | Admissions → International | 英语授课本科满 X 年通常免考 |
| 先修课 | Program curriculum / handbook / FAQ | 特别注意线性代数、微积分、统计、编程要求 |
| 学费 | Program tuition page | 区分本地/国际生 |
| 奖学金 | Funding / Financial Aid | 是否 automatic consideration / 需单独申请 |
| 招生人数 | Program page / About | 也可在 GradCafe / 论坛查 |
| 截止日期 | Admissions → Deadlines | 区分 priority / regular / scholarship deadline |
| 导师研究 | Lab website → People + Research + Publications | 看 Recent publications (近 3 年)、Grants、Open positions |
| 导师是否招生 | Lab website / FAQ / Email | 明确写 "recruiting" / "hiring" / "accepting students" 为 Yes；否则默认 Unknown |

### 12. 搜索查询模板

根据不同目标国家和平台，推荐使用以下搜索词（依需要组合）：

#### 按国家
- **美国 PhD:** `site:edu "Physics PhD" admissions requirements`
- **美国 Master:** `site:edu "Master of Science" Physics`
- **加拿大 Master:** `site:ca "MSc" Physics admission requirements`
- **英国 Master:** `site:ac.uk "MSc" Physics entry requirements`
- **瑞士 Master:** `site:ch "Master" Physics ETH` / `site:ch "Master" Physics EPFL`
- **新加坡:** `site:edu.sg "Master" Physics` / `site:edu.sg "PhD" Physics`
- **香港:** `site:edu.hk "MSc" Physics`
- **澳大利亚:** `site:edu.au "Master" Physics`

#### DS Master 专项
- `site:edu "Data Science" Master admission requirements`
- `"Data Science" MSc "application requirements" 2027`
- `"Master of Data Science" prerequisites`

#### 导师搜索
- `site:edu "dark matter" "Bayesian" professor physics` — 找方向匹配的教授
- `"galaxy dynamics" "MCMC" "professor"` — 找方法匹配的教授
- `site:edu "faculty" "computational astrophysics"` — 计算天体物理方向
- 进入导师 lab 网站后查看:  People →  Publications →  Research →  Join / Openings
