# AGENTS — 项目操作手册

## 0. Purpose

This repository tracks graduate school options for HY, a University of Toronto physics student targeting Fall 2027 admission. The primary job of any assistant working here is to transform scattered admissions facts into a reliable application database.

## 1. Applicant snapshot

- University of Toronto, Physics, GPA 3.0/4.0, junior standing
- GRE 317, Q166
- TOEFL/IELTS waived because the degree is from an English-instruction university
- Research 1: Bayesian inference on the dark-matter halo c-M relation using MaNGA data and PyMC 5; first-author paper is ready for arXiv submission and later journal submission; LoR is likely weak because the project was a commercial class-project arrangement
- Research 2: one-on-one project with a UCL physics professor, started in May 2026; topic and LoR strength remain uncertain
- Skills: Python, PyMC 5, Bayesian MCMC
- Targets: Physics PhD, Physics Master, Data Science Master

## 2. Source priority

Use sources in this order and stop as soon as the needed field is confirmed:

1. Official program page
2. Official admissions page
3. Advisor or lab website
4. Program handbook or FAQ
5. Graduate school admissions page
6. Third-party aggregators only as backup context, never as the primary source

If two sources disagree, keep both in the notes and prefer the newer official source.

## 3. Required data by program type

### 3.1 Master programs

For every Master entry, capture these fields in the relevant folder README and in a per-program file:

| Field | What to record |
|------|----------------|
| Country | Official country name |
| University | Official school name |
| Program name | Exact program title |
| Track | Computational physics, data science, or other |
| GPA requirement | Minimum and, if available, typical admitted level |
| GRE requirement | Required, optional, waived, or not mentioned |
| TOEFL/IELTS | Whether waived for English-instruction degrees |
| Prerequisites | Required background courses or skills |
| Cohort size | Intake size or class size |
| Deadline | Main deadline and scholarship deadline if separate |
| Funding | Tuition and any scholarship/TA/RA support |
| Source | Official program URL |
| Match | High, medium, or low, with one-sentence reason |
| Notes | Any caveats, including country-specific issues |

### 3.2 PhD programs and advisors

For every PhD program, capture the program-level fields above plus advisor records.

Program-level fields:

- Program name, department, degree type
- GPA / GRE / TOEFL requirements
- Cohort size
- Deadline, including fellowship-priority deadlines
- Funding model, including whether self-funded study is accepted
- Official URL

Advisor-level fields:

- Name, title, department
- Research focus, narrowed to the subfield level
- Current projects or grants
- Representative papers from the last 3 years
- Whether the lab is recruiting
- Whether outreach is needed
- Contact status: not contacted, emailed, replied, positive, negative

## 4. Match logic

Use this scale consistently across programs and advisors:

| Level | Meaning |
|------|---------|
| High | Strong overlap with dark matter, Bayesian inference, galaxy dynamics, computational astrophysics, or Python-based scientific computing |
| Medium | Same broad area, but not a direct method or topic match |
| Low | Weak topical and methodological overlap |

If the evaluation depends on a single missing fact, mark it as unknown rather than upgrading the fit.

## 5. Country and GPA interpretation

- United States: GPA 3.0 is below the common PhD/master applicant average, so research and writing quality matter more than ranking alone
- Canada: GPA 3.0 is often within range for many Master programs, especially at U of T peers or closely related schools
- UK: interpret GPA through degree classification; U of T 3.0 is roughly comparable to a 2:1 range for many institutions
- Switzerland: course fit matters heavily; use strict prerequisite checking
- Singapore, Hong Kong, Australia: U of T recognition is usually helpful, but funding and prerequisite fit still matter

Do not use Safe/Match/Reach as a guarantee. These labels are only planning aids.

## 6. Output and file rules

- Create one markdown file per school or advisor before updating the folder summary table
- Use the naming convention already defined in each folder
- Keep source URLs visible in every file
- Add a last-verified date when a source is checked
- Update contact status as soon as it changes
- High-priority or deadline-nearing items should be visually marked in the summary table

## 7. Search prompts

Use these query patterns when starting a new search:

- Physics PhD: site:edu "Physics PhD" admissions requirements
- Physics Master: site:edu "Master of Science" Physics
- Canada: site:ca "MSc" Physics admission requirements
- UK: site:ac.uk "MSc" Physics entry requirements
- Switzerland: site:ch "Master" Physics ETH or site:ch "Master" Physics EPFL
- Singapore: site:edu.sg "Master" Physics or site:edu.sg "PhD" Physics
- Hong Kong: site:edu.hk "MSc" Physics
- Australia: site:edu.au "Master" Physics
- Data Science: site:edu "Data Science" Master admission requirements
- Advisor search: dark matter Bayesian professor physics, galaxy dynamics MCMC professor, computational astrophysics faculty

## 8. Quality bar

Every entry should make the next model's job easier by answering four questions without interpretation: can the applicant apply, what is required, how strong is the fit, and what source supports the claim. If a field cannot be verified from a reliable source, leave it explicitly unresolved.
