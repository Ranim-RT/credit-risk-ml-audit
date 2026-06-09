## Credit Risk ML Audit

### Description
Audit of a Random Forest model trained to predict bank loan 
approvals on the German Credit Risk dataset (Kaggle).
Includes model explainability and gender fairness analysis.

### Dataset
German Credit Risk — Kaggle

### Tools
Python · Scikit-learn · SHAP · LIME · Pandas · Matplotlib

### What I did
- Trained a Random Forest classifier to predict loan approvals
- Used SHAP for global feature importance analysis
- Used LIME to explain individual predictions
- Conducted a gender fairness audit
- Verified compliance with EU AI Act requirements

### Key Results
- Top features driving refusals: credit amount and duration
- Gender acceptance rate: Men 71% / Women 68%
- Model is not significantly discriminatory
