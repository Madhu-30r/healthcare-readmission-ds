## Hospital Readmission Prediction - Diabetic Patients

### Business Problem
Predicting 30-day hospital readmission for diabetic patients to enable 
care managers to proactively intervene with high-risk patients.

### Approach
- EDA on 100,244 patient records
- Data cleaning and feature engineering
- Logistic regression baseline (numeric features only)
- Feature encoding (age, medications, lab results)
- Full logistic regression with encoded categorical features

### Results
| Model | Recall | ROC-AUC |
|---|---|---|
| Baseline (7 features) | 0.463 | 0.629 |
| Full model (encoded) | 0.516 | 0.639 |

### Next Steps
- Tree-based models (Random Forest, XGBoost) to improve AUC above 0.70
- Hyperparameter tuning
- SHAP values for model interpretability
