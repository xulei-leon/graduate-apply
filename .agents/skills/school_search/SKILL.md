---
name: school_search
description: Graduate school search and requirements capture for physics/DS applicants. Use when searching for programs, advisors, or recording admission data. Includes ranking filters, required fields per program type, match logic, and country-specific GPA interpretation.
---

# School Search — Graduate Application Research

## Ranking Filter

Only consider programs meeting at least one criterion:

| Criterion | Details |
|-----------|---------|
| QS World University Rankings | Top 100 overall **or** top 100 in relevant subject (Physics & Astronomy, Computer Science, Statistics, Data Science) |
| US NEWS Best National Universities (US only) | Top 50 overall **or** top 50 in relevant subject |

## Source Priority

Use in this order; stop once the needed field is confirmed:

1. Official program page
2. Official admissions page
3. Advisor or lab website
4. Program handbook or FAQ
5. Graduate school admissions page
6. Third-party aggregators only as backup context, never primary source

If two sources disagree, keep both in notes and prefer the newer official source.

## Required Data Fields

### Master Programs

For every Master entry, capture in a per-program `.md` file and the folder summary table:

| Field | What to record |
|-------|----------------|
| Country | Official country name |
| University | Official school name |
| Program name | Exact program title |
| Master type | Academic/Research or Professional (taught) |
| Duration | Program length (e.g., 1 year, 2 years) |
| Research/thesis | Whether thesis or research project required |
| Track | Computational physics, data science, or other |
| GPA requirement | Minimum and typical admitted level |
| GRE requirement | Required, optional, waived, or not mentioned |
| TOEFL/IELTS | Whether waived for English-instruction degrees |
| Prerequisites | Required background courses or skills |
| Cohort size | Intake or class size |
| Deadline | Main deadline and scholarship deadline if separate |
| Funding | Tuition and any scholarship/TA/RA support |
| Tuition | Exact tuition (international) |
| Source | Official program URL |
| Last verified | Date checked |
| Ranking | QS overall rank and Physics subject rank; US NEWS for US schools |
| Match | High / Medium / Low with one-sentence reason |
| Notes | Caveats including country-specific issues |

### PhD Programs

For each PhD entry, capture program-level data plus advisor records.

**Program-level:**

- Program name, department, degree type
- GPA / GRE / TOEFL requirements
- Cohort size
- Deadline, including fellowship-priority deadlines
- Funding model, including whether self-funded is accepted
- Official URL

**Advisor-level (create one file per advisor):**

| Field | What to record |
|-------|----------------|
| Name, title, department | Full name, title, home department |
| Research focus | Narrowed to subfield level |
| Current projects/grants | Active research direction |
| Representative papers | Last 3 years |
| Recruiting | Whether the lab is hiring |
| Outreach needed | Whether contact is appropriate |
| Contact status | Not contacted / Emailed / Replied / Positive / Negative |

### Data Science Master Programs

Same fields as Master Programs above. Prioritise programs that explicitly welcome non-CS majors or accept physics backgrounds.

## Master Type Classification

| Type | Characteristics |
|------|----------------|
| Academic/Research | Thesis required; research-oriented; prepares for PhD |
| Professional (taught) | Coursework-oriented; no thesis or optional project; industry-focused |
| Both tracks | Offers both options — include in both summary tables |

## Match Logic

| Level | Meaning |
|-------|---------|
| High | Strong overlap with dark matter, Bayesian inference, galaxy dynamics, computational astrophysics, or Python-based scientific computing |
| Medium | Same broad area, but not a direct method or topic match |
| Low | Weak topical and methodological overlap |

## Country / GPA Interpretation

- **United States:** GPA 3.0 is below common PhD/master applicant average; research and writing quality matter more
- **Canada:** GPA 3.0 is often within range for many Master programs, especially at U of T peers
- **UK:** U of T 3.0 ≈ 2:1 range for many institutions
- **Switzerland:** Course fit matters heavily; strict prerequisite checking
- **Singapore, Hong Kong, Australia:** U of T recognition helpful; funding and prerequisite fit still matter
- **Germany:** GPA 3.0 (~2.5 German) is below typical BSc average; research may compensate

Use Safe/Match/Reach as planning aids only, not guarantees.

## Summary Table Columns

### Master Summary Tables

Include these columns:
`# | Country | University | QS rank | US NEWS | Program | Type | Duration | Thesis | Track | GPA req | GRE req | Deadline | Tuition | Match | Difficulty`

Sort by region. Within each region:
- US schools: sort by US NEWS rank ascending
- Other regions: sort by QS rank ascending

## File Rules

- One `.md` file per program or advisor
- Follow existing naming convention in each folder
- Keep source URLs visible
- Add last-verified date
- Update contact status as it changes
- Mark high-priority or deadline-nearing items visually

## Search Prompts by Category

| Category | Search Query Pattern |
|----------|---------------------|
| Physics PhD | `site:edu "Physics PhD" admissions requirements` |
| Physics Master | `site:edu "Master of Science" Physics` |
| Canada | `site:ca "MSc" Physics admission requirements` |
| UK (taught) | `site:ac.uk "MSc" Physics entry requirements` |
| UK (research) | `site:ac.uk "MSc by Research" Physics` |
| Switzerland | `site:ch "Master" Physics ETH` or `site:ch "Master" Physics EPFL` |
| Germany | `site:de "Master of Science" Physics English` |
| Singapore | `site:edu.sg "Master" Physics` |
| Hong Kong | `site:edu.hk "MSc" Physics` |
| Australia | `site:edu.au "Master" Physics` |
| Data Science | `site:edu "Data Science" Master admission requirements` |
| Advisor search | `dark matter Bayesian professor physics`, `galaxy dynamics MCMC professor` |

## Workflow

1. For each target, open the official program/admissions/advisor page
2. Extract all required fields (see above)
3. Save a single `.md` file in the correct folder
4. Update the folder `README.md` index table with a summary row
5. After all targets captured, verify completeness and consistency
