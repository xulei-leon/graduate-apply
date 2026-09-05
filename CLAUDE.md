# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

Graduate school application research workspace for HY, a University of Toronto physics student (GPA 3.0/4.0, GRE 317 Q166) targeting Fall 2027 intake. The repo is a structured decision database — not broad research notes. Every entry should be source-backed with a verifiable URL and a last-verified date.

**Targets:** Physics PhD (40), Physics Master (30), Data Science Master (15)

## Repository architecture

```
physics-phd/          One .md file per advisor (not per program). Advisor files include program-level info in header.
physics-master/        One .md file per program.
ds-master/             One .md file per program (currently empty, has EXAMPLE template).
guides/                Reference: country-differences.md (US/CA/UK/CH/SG/HK/AU comparison)
*.md at root           Summary indexes linking to per-program/per-advisor files; applicant profile; targets.
AGENTS.md              Full operations manual — source priority, required fields, match logic, search workflow.
.agents/skills/        Claude Code skill definitions (school-search).
```

**Key distinction:** `physics-phd/` files are per-advisor (multiple files per university), while `physics-master/` and `ds-master/` files are per-program (one file per university/program combo).

## Primary reference: AGENTS.md

`AGENTS.md` is the authoritative operations manual. It defines:
- Source priority order (official program page → admissions page → advisor/lab site → handbook → grad school page)
- Required fields for each entry type (section 3)
- Match logic: High/Medium/Low based on overlap with dark matter, Bayesian inference, galaxy dynamics, computational astrophysics (section 4)
- Country-specific GPA interpretation (section 5)
- File rules and naming conventions (section 6)
- Search workflow and quantitative targets (section 9)

## File naming conventions

- **PhD advisor files:** `University_LastName.md` (e.g., `Berkeley_Ferraro.md`, `MIT_Necib.md`)
- **Physics Master files:** `University_ProgramAbbrev.md` (e.g., `UofT_MSc_Physics.md`, `ETH_MSc_Physics.md`)
- **DS Master files:** Follow the `EXAMPLE_UBC_MDS.md` template pattern

## Working with this repo

There are no build, test, or lint commands — this is a pure markdown research database.

When adding or updating entries:
1. Create/edit the per-program or per-advisor `.md` file first
2. Then update the folder `README.md` index table to match
3. Then update the relevant root-level summary file (`physics-phd-programs.md`, `physics-master-academic-programs.md`, `physics-master-professional-programs.md`)
4. Keep counts, region totals, and target totals synchronized across all three levels

**Ranking filter** applies only to Master programs (QS top 100 or US News top 50). PhD programs have no ranking restriction.

**Region scope:** PhD = US + Singapore only. Master = Canada, US, UK, Switzerland, Singapore, Hong Kong, Australia, Germany.

## Consistency rules from AGENTS.md

- Preserve original-source quotations, official program and policy names, and source-language terminology in English. Write synthesized reports, comparisons, recommendations, and analytical prose in Chinese.
- Do not leave placeholders in final entries unless the source truly doesn't provide the field
- Mark uncertain facts explicitly rather than inferring
- When in doubt about match level, choose the lower level until verified
- Prefer the newer official source when two sources disagree
