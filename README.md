# Hi, I'm Arnav Kumar

**Medical Sciences & Engineering undergrad at IIT Madras.** I build machine learning for clinical imaging, biosignals and physiology, and the evaluation tooling that checks whether a medical model actually holds up.

- Working on quantitative coronary angiography: frame counts, dye velocity and stenosis from routine cine runs
- Interested in medical imaging, physiological modelling, RL for treatment scheduling, and honest model evaluation
- Currently implementing a transformer from scratch to understand attention properly
- Open to AI / ML internships &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/arnav-kumar-6198aa313)

## Featured work

| Project | What it does | Built with |
|---|---|---|
| [**TIMI Flow Grading**](https://github.com/A-b29/TIMI-Flow-Grading) | Semi-automated corrected TIMI frame count, dye-velocity profiling and three stenosis measures from DICOM coronary angiograms. UI-free engine with 126 tests, Docker and CI. | Python · OpenCV · pydicom · SciPy |
| [**RSNA Knee Abnormality Detection**](https://github.com/A-b29/RSNA-Knee-Competition) | Kaggle solo entry: 12 knee-MRI findings from weak report labels using 2.5D attention-MIL ConvNeXt models and teacher-student label denoising. 0.956 macro AUC on the public leaderboard, top 17% (1,088 of 6,425 teams). | PyTorch · ConvNeXt · Kaggle T4 |
| [**What should adaptive therapy optimise?**](https://github.com/A-b29/RL-Adaptive-Therapy-in-Cancer) | Four published RL reward objectives for adaptive cancer therapy ported into one Lotka-Volterra environment, with PPO agents scored against the value-iteration optimum on every objective. | PyTorch · PPO · value iteration |
| [**Clinova**](https://github.com/A-b29/Clinova---An-Evidence-Grounded-Clinical-Intelligence-Prior-Authorization-Platform) | Prior-authorization copilot that ties every extracted clinical fact to its source sentence, retrieves the matching policy text and marks each criterion `SUPPORTED`, `NOT_FOUND` or `CONFLICTING` for a human reviewer. | RAG · sentence-transformers · Pydantic · Streamlit |
| [**HFpEF Therapeutics & Aortic Haemodynamics**](https://github.com/A-b29/HFpEF-Therapeutics-and-Aortic-Haemodynamics) | Coupled left-ventricle and transmission-line aorta model of heart failure with preserved ejection fraction, used to test an aortic compliance-gradient therapy. | SciPy · stiff ODEs · VTK export |
| [**TaskPilot**](https://github.com/A-b29/TaskPilot) | To-do app you run by chatting: an LLM tool-calling agent adds, updates and assigns tasks in Postgres. [Live demo](https://task-pilot-xi.vercel.app). | FastAPI · React · Postgres |

## More projects

**Biomedical modelling and signals**

- [PK/PD Simulator](https://github.com/A-b29/PKPD-Simulator): interactive pharmacokinetics and pharmacodynamics teaching tool with multi-compartment models and a 40-drug library (FastAPI + Next.js)
- [ECG Signal Quality Classifier](https://github.com/A-b29/ecg-quality-classifier): 38k-parameter 1D CNN that screens 12-lead ECGs as clean, noisy or artifact-contaminated
- [Cas9 activity prediction](https://github.com/A-b29/Predicting-Gene): ESM-2 and supervised baselines on a SpCas9 deep mutational scan, with position- and domain-held-out splits
- [Pulsatile Pump Modelling](https://github.com/A-b29/Pulsatile-Pump-Modelling): cardiac-cycle flow simulation with wall shear stress and PV loops

**Medical AI evaluation tools**

- [Selective Diagnosis Simulator](https://github.com/A-b29/Selective-Diagnosis-Simulator): coverage vs. selective risk when a classifier can abstain and refer
- [Model Forensics Workbench](https://github.com/A-b29/Forensics-Workbench-A-model-): subgroup error analysis with Wilson intervals and small-cohort guards
- [Counterfactual Medical Imaging Lab](https://github.com/A-b29/Counterfactual-Medical-Imaging): prediction drift under controlled image perturbations
- [Medical AI Crash-Test Simulator](https://github.com/A-b29/Medical-AI-Crash-Test-Simulator): seeded stress tests for a tabular classifier
- [Experiment Autopsy Agent](https://github.com/A-b29/Autopsy-Agent-Experiment-): static auditor that flags data leakage and missing seeds in ML repos
- [Anatomy-as-Data](https://github.com/A-b29/Anatomy-as-Data): reproducible geometry measurements from 3D segmentations

## Toolbox

**ML and imaging:** Python, PyTorch, scikit-learn, OpenCV, pydicom, NumPy, SciPy  
**Apps and infra:** FastAPI, React, Next.js, Streamlit, PostgreSQL, Docker, GitHub Actions
