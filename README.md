# Selected Machine Learning and Scientific Projects

My work combines 20+ years of experimental physics research 
(PhD from the University of Bonn, research at the University of Mainz and George Washington University, 
70+ peer-reviewed publications, Carl Zeiss Fellowship, scientific leadership and management roles) 
with modern machine learning across entity resolution, medical imaging, computational biology, and production data science. 
The common thread: systematic experimental methodology and solution of non-trivial tasks applied to complex, noisy, 
real-world data.

[Machine Learning Projects](#machine-learning-projects) ·
[Selected Scientific Projects](#selected-scientific-projects) ·
[Research Profiles](#research-profiles)

---

## Machine Learning Projects

### Medical AI

#### AMIA 2026 – Medical Image Analysis Challenge (3rd Place, June 2026)

Development of a solution for multi-class chest X-ray abnormality detection, 
achieving 3rd place on the private leaderboard among 200+ participants.

The project systematically investigates detector complementarity 
across architectures (RT-DETR, DINO), optimization strategies 
(ADAM, MuSGD), and cross-validation folds. The central finding 
is that selective evidence fusion, using independent detectors 
as supporting evidence rather than fusing all predictions,
consistently outperforms naive ensembling.

**Main topics:**
- Object detection with transformer-based architectures 
  (RT-DETR, DINO)
- Detector complementarity and confidence-based reranking
- Cross-fold consensus and donor selection
- VLM experiments for annotation refinement (MedGemma, Qwen)
- Distribution shift analysis and validation-to-leaderboard 
  transfer

**Outcome:** 3rd place (private leaderboard). 
Comprehensive technical writeup published.

**Links:**
- [Technical writeup](https://vsokhoyan.github.io/ChestXRay_Multiclass_Detection/)

---

### Computational Biology
#### CAFA-6 – Protein Function Prediction (March 2026)

Development of transformer-based methods for automatic protein 
function annotation using ProtT5-XL and ESM2 foundation models, 
including end-to-end fine-tuning and systematic benchmarking 
against fixed-embedding baselines.

A key methodological contribution is an information accretion-aware ensemble 
aggregation strategy, which uses different 
aggregation schemes for ontology regions depending on label 
specificity, addressing the challenge of rare-label signal 
preservation in hierarchical multi-label prediction.

**Main topics:**
- End-to-end transformer fine-tuning (ProtT5-XL 3B, ESM2)
- Fixed embedding baselines vs fine-tuned models
- Rare-label training dynamics and label-frequency analysis
- Information-accretion-aware ensemble aggregation
- GO-DAG propagation and ontology-consistent postprocessing
- Reference-guided prediction refinement

**Outcome:** Detailed methodological report published. 
Work in progress toward a scientific publication.

**Links:**
- [Technical writeup](https://vsokhoyan.github.io/CAFA6-ML/)

---

### Applied Machine Learning

#### Entity Resolution and Fraud Detection

Development of production machine learning methods for 
large-scale entity resolution within the German Financial 
Administration, including methods for distinguishing genuine 
entity matches from typographical variations and OCR-distorted 
name pairs. The developed methods combine neural similarity learning, 
graph-based clustering, and classical machine learning to improve identity 
resolution under realistic administrative data quality conditions.

**Main topics:**
- Siamese neural networks for pairwise similarity
- Transformer-based and BERT embedding approaches
- Graph-based entity resolution
- Handling of real-world data quality issues (typos, OCR 
  distortions, formatting inconsistencies)

**Outcome:** Production deployment in operational systems 
serving the German Financial Administration. 

---

#### ML for Identification of Correlated Events in Nuclear Physics Experiments

Development of a machine learning method for identifying 
correlated events in tagged-photon nuclear physics experiments. 
The method improves event matching and measurement accuracy 
under realistic experimental conditions with overlapping 
background.

This project directly bridges experimental physics and modern 
ML: the challenge of extracting weak correlated signals from 
large noisy datasets is common to both domains.

**Outcome:** Published in the Journal of Instrumentation (JINST).

**Links:**
- Publication: V. Sokhoyan, E. Mornacchi, “A new Machine Learning-based method for identification of time-correlated events at tagged photon facilities”,
  Journal of Instrumentation 18, P10007 (2023), [Read on arXiv](https://arxiv.org/abs/2307.04776)

---

### Foundation Models and Scientific AI: RNA, LLMs, and Biological Sequences

Evaluation and application of modern foundation models to 
scientific prediction tasks, including biological sequence 
analysis and scientific LLM benchmarking.

**Projects include:**
- RNA structure prediction (Stanford RNA 3D Folding Part 2 at Kaggle, top 27%). 
- MedGemma and Qwen fine-tuning for medical imaging tasks.
- Nemotron scientific LLM evaluation and benchmarking.

**Outcome:** Practical experience with fine-tuning and 
applying large foundation models across biological, medical, 
and scientific domains.

**Links:**

- [Kaggle Competitions](https://www.kaggle.com/vahesokhoyan/competitions)

---

## Selected Scientific Projects

### Polarization Observables in Meson Photoproduction (PhD)

First measurement of polarization observables Is and Ic in double pion photoproduction with the 
CBELSA/TAPS experiment at ELSA accelerator in Bonn (University of Bonn, 2006–2012).

**Main contributions:**
- Large scale data analysis
- Monte Carlo simulations of complex detection apparatus and physical processes
- Preparation of particle detectors
- Multiple first-author publications

**Outcome:** One of the publications (Eur.Phys.J. A51 (2015) no.8, 95 (2015)) selected by the Particle Data 
Group (PDG) as the primary reference for properties of multiple baryon resonances and their properties.

**Links:**
- V. Sokhoyan, E. Gutz, H. van Pee et al., “Data on Is and Ic in γp → pπ⁰π⁰ reveal cascade decays of N(1900) via N(1520)pi”, Phys. Lett. B746 (2015) 127-131 (2015), [Read open access at PLB](https://www.sciencedirect.com/science/article/pii/S0370269315003299?via%3Dihub).
- V. Sokhoyan, E. Gutz, V. Crede, H. van Pee et al., “High-statistics study of the reaction γp → p2π⁰“, Eur. Phys. J. A51 (2015) no.8, 95 (2015), [Read on arxiv](https://arxiv.org/abs/1507.02488).
- A. Thiel, V. Sokhoyan, E. Gutz, H. van Pee et al., “Three-body nature of N and Delta resonances from sequential decay chains”, Phys. Rev. Lett. 114 no. 9, 091803 (2015), [Read on arxiv](https://arxiv.org/abs/1501.02094).

---

### Proton Scalar Polarizabilities (GWU)

First measurement of proton scalar polarizabilities 
using beam asymmetry below the pion-production threshold 
(George Washington University and University of Mainz, 2012–2014).

**Main contributions:**
- Full experimental analysis and physical interpretation
- Proposal development and successful defense at Program 
  Advisory Committee
- First-author publication

**Outcome:** Published as first author in the European 
Physical Journal A, providing a new experimental reference 
for nucleon scalar polarizabilities. 

**Link:**
- Publication: V. Sokhoyan, E.J. Downie, E. Mornacchi, J.A. McGovern, N. Krupina et al., “Determination of the scalar polarizabilities of the proton using beam asymmetry Σ3 in Compton scattering”, Eur.Phys.J. A53 (2017) no.1, 14 (2017), [Read on arXiv](https://arxiv.org/abs/1611.03769).

---

### Carl Zeiss Research Fellowship (Project Leader)

Independent research project investigating in-medium 
modifications of baryon resonances using circularly polarized 
photon beams (University of Mainz, 2015–2016).

This project required extraction of weak resonance signals 
from large, noisy nuclear datasets — the same core challenge 
underlying all subsequent machine learning work across medical 
imaging and computational biology.

**Main contributions:**
- Proposed the idea of using circularly polarized photons to investigate in-medium modifications of baryon resonances on heavy targets.
- Competitive fellowship proposal (€200k awarded by Carl-Zeiss-Stiftung)
- Independent project leadership
- Student and postdoc supervision
- Experimental campaign coordination at MAMI
- Data analysis and publication

**Outcome:** First-author publications in Physics Letters B 
and Physical Review C.

- V. Sokhoyan, S. Prakhov, A. Fix et al., “Measurement of the beam-helicity asymmetry in photoproduction of π⁰η pairs on carbon, aluminum, and lead“, Phys. Lett. B 802, 135243 (2020), [Read on arxiv](https://arxiv.org/abs/1907.00232).
- V. Sokhoyan, S. Prakhov, A. Fix et al., “Study of the γp → π⁰ηp reaction with the A2 setup at MAMI”, Phys. Rev. C 97, 055212 (2018), [Read on arxiv](https://arxiv.org/abs/1803.00727).

---

### Active Target TPC Development (PRES / A2 Collaboration)

Experimental programs with integration of active time-projection 
chambers for precision proton-radius and polarizability measurements 
(University of Mainz, 2017–2023).

**Main contributions:**
- Hardware coordination and interim spokesperson 
  (PRES Collaboration on the German side at the University of Mainz)
- Monte Carlo (GEANT4) detector simulations for TPC integration with Crystal Ball calorimeter
- Design, coordination and execution of multiple experimental campaigns

---

### Scientific Leadership within the A2 Collaboration

Scientific referee for the majority of publications of the 
A2 Collaboration at MAMI (2018–2023). Responsibilities 
included systematic review of experimental analyses, 
publication quality assurance, and coordination of large
scale experiment.

The systematic quality-assessment methodology developed in 
this role, evaluating consistency, reproducibility, and 
error propagation across large datasets, directly connects with 
current approaches to ML model evaluation and validation.

---

# Research Profiles

- [Google Scholar – Publications & Citations](https://scholar.google.com/citations?user=7leLPVMAAAAJ&hl=de)
- [Scopus Author Profile (h-index: 26)](https://www.scopus.com/authid/detail.uri?authorId=23989342800)
- [Kaggle Competitions Profile](https://www.kaggle.com/vahesokhoyan)
