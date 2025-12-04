# Call Fraud Detection (Telecom)
Simple offline ML project to detect fraudulent telecom accounts.

## What it does
- Data cleaning & feature engineering
- Handles class imbalance (SMOTE)
- Trains RandomForest & XGBoost
- Evaluates using precision/recall/F1 & PR-AUC
- Saves best model and scaler for offline scoring

## How to run
1. Open notebook.ipynb in Google Colab.
2. Upload `CDR-Call-Details.csv` to /mnt/data or adjust path.
3. Run cells top-to-bottom.
4. Artifacts saved at /mnt/data/call_fraud_project_artifacts/
