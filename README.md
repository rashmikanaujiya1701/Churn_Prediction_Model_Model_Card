# Churn_Prediction_Model_Model_Card
Capstone Project

# D2C Customer Churn Prediction

## Part 3: Churn Prediction Model & Model Card

### Objective

Predict whether a customer will churn within the next 60 days using historical behavioral, transactional, support, and engagement signals.

---

## Repository Contents

* churn_model.ipynb
* model.pkl
* metrics.json
* error_analysis.md
* model_card.md
* requirements.txt

---

## Modeling Approach

### Baseline Model

* Logistic Regression

### Stronger Model

* Random Forest Classifier

---

## Features Used

* Recency
* Frequency
* Monetary Value
* Support Ticket Count
* Refund Rate
* Campaign Engagement
* Web/App Activity
* Category Diversity
* Discount Usage

---

## Leakage Prevention

Only information available on or before the snapshot date was used.

Excluded:

* Future purchases
* Post-snapshot support tickets
* Future campaign outcomes
* Target-window information

---

## Model Outputs

* Churn Probability
* Predicted Churn Flag

---

## Saved Model

Load model using:

```python
import joblib
model = joblib.load("model.pkl")
```
