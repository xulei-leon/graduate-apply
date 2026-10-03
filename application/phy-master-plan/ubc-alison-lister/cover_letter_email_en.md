Subject: Fall 2027 Physics MSc inquiry — ML evaluation and likelihood inference

Dear Professor Lister,

I am a Physics Specialist undergraduate at the University of Toronto, expecting to graduate in June 2027 and interested in UBC’s Master of Science in Physics for Fall 2027. The ATLAS [weakly supervised dijet anomaly-detection paper](https://arxiv.org/abs/2502.09770), which lists you as a co-author, connects with my interest in statistical validation: classifier-based selections feed into pyhf profile-likelihood fits, with separate checks of background-related biases. I would like to understand how uncertainties in learned selections affect subsequent inference.

Since May 2026, I have worked under Professor Mario Campanelli at UCL on simulated H → ZZ* → 2e2μ events. I processed public ATLAS simulated signal and background samples, grouped 19 kinematic variables into four sets, split data by physical event group, and compared all 15 nonempty feature-group combinations with MLP classifiers across five random seeds. I built a common pyhf profile-likelihood workflow, compared nominal 68% signal-strength interval widths and used exact Shapley attribution to assess each group's contribution. I then conducted 200 event-group bootstrap replicates and conditional coverage diagnostics to examine finite-sample uncertainty and interval calibration. The results remain exploratory, and a first-author manuscript is in progress. Code: https://github.com/hyi03/HiggsML.

Previously, I completed a MaNGA dark-matter halo project independently, using PyMC, MCMC and population inference for 620 selected disk galaxies. I wrote a first-author manuscript, now complete but not submitted; a preview is available at https://hyi03.github.io/manga-dm/paper-preview.

If relevant to an MSc project in your group, I would be interested in a small simulation study testing how classifier selection and background mismodelling affect a profile-likelihood result. I would need to learn the relevant ATLAS analysis and detector context. Are you considering MSc students for Fall 2027?

I can provide my CV and further research details. Thank you for your time.

Best regards,
Hongyi Xu
University of Toronto
hyi.xu@mail.utoronto.ca
