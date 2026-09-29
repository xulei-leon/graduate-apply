# Hongyi Xu

University of Toronto · hyi.xu@mail.utoronto.ca

## Education

**University of Toronto · Physics Specialist (undergraduate)**
September 2023–present; expected graduation: June 2027

Completed coursework: Advanced Classical Mechanics; Quantum Mechanics I; Electricity & Magnetism; Thermal Physics; Practical Physics I / II; Advanced Calculus; Linear Algebra I / II; Ordinary Differential Equations; Introduction to Computer Programming; Introduction to Computer Science.

## Research Interests

My primary research interest is computational physics, particularly the use of numerical methods and statistical inference to test physical models and constrain their parameters. Specific interests include:

- Particle physics: kinematic feature analysis, statistical inference, and uncertainty assessment.
- Dark matter and cosmology: numerical modelling of dark-matter halos and their observational constraints.

I hope to deepen my training in computational methods and the relevant physics theory during a master's program.

## Research Experience

### Feature Attribution and Signal-Strength Inference in Simulated Higgs Four-Lepton Events

May 2026–present; supervised by Professor Mario Campanelli, University College London

**Used MLP classification, likelihood inference, and feature attribution to study how kinematic inputs affect signal-strength constraints in simulated Higgs four-lepton events.**

- Designed a feature-group comparison: processed public ATLAS simulated H → ZZ* → 2e2μ signal and background samples, divided 19 kinematic variables into four groups, split data by physical event group, and trained and compared MLP classifiers for all 15 nonempty feature-group combinations across five random seeds.
- Built a common pyhf profile-likelihood inference workflow, compared inputs using nominal 68% signal-strength interval widths, and used exact Shapley attribution to decompose the contributions of the four feature groups to interval width.
- Conducted 200 event-group bootstrap replicates and conditional coverage diagnostics to examine uncertainty from finite simulated samples and interval calibration.
- Project code: https://github.com/hyi03/HiggsML
- First-author manuscript (in progress): Kinematic feature attribution for signal-strength inference in simulated H → ZZ* → 2e2μ events.

### MaNGA Galaxy Kinematics and Dark-Matter Halo Parameter Inference

2025–2026; completed the project independently

**Used Bayesian modelling and population inference to study the mass–concentration relation of dark-matter halos in MaNGA disk galaxies.**

- In rotation-curve mass decomposition, found that obtaining a single optimum by numerical optimization could not adequately capture the degeneracy and uncertainty in halo mass and concentration.
- Learned and applied PyMC Bayesian modelling and MCMC posterior sampling to characterize the relationship between halo mass and concentration; used prior predictive checks, prior-sensitivity tests, and sampling diagnostics to assess how parameter constraints depend on the data and priors.
- Conducted a population analysis of 620 selected disk galaxies. Used prior-corrected importance sampling to infer the slope, normalization, and intrinsic scatter of the concentration–mass relation from individual-galaxy joint posterior samples; used inclination-sensitivity checks and PSIS diagnostics to assess limitations arising from model assumptions and reweighting stability.
- Project website: https://hyi03.github.io/manga-dm/
- First-author manuscript (completed): [Bayesian Hierarchical Inference of the Dark Matter Halo Concentration–Mass Relation from MaNGA Disk Galaxy Rotation Curves](https://hyi03.github.io/manga-dm/paper-preview)

### Comparison of Milky Way Dark-Matter Halo Models

2021–2022; secondary-school project supervised by an external mentor

**Used rotation-curve fitting to compare the fit of three Milky Way dark-matter halo models.**

- Used Python to fit mentor-provided Milky Way kinematic data by least squares and compared NFW, Einasto, and Isothermal halo models using rotation-curve RMSE.

## Skills

- Scientific computing: Python data processing and visualization, curve fitting, and residual analysis; PyMC, Bayesian MCMC, and posterior and parameter-uncertainty analysis.
- Machine learning: learned and applied MLP classification, feature-group comparison, and exact Shapley attribution through the Higgs simulation project.
- Research writing: wrote the MaNGA manuscript; wrote LaTeX lab reports and technical documentation.
- Languages: native Chinese; pursuing an undergraduate degree taught in English at the University of Toronto.
