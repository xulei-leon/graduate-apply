# Hongyi Xu

hyi.xu@mail.utoronto.ca · https://github.com/hyi03

## Research Interests

Computational and high-energy physics; statistical inference; Bayesian modeling; machine learning for particle and astrophysics research.

## Education

**University of Toronto**, Sept 2023–June 2027 (expected)
Major: Honours Bachelor of Science (HBSc), Physics Specialist, Toronto, Canada


**Selected completed coursework:** Advanced Classical Mechanics; Advanced Physics Lab; Electricity & Magnetism; Thermal Physics; Electromagnetic Theory; Quantum Mechanics I; Introduction to Computer Programming; Introduction to Computer Science.

**Selected coursework in progress:** Computational Physics; Quantum Mechanics II; Nonlinear Physics; Introduction to High Energy Physics; Time Series Analysis; Relativistic Electrodynamics; Statistical Mechanics.

## Research Experience

### Feature Attribution for Higgs Four-Lepton Signal-Strength Inference

May 2026–Present

Research Project, advisor: Prof. Mario Campanelli, University College London · Remote

- Investigated how kinematic feature selection affects signal-strength inference in simulated Higgs four-lepton events, using public ATLAS H → ZZ* → 2e2μ signal and background samples.
- Designed a systematic comparison of 19 kinematic variables, grouping them into four feature sets and evaluating all 15 nonempty combinations with MLP classifiers across five random seeds; built a unified pyhf profile-likelihood pipeline to compare classification performance with physical parameter constraints.
- Applied exact Shapley attribution, 200 event-group bootstrap replicates, and conditional coverage diagnostics to assess feature contributions and inference reliability, finding that classifier AUC and signal-strength interval width did not always favor the same feature inputs.

Manuscript: First-author manuscript in preparation; Code: https://github.com/hyi03/HiggsML

### MaNGA Kinematics and Dark-Matter Halo Inference

2025–2026

Independent Research

- Developed a rotation-curve mass-decomposition pipeline using Python and PyMC for 620 selected MaNGA disk galaxies, combining galaxy-level posteriors with population-level inference of the dark-matter halo concentration–mass relation.
- Applied MCMC and prior-corrected importance sampling to infer the relation’s slope, normalization, and intrinsic scatter while characterizing halo mass–concentration degeneracy and parameter uncertainty.
- Tested robustness using prior predictive checks, prior-sensitivity analyses, sampling diagnostics, inclination-sensitivity tests, and PSIS diagnostics; recovered a modest negative concentration–mass slope (α = −0.093) for the selected galaxies under fixed photometric inclinations, with subsample tests identifying inclination uncertainty as a major limitation.

Manuscript: First-author manuscript (completed; not yet submitted): [Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper/Local_Concentration__Mass_Relation_from_MaNGA.pdf) (PDF)

Project website: https://hyi03.github.io/manga-dm/

## Technical Skills

- Programming & Tools: Python, PyMC, pyhf, LaTeX.
- Statistical Methods: Bayesian inference, MCMC, importance sampling, profile likelihood, bootstrap, posterior predictive checks, PSIS diagnostics.
- Machine Learning: MLP classification, feature-group comparison, Shapley attribution.
- Languages: Mandarin Chinese (native); English (pursuing an undergraduate degree taught in English).
