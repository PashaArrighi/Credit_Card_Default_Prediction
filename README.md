# Credit_Card_Default_Prediction

A machine learning project to predict which credit card clients are likely to default, completed for **BUSA8001 – Applied Predictive Analytics** at Macquarie University.

## Overview
Using a dataset of **30,000 clients**, the project builds predictive models to improve credit risk assessment. Features include demographics, credit limits, payment history, and bill amounts, with the target variable `default.payment.next.month` (1 = Default, 0 = No Default).

## Workflow
- **Data Preprocessing** – Cleaning, encoding, and scaling.
- **EDA** – Distribution analysis, correlations, and key predictor identification.
- **Modeling** – Logistic Regression, Decision Trees, Random Forest.
- **Evaluation** – Accuracy, Precision, Recall, AUC.
- **Selection** – Best model chosen based on balanced performance.

## Tools
Python (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`) in Jupyter Notebook.

## Key Insight
Past payment behaviour is the strongest indicator of default, followed by credit limit and education level.

---
**Author**: Muhammad Pasha Arrighi Effendi
