# Model Card

## Model Name

Customer Churn Prediction Model

---

## Intended Use

Identify customers likely to churn within the next 60 days so retention teams can take proactive action.

---

## Intended Users

* Marketing Team
* Customer Success Team
* Product Team
* Leadership Team

---

## Data Used

Sources:

* Customers
* Orders
* Support Tickets
* Web Events
* Campaign History

Target:

* Churn within next 60 days

---

## Model Type

Random Forest Classifier

Baseline Comparison:

* Logistic Regression

---

## Performance

See metrics.json for detailed results.

Primary Metrics:

* Precision
* Recall
* F1 Score
* ROC-AUC

---

## Threshold

Business threshold selected based on recall and retention budget constraints.

---

## Limitations

* Customer behavior may change over time.
* New products may alter churn patterns.
* Seasonal effects may impact predictions.

---

## Ethical Risks

* Over-targeting customers with incentives.
* Potential bias from historical campaign decisions.
* Unequal treatment across customer groups.

---

## Monitoring Requirements

Monitor:

* Recall
* Precision
* Data drift
* Feature drift
* Segment performance

Review monthly.

---

## Should Not Be Used For

* Credit decisions
* Employment decisions
* Individual risk scoring outside retention use cases
