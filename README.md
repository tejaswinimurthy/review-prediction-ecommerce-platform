# Review Prediction for Targeted Customer Incentives

📄 **Full case study:**  
[Review Prediction for Targeted Customer Incentives](./review_prediction_exploration.md)

---

## Context
This project is based on an academic, consulting-style assignment completed as part of the MSc Business Analytics programme at Warwick Business School.

The task was framed as a real-world business pitch for a large eCommerce platform, with the objective of developing a predictive model to identify customers most likely to leave positive reviews, enabling more efficient and targeted incentive strategies.

---

## Business Problem
Online retail platforms rely heavily on positive customer reviews, but incentivising every customer is costly and inefficient.

The objective was to:
- Predict which customers are most likely to leave positive reviews
- Enable targeted incentives rather than blanket campaigns
- Select a predictive model based on **business usefulness**, not raw accuracy alone

---

## Approach (High Level)
- Joined and prepared multiple relational datasets representing orders, customers, products, sellers, and reviews
- Engineered behavioural and transactional features at the order level
- Trained and evaluated multiple classification models
- Focused evaluation on precision, recall, and the cost of incorrect targeting

---

## Model Selection & Outcome
Multiple classification models were evaluated, including logistic regression, random forest, and **gradient boosted decision trees (GBDT)**.

**GBDT delivered the strongest overall performance** and was selected as the final model, particularly due to its favourable precision–recall trade-off aligned with the business objective of targeted incentives.

The analysis demonstrated that predictive modelling can meaningfully support more efficient review-incentive strategies while maintaining review quality.

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebooks

---

## Notes
This repository contains a portfolio-safe adaptation of the original academic work. All data used here is synthetic or anonymised, and the focus is on methodology, decision framing, and evaluation logic rather than proprietary data.
