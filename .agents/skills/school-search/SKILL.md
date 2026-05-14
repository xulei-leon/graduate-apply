---
name: school-search
description: Graduate program and advisor research for physics and data science applicants. Use when searching for official admissions facts, checking fit, or recording programs and advisors in markdown.
---

# School Search Skill

## Purpose

Turn official admissions pages into structured, source-backed records for graduate programs and advisors.

## Use When

Use this skill when the user asks to:

- find or compare master's or PhD programs
- verify admissions requirements, deadlines, or funding
- research advisors or labs
- record a program or advisor in the repository
- update a folder summary table

## Core Rules

- Prefer official sources and stop as soon as the needed fact is confirmed.
- Record unknown items as unknown instead of guessing.
- Keep source URLs visible in every file.
- Add a last-verified date whenever a source is checked.
- Follow the existing naming convention in the target folder.
- One markdown file per program or advisor.

## Source Priority

Use sources in this order:

1. Official program page
2. Official admissions page
3. Advisor or lab website
4. Program handbook or FAQ
5. Graduate school admissions page
6. Third-party source only as backup context

If sources conflict, keep both in the notes and prefer the newer official source.

## Ranking Filter

Only include programs that meet at least one of these filters:

| Criterion | Requirement |
|---|---|
| QS World University Rankings | Top 100 overall or top 100 in a relevant subject |
| US News Best National Universities | Top 50 overall or top 50 in a relevant subject, for US schools |

Relevant subjects include Physics & Astronomy, Computer Science, Statistics, and Data Science.

## What To Capture

### Master Programs

Record these fields for each master's program:

| Field | What to record |
|---|---|
| Country | Official country name |
| University | Official school name |
| Program name | Exact program title |
| Degree type | Academic/research, professional/taught, or both |
| Track | Computational physics, data science, or other |
| Duration | Program length |
| Thesis or research | Whether a thesis or project is required |
| GPA requirement | Minimum and, if available, typical admitted level |
| GRE requirement | Required, optional, waived, or not mentioned |
| TOEFL/IELTS | Whether waived for English-instruction degrees |
| Prerequisites | Required background courses or skills |
| Cohort size | Intake or class size |
| Deadline | Main deadline and scholarship deadline if separate |
| Funding | Tuition and any scholarship, TA, or RA support |
| Source | Official program URL |
| Last verified | Date checked |
| Match | High, medium, or low with a short reason |
| Notes | Caveats and unresolved items |

### PhD Programs and Advisors

Capture program-level facts plus advisor records.

Program-level facts:

- Program name, department, and degree type
- GPA, GRE, and TOEFL/IELTS requirements
- Cohort size
- Deadline, including fellowship-priority deadlines
- Funding model, including whether self-funded study is accepted
- Direct-entry policy from bachelor's, if relevant
- Official URL

Advisor-level facts:

| Field | What to record |
|---|---|
| Name, title, department | Full name, title, and home department |
| Research focus | Narrow subfield focus |
| Current projects or grants | Active directions or funding |
| Representative papers | Recent papers from the last 3 years |
| Recruiting | Whether the lab is hiring |
| Outreach needed | Whether contact is appropriate |
| Contact status | Not contacted, emailed, replied, positive, or negative |

## Fit Logic

Use this scale consistently:

| Level | Meaning |
|---|---|
| High | Strong overlap with dark matter, Bayesian inference, galaxy dynamics, computational astrophysics, computational particle physics, or Python-based scientific computing |
| Medium | Same broad area, but not a direct topic or method match |
| Low | Weak topical and methodological overlap |

If a fit judgment depends on one missing fact, keep it unresolved rather than upgrading the fit.

## Writing Standard

- Use concise, factual language.
- Prefer short bullets and tables over long prose.
- Make deadlines, funding, and uncertainty obvious.
- Preserve the official program title and school name exactly.
- Mark high-priority or deadline-nearing items visually in summary tables.

## Workflow

1. Open the official program, admissions, or advisor page.
2. Extract only verifiable facts.
3. Decide whether the record belongs in a master program file or advisor file.
4. Write one markdown file for the entry.
5. Update the folder `README.md` summary row.
6. Add the last-verified date and any unresolved notes.

## Clarification Rule

Ask a question only if a missing detail changes the record structure or the source you should trust. Otherwise, proceed with the best verified official source and leave unresolved fields as unknown.
