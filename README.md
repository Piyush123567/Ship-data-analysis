# Ship Risk Prediction

## Project Overview
This project predicts the **risk level of ships** based on features like `dwt` (deadweight), `gt` (gross tonnage), and `built_year`. The goal is to help shipping companies identify **high-risk ships** for better safety and maintenance planning using machine learning.

---

## Problem Statement
- Manual ship risk assessment is **time-consuming**.
- We aim to **automate risk prediction** using historical ship data.
- This helps reduce **accidents and operational issues**.

---

## Key Insights
- Logistic Regression achieved **80% test accuracy**.
- Tree-based models (Decision Tree, Random Forest, Gradient Boost, AdaBoost) show **overfitting**.
- Important features: `dwt`, `gt`, `built_year`.
- Categorical features like `company_name` and `ship_name` were removed due to high uniqueness.

---

## Tools & Libraries
- Python 3
- Pandas, NumPy
- Scikit-learn: Logistic Regression, Decision Tree, Random Forest, Gradient Boost, AdaBoost
- StandardScaler for numeric feature scaling

---

## Metrics (Logistic Regression)
| Dataset | Accuracy | F1 Score | Precision | Recall | ROC-AUC |
|---------|---------|---------|-----------|--------|---------|
| Train   | 0.8733  | 0.8744  | 0.9383    | 0.8444 | 0.8806  |
| Test    | 0.8000  | 0.8000  | 0.8000    | 0.8000 | 0.8000  |

---

## Future Improvements
- Add more ship data for better generalization.
- Tune tree-based models to reduce overfitting.
- Include more features like ship type, age, or route.
- Use cross-validation to improve performance evaluation.

