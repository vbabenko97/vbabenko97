# Vitalii Babenko

Clinical machine learning & medical imaging (PhD) · production GenAI systems · validation methodology for models that must hold up in the clinic.

I am a Vienna-based PhD in Computer Science (2025) working on trustworthy clinical machine learning for medical image analysis across ultrasound, CT, and MRI. My focus is the validation methodology that decides whether a model holds up beyond curated benchmarks — leakage-aware and patient-grouped cross-validation, patient-level aggregation, calibration, and robustness under acquisition and cohort shift. My doctoral work developed hierarchical ensemble classifiers for multi-class pathology diagnosis, with clinical evaluation in liver fibrosis staging and applied work in cardiac imaging and physiological-signal analysis for stress and cognitive workload. In parallel, I build production GenAI backend systems in industry. I am open to postdoctoral and research collaborations in Vienna and Europe at the intersection of clinical ML, medical imaging, and trustworthy AI.

## Current focus

- **Medical imaging / clinical ML** — robust, reproducible evaluation of clinical models (radiomics, texture analysis, ensemble methods) across ultrasound, CT, and MRI.
- **Production GenAI systems** — event-driven inference backends (FastAPI, AWS), provider-resilient integration, and drift monitoring; reliability and deployment constraints for ML in production.
- **Physiological-signal research** — stress and cognitive-workload classification from HR/BP/HRV signals, within the NATO SPS "Real-Time Stress Monitoring" project with the University of Calgary.

## Selected repositories

- **[clinval-validator](https://github.com/vbabenko97/clinval-validator)** — a validation-risk auditor for clinical-AI performance claims: it flags patient-level leakage, weak evaluation splits, and subgroup degradation in a model's `predictions.csv`, then renders a reviewer-style Validation Risk Report. Deterministic Python computes every metric; Claude only explains the risk. *(Python)*
- **[repro-survival-model-evaluation](https://github.com/vbabenko97/repro-survival-model-evaluation)** — an agent-driven, CPU-only reproduction of the ICML 2026 paper *When Can We Trust Survival Model Evaluation?* on real METABRIC data at reduced scale (one dataset, four classical CPU models): Claim 1 reproduced, Claim 2 graded `partial` in the repository, which also records the challenge's differing automated `verified` verdict (quality `medium`) and the limitations. [Live logbook (Trackio Space)](https://huggingface.co/spaces/vbabenko97/repro-when-can-we-trust-survival-model-evaluation). *(Python)*
- **[repro-instance-level-costs](https://github.com/vbabenko97/repro-instance-level-costs)** — an agent-driven reproduction of the ICML 2026 paper *Instance-Level Costs for Nuanced Classifier Evaluation* on its publicly obtainable datasets: the headline result reproduces on real Jigsaw data (error rate 2.92x the cost-weighted NEC metric; paper ~3x), cost-weighted training only partially, and the fine-tuned-model results were not reproduced (no GPU). The challenge's automated judge graded the NEC claim `verified` and the cost-weighting claim `inconclusive` (quality `high`). [Live logbook (Trackio Space)](https://huggingface.co/spaces/vbabenko97/repro-instance-level-costs). *(Python)*
- **[RFOCT](https://github.com/vbabenko97/RFOCT)** — Random Forest of Optimal-Complexity Trees, a custom tree ensemble for classification: the research/reference implementation of the algorithm published in *Cybernetics and Systems Analysis* (2023) for classifying pathologies on medical images. *(Python)*
- **[GeneticRace](https://github.com/vbabenko97/GeneticRace)** — a JavaFX desktop decision-support prototype from my Bachelor's thesis: optimizing treatment strategies for congenital heart defects by combining GMDH classifiers, the Analytic Hierarchy Process (AHP), and a genetic algorithm. *(Java)*

<!-- Add LiverRight (liver-fibrosis-from-ultrasound radiomics app) here once the clean public version is published. -->

## Research

PhD in Computer Science (2025), Igor Sikorsky Kyiv Polytechnic Institute — dissertation on hierarchical classification for pathology diagnosis from medical images of different modalities.

29 publications (Scopus citations: 30, h-index: 3, as of July 2026), including 7 Scopus-indexed journal articles and 8 Scopus-indexed conference papers (IEEE, Springer), among them a first-author methodology paper in *Cybernetics and Systems Analysis* (Springer).

→ [Scopus](https://www.scopus.com/authid/detail.uri?authorId=57221875186) · [ORCID](https://orcid.org/0000-0002-8433-3878) · [Google Scholar](https://scholar.google.com/citations?user=m5NgeD8AAAAJ&hl=en)

## Tech

- **Languages:** Python, SQL, Java, C++
- **ML / DL:** scikit-learn, PyTorch, XGBoost, LightGBM, TensorFlow
- **Medical imaging & validation:** radiomics & texture analysis (GLCM, GLRLM), ROI- and patient-level aggregation, leakage-aware nested/grouped CV, calibration (Brier, ECE), OpenCV, ultrasound/CT/MRI preprocessing
- **Backend / data:** FastAPI, AsyncIO, Pydantic, Jinja2, pandas, NumPy, SciPy
- **Cloud / infra:** AWS (S3, SQS, Lambda, Glue, SageMaker), Docker

## Contact

Vienna, Austria · [vbabenko2191@gmail.com](mailto:vbabenko2191@gmail.com) · [LinkedIn](https://www.linkedin.com/in/vbabenk) · [Scopus](https://www.scopus.com/authid/detail.uri?authorId=57221875186) · [ORCID](https://orcid.org/0000-0002-8433-3878) · [Google Scholar](https://scholar.google.com/citations?user=m5NgeD8AAAAJ&hl=en)
