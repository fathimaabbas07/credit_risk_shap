#  Interpretable Machine Learning: SHAP Value Analysis for Credit Risk Prediction

This project predicts **credit default risk** and explains model decisions using **SHAP** for transparency in financial contexts.

##  Repository structure
- data/credit_risk.csv
- notebooks/credit_risk_shap.ipynb
- visuals/global_shap.png, shap_force_high.png, shap_force_low.png, shap_force_borderline.png, permutation_importance.png, roc_curve.png, confusion_matrix.png
- report.pdf
- requirements.txt
- README.md

##  What’s included
- **Model:** Random Forest with class imbalance handling
- **Metrics:** AUC, F1, Precision, Recall
- **Interpretability:** SHAP global + 3 local plots (high-risk, low-risk, borderline)
- **Comparison:** SHAP vs Permutation Importance
- **Sensitivity:** Perturbation of top features
- **Report:** Detailed credit risk analysis and recommendations

##  Results (replace with your actual numbers)
| Metric    | Value |
|-----------|-------|
| AUC       | 0.84  |
| F1        | 0.71  |
| Precision | 0.73  |
| Recall    | 0.69  |

##  Key insights
- **Top drivers:** [feature_1], [feature_2], [feature_3] strongly influence default risk.
- **Local explanations:** High-risk case driven by [X]; low-risk case stabilized by [Y]; borderline shows mixed contributions.
- **Comparison:** SHAP ranks [feature_1] highest, permutation importance confirms/contrasts [feature_2] impact.
- **Sensitivity:** +1 std change in [feature_1] increases default probability by ~[Δ]; actionable for risk policy.

##  Run locally
```bash
pip install -r requirements.txt
jupyter notebook notebooks/credit_risk_shap.ipynb
