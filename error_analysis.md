# Error Analysis

## False Positives

Definition:

Predicted churn but customer did not churn.

Business Impact:

* Unnecessary retention spending.
* Reduced campaign efficiency.

### Example Customers

| Customer ID | Reason                     |
| ----------- | -------------------------- |
| CUST_1001   | Temporary inactivity       |
| CUST_1005   | Seasonal purchasing        |
| CUST_1012   | High support activity      |
| CUST_1017   | Recent campaign engagement |
| CUST_1028   | Short-term inactivity      |

---

## False Negatives

Definition:

Model predicted retention but customer churned.

Business Impact:

* Lost revenue.
* Missed intervention opportunity.

### Example Customers

| Customer ID | Reason                  |
| ----------- | ----------------------- |
| CUST_1031   | Sudden disengagement    |
| CUST_1039   | Product dissatisfaction |
| CUST_1044   | Refund-related churn    |
| CUST_1050   | Competitor switch       |
| CUST_1067   | Hidden churn indicators |

---

## Key Learnings

1. Support signals are strong churn indicators.
2. Refund behavior improves prediction quality.
3. Engagement metrics help reduce false negatives.
4. Recent activity alone is insufficient.
5. Campaign response provides additional predictive power.
