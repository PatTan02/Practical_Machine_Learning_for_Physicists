# Practical_Machine_Learning_for_Physicists — Mini Project

A compact, end-to-end set of notebooks exploring binary and multi-class classification, with an emphasis on rigorous evaluation, precision-focused tuning, and reproducible pipelines.

---


### Binary Classification
**Notebook:** [Binary_Classification_precision_trial.ipynb](Binary_Classification_precision_trial.ipynb)  
- Framed a binary classification task and created **stratified** train/validation/test splits.
- Performed quick EDA (class balance, feature summaries, correlation checks).
- Built **scikit-learn pipelines** for preprocessing (imputation, scaling/encoding) and modelling.
- Trained and compared several baseline and stronger classifiers (linear and tree-based).
- **Optimised for precision**: class weighting, decision-threshold tuning from the **precision–recall curve**, and PR-AUC reporting.
- Reported metrics (precision, recall, F1, confusion matrix) and plotted **ROC**/**PR** curves.

---
### Ternary Classification
**Notebook:** [Ternary_Mini_project_trial2.ipynb](Ternary_Mini_project_trial2.ipynb)  
- Extended the task to **three classes**; encoded labels and addressed imbalance.
- Trained multi-class versions of the models (OvR/OvO where appropriate) within pipelines.
- Evaluated with **macro-averaged** precision/recall/F1, per-class reports, and a **3×3 confusion matrix**.
- Used cross-validation and **learning curves** to diagnose bias–variance behaviour.

---
### Pixel-wise Classification
**Notebook:** [Mini_project_extension_trial3.ipynb](Mini_project_extension_trial3.ipynb)  
- Added **feature engineering**/selection experiments and ablation checks.
- Ran systematic **hyperparameter search** (Grid/Randomised CV) over full pipelines.
- Explored **probability calibration** and custom **threshold selection** based on task costs.
- Interpreted models with **feature/permutation importance** and brief error analysis.
- Finalised a pipeline for inference and demonstrated predictions on held-out data.
