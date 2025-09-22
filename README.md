# 🌳 Interpretable Trees and Regularized Regression

This project explores **decision trees, interpretable rule extraction, and regularized regression techniques** 
on two UCI datasets:  
- **Acute Inflammations dataset** (multi-label classification)  
- **Communities and Crime dataset** (socio-economic predictors of crime rates)  

It also includes experiments with **boosting (XGBoost)** and feature selection.  

---

## ✨ Features
- **Decision Trees (Acute Inflammations)**  
  - Visualized full tree structures  
  - Converted splits into **if–then rules**  
  - Applied **cost-complexity pruning** for interpretable models  

- **Communities & Crime (Regression)**  
  - Imputed missing values  
  - Exploratory analysis: correlation matrix, coefficient of variation  
  - Compared models:  
    - Ordinary Least Squares (baseline)  
    - Ridge regression (CV-tuned λ)  
    - LASSO (CV-tuned λ; variable selection)  
    - Principal Component Regression (PCR)  
    - XGBoost with L1-penalized logistic regression at nodes  

- **Evaluation Metrics**  
  - Classification: confusion matrices, interpretability of extracted rules  
  - Regression: Train/Test MSE, feature importance from LASSO/XGBoost  
