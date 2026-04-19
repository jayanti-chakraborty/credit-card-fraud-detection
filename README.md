# credit-card-fraud-detection
Credit Card Fraud Detection using XGBoost, SMOTE and SHAP explainability on 284k real transactions — achieved 97.6% AUC score
## Tech Stack
- Python
- XGBoost
- SMOTE (imbalanced-learn)
- SHAP
- Scikit-learn
- Matplotlib / Seaborn
  ## Approach
1. EDA - Analyzed fraud vs normal transaction distribution
2. Preprocessing - StandardScaler for feature scaling
3. SMOTE - Handled imbalanced dataset by generating synthetic fraud samples
4. XGBoost - Trained gradient boosting model for classification
5. SHAP - Explainability analysis to identify top fraud indicators
