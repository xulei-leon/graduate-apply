# Research Background

Last updated: 2026-06-22

## Core Narrative

The applicant's research profile should be framed as computational physics, not as two unrelated subfields.

Unified theme:

> Using statistical inference, machine learning, and reproducible computational experiments to extract physical insight from complex data.

| Project | Field | Methods | Main signal |
|---|---|---|---|
| Dark matter halo concentration-mass relation | Astrophysics / cosmology | Bayesian inference, MCMC, PyMC 5, MaNGA data | Probabilistic modeling, uncertainty quantification, first-author manuscript potential |
| Jet foundation models / JetClass top tagging | High-energy physics / jet physics | ML for physics, PET / OmniLearn-style models, feature ablation, ROC AUC | Representation learning, controlled ML experiments, reproducible evaluation |

Stronger application framing:

> I have used computational and statistical methods to study complex physical systems across scales, from Bayesian inference of dark-matter halo structure to machine-learning models for particle jets.

Avoid the weaker framing:

> I have worked on astrophysics and particle physics.

## How the Projects Connect

The two projects are connected by method, not by physical object.

The dark matter project asks how astronomical data can constrain the dark-matter halo concentration-mass relation. Its strength is interpretable probabilistic inference: model assumptions, MCMC sampling, posterior uncertainty, and physical parameter interpretation.

The jet project asks how particle-level input representation affects PET / OmniLearn-style top-tagging models on JetClass. Its strength is controlled scientific ML: feature ablation, data efficiency, ROC AUC, background rejection, fixed splits, and reproducible experiment records.

Together, they show that the applicant can:

- translate physical questions into quantitative models;
- implement statistical and ML workflows in Python;
- evaluate models with uncertainty, metrics, and controlled comparisons;
- move across physical scales while keeping a consistent computational research focus.

## Second Project: Accurate Description

The second project should be described as:

> A computational particle-physics project studying how particle-level input representations affect PET / OmniLearn-style jet-tagging models on JetClass.

Research question:

> On JetClass binary top tagging, how does particle-level feature richness affect PET-style model performance and data efficiency when dataset, split, preprocessing, model protocol, and evaluation metrics are controlled?

Useful keywords:

- High-energy physics
- Jet physics
- JetClass
- Top tagging
- QCD background
- Particle-level representation
- PET / Particle Transformer
- OmniLearn
- Foundation models for particle physics
- Feature ablation
- Data efficiency
- ROC AUC
- Background rejection
- Reproducible experiment pipeline

Conservative contribution statements:

- Studied recent jet foundation models, including OmniJet-alpha and OmniLearn.
- Identified particle-level input representation as a key factor in downstream tagging performance.
- Designed a controlled JetClass top-tagging feature-ablation study.
- Prepared a JetClass data-quality workflow for HDF5 inspection, masks, labels, fixed split manifests, and reusable experiment records.
- Planned evaluation using ROC AUC, background rejection, seed repetitions, and structured run metadata.

Do not claim completed large-scale results unless experiment outputs exist.

## Master's Application Positioning

For master's applications, the goal is to show readiness for systematic training in computational physics, scientific ML, or data-driven physical science.

Main message:

> Through two computational physics projects, I have developed experience with Bayesian inference and ML for physics. I now want to strengthen my foundation in numerical methods, statistical modeling, machine learning, and research practice through a master's program.

Reusable SOP paragraph:

> My research experiences have led me toward computational physics rather than a single experimental or theoretical subfield. In my astrophysics project, I used Bayesian inference and MCMC methods to study the dark-matter halo concentration-mass relation from astronomical data. In my more recent particle-physics project, I have been studying foundation-model approaches for jet tagging, focusing on how particle-level input representations affect PET / OmniLearn-style models on JetClass. Although the two projects involve very different physical scales, they share the same structure: translating a physics question into a quantitative model, implementing the model computationally, testing its reliability, and interpreting the results in physical terms. A master's program would allow me to strengthen this foundation through advanced training in numerical methods, statistical modeling, machine learning, and computational physics research.

## PhD Application Positioning

For PhD applications, the narrative must be more research-focused and advisor-specific.

Main message:

> I want to develop and apply statistical and machine-learning methods for inference, representation learning, and prediction in data-intensive physical systems.

Reusable SOP paragraph:

> My research interests have developed around computational and data-driven approaches to physics. In my astrophysics project, I studied the dark-matter halo concentration-mass relation using Bayesian inference and MCMC methods, which trained me to formulate a physical question as a probabilistic model, quantify uncertainty, and interpret population-level parameters. My current particle-physics project has broadened this interest from inference to representation learning: I am studying how particle-level input features affect PET / OmniLearn-style jet-tagging models on JetClass, with emphasis on controlled ablations, data efficiency, and reproducible evaluation. Together, these experiences have shaped my goal of pursuing research in computational physics, especially methods that connect physical theory, numerical modeling, machine learning, and complex data.

Advisor-specific variations:

- Computational astrophysics: emphasize Bayesian inference, dark matter, galaxy dynamics, and simulation-observation comparison.
- ML for HEP: emphasize jet representation learning, foundation models, transfer learning, and data-efficient tagging.
- Scientific ML: emphasize reliable and interpretable models for complex physical systems.

## CV Language

Dark matter project:

- Built a Bayesian inference pipeline in Python/PyMC 5 to study the dark-matter halo concentration-mass relation using MaNGA galaxy data.
- Implemented MCMC-based posterior inference and uncertainty quantification for galaxy-level and population-level model parameters.
- Analyzed late-type disk galaxy kinematics and interpreted inferred halo parameters in the context of dark matter structure formation.
- Prepared a first-author manuscript for arXiv submission and subsequent journal submission.

Jet foundation model project:

- Investigated foundation-model approaches for jet physics, focusing on PET / OmniLearn-style models for JetClass top tagging.
- Designed a controlled feature-representation ablation study comparing nested particle-level inputs, including kinematics, PID, charge, and energy/momentum fractions.
- Prepared a JetClass preprocessing and data-audit workflow for HDF5 inspection, particle masks, label handling, fixed split manifests, and reproducible experiment records.
- Planned model evaluation using ROC AUC, background rejection at fixed signal efficiency, seed repetitions, and structured run metadata.

Research interests:

> Computational physics, Bayesian inference, machine learning for physics, uncertainty quantification, scientific machine learning, dark matter and galaxy dynamics, jet physics, and foundation models for particle physics.

## Interview Answer

If asked why the two projects are in different fields:

> They are different in physical context, but connected by methodology. In both projects I use computational models to connect data with physical interpretation. The dark-matter project trained me in Bayesian inference and uncertainty quantification, while the jet-physics project has trained me to think about machine-learning representation, controlled ablations, and reproducible evaluation. Together, they helped me realize that my main interest lies in computational methods for data-intensive physics rather than in only one physical system.

If asked about the role of ML in physics:

> I see ML as a modeling tool rather than a replacement for physics. In physical applications, predictive accuracy is not enough; the model also needs to be validated against physical expectations, tested for generalization, and evaluated under controlled protocols.

## Main Risk to Manage

The profile may look scattered if it is organized by field: astrophysics plus HEP. It becomes coherent when organized by method:

- Bayesian inference
- Machine learning for physics
- Uncertainty quantification
- Feature representation
- Reproducible scientific computing
- Interpretable physical modeling

Final short profile:

> Computational physics applicant with experience in Bayesian inference, MCMC, machine learning, feature ablation, and data-driven modeling across astrophysics and high-energy physics.

