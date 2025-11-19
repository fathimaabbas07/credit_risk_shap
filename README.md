# Credit Risk Prediction with SHAP

## Overview
This project uses XGBoost and SHAP to predict and interpret credit risk from German Credit Data.

## Tools Used
- Python
- XGBoost
- SHAP
- Scikit-learn
- Matplotlib

## Files
- `credit_risk_data.csv`: Dataset
- `model.py`: Model training and evaluation
- `shap_analysis.py`: SHAP plots and sensitivity
- `report.md`: Project report
- `README.md`: Project overview

## Results
- AUC: 0.61
- F1 Score: 0.81
- SHAP shows 'Duration' and 'Credit Amount' are key drivers of risk

## How to Run
Upload dataset and run `model.py` in Colab or local Python environment.

## Optional Deployment
You can deploy using Streamlit or Flask (not required for submission).
