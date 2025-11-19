# Credit Risk Prediction with SHAP

## 1. Objective
Build an interpretable ML model to predict credit risk using SHAP.

## 2. Dataset
German Credit Data with 1000 samples and 20 features.

## 3. Model
Used XGBoost classifier with 80/20 train-test split.

### Evaluation Metrics:
- AUC: 0.61
- F1 Score: 0.81

## 4. Global Interpretability
SHAP bar plot shows 'Duration', 'Credit Amount', and 'Age' are most influential features.

## 5. Local Interpretability
SHAP force plots reveal how individual features push predictions toward high or low risk.

## 6. SHAP vs Permutation
Permutation importance confirms SHAP’s top features. SHAP provides more consistent and interpretable results.

## 7. SHAP Sensitivity
Changing 'Duration' from 48 to 24 months reduced predicted risk from 0.66 to 0.42.

## 8. Conclusion
SHAP enables transparent credit risk decisions. The model is accurate and interpretable.
