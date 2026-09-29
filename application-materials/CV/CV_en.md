# Hongyi Xu

University of Toronto · hyi.xu@mail.utoronto.ca

## Education

**University of Toronto · Physics Specialist (undergraduate)**
Sep 2023–present; expected graduation: June 2027

Completed coursework: Advanced Classical Mechanics; Quantum Mechanics I; Electricity & Magnetism; Thermal Physics; Practical Physics II; Introduction to Computer Programming; Introduction to Computer Science.

## Research Interests

My primary research interest is computational physics, particularly the use of numerical methods and statistical inference to test physical models and constrain their parameters. Specific interests include:

- Particle physics: kinematic feature analysis, machine learning, and likelihood inference, with attention to how input features affect physical parameter constraints and their reliability.
- Dark matter and cosmology: numerical modelling and observational constraints of dark-matter halos, with attention to parameter degeneracy and Bayesian inference in galaxy dynamics.

During a master's program, I hope to develop stronger foundations in computational physics, statistical modelling, and relevant physical theory.

## Research Experience

### Feature Attribution and Signal-Strength Inference in Simulated Higgs Four-Lepton Events

May 2026–present; supervised by Professor Mario Campanelli, University College London

**Studied how different kinematic inputs affect signal-strength constraints in simulated Higgs four-lepton events, comparing classification performance with physical parameter inference.**

- Designed a feature-group comparison using public ATLAS simulated H → ZZ* → 2e2μ signal and background samples. Grouped 19 kinematic variables into four sets, split data by physical event group, and trained and compared MLP classifiers for all 15 nonempty combinations across five random seeds.
- Built a common pyhf profile-likelihood inference workflow, evaluated inputs using nominal 68% signal-strength interval widths, and used exact Shapley attribution to assess feature-group contributions; classifier AUC and interval width did not always rank the inputs alike.
- Ran 200 event-group bootstrap replicates and conditional coverage diagnostics to assess finite-simulation uncertainty and interval reliability. The results remain exploratory and do not establish a calibrated gain in inference precision.

First-author manuscript (in preparation): Kinematic feature attribution for signal-strength inference in simulated H → ZZ* → 2e2μ events.

Project code: https://github.com/hyi03/HiggsML

### MaNGA Galaxy Kinematics and Dark-Matter Halo Parameter Inference

2025–2026; conducted the research analysis independently

**Combined galaxy rotation-curve modelling with Bayesian population inference to study the concentration–mass relation of dark-matter halos in MaNGA disk galaxies.**

- Applied PyMC modelling and MCMC posterior sampling to rotation-curve mass decomposition, characterizing the degeneracy between halo mass and concentration for individual galaxies and quantifying parameter uncertainty.
- Analysed 620 selected disk galaxies at the population level, using prior-corrected importance sampling of individual-galaxy joint posterior samples to infer the slope, normalization, and intrinsic scatter of the concentration–mass relation.
- Assessed parameter constraints through prior predictive checks, prior-sensitivity tests, and sampling diagnostics; used inclination-sensitivity tests and PSIS diagnostics to examine the effects of model assumptions and reweighting stability on population inference.

First-author manuscript (completed; not yet submitted): [Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper-preview) (manuscript preview)

Project website: https://hyi03.github.io/manga-dm/

### Comparison of Milky Way Dark-Matter Halo Models

2021–2022; secondary-school project supervised by an external mentor

- Used Python to fit mentor-provided Milky Way kinematic data by least squares and compared the fit of NFW, Einasto, and Isothermal dark-matter halo models using rotation-curve RMSE.

## Skills

- Programming and tools: Python, PyMC, pyhf, LaTeX.
- Statistical methods: Bayesian MCMC, importance sampling, profile likelihood, bootstrap, posterior and coverage diagnostics.
- Machine learning: MLP classification, feature-group comparison, exact Shapley attribution.
- Languages: native Chinese; pursuing an undergraduate degree taught in English at the University of Toronto.
