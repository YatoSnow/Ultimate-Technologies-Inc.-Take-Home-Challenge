# User Retention Prediction – Ultimate Technologies Case Study

## Project Overview
This project focuses on predicting whether a user will remain active in their **6th month** on the Ultimate Technologies platform. The goal is to identify key behavioral and demographic drivers of long-term retention and provide actionable insights to improve user engagement.

This work was completed as part of a take-home data science challenge, following an end-to-end applied machine learning workflow.

---

## Problem Statement
Ultimate Technologies aims to improve long-term rider retention. The task is to build a predictive model that determines whether a user will be active in their 6th month on the platform, and to interpret which factors most influence retention.

---

## Data Description
The dataset contains user-level behavioral and demographic features, including:
- Usage patterns
- Signup and activity information
- Demographic attributes
- Binary target variable indicating 6th-month activity

The dataset required cleaning, feature selection, and handling of imbalanced classes.

---

## Methodology
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature engineering
3. Train-test split
4. Baseline model development
5. Supervised classification modeling
6. Model evaluation and comparison
7. Business interpretation of results

---

## Modeling Approach
The following models were evaluated:
- Logistic Regression (baseline)
- Tree-based models (Random Forest)

Model performance was assessed using:
- Accuracy
- ROC-AUC
- Precision / Recall
- F1-score

---

## Results
- Best-performing model achieved:
  - **Accuracy:** ~0.72
  - **ROC-AUC:** ~0.75
- The model significantly outperformed baseline classifiers
- Tree-based models captured nonlinear relationships in user behavior more effectively

---

## Key Insights
- User activity patterns were stronger predictors of retention than demographic features
- Early engagement signals strongly correlated with 6th-month activity
- Retention can be improved by targeting users with low early engagement

---

## Limitations
- Limited feature set restricted deeper behavioral insights
- Class imbalance impacted recall for inactive users
- No temporal modeling of user behavior was applied

---

## Next Steps
- Incorporate time-series user activity data
- Apply gradient boosting models (XGBoost / LightGBM)
- Perform hyperparameter optimization
- Develop a retention-focused intervention strategy

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
