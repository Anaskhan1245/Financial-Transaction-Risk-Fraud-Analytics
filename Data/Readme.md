# Data

This folder contains documentation related to the dataset used in the project.

The original transaction dataset is not included in this repository due to dataset size and repository management considerations.

The data dictionary documents the fields used throughout the Python, SQL, and Power BI analysis.


# Data Dictionary

| Column | Description |
|---|---|
| step | Time step associated with the transaction |
| type | Type of financial transaction |
| amount | Transaction amount |
| nameOrig | Origin account identifier |
| oldbalanceOrg | Origin account balance before transaction |
| newbalanceOrig | Origin account balance after transaction |
| nameDest | Destination account identifier |
| oldbalanceDest | Destination account balance before transaction |
| newbalanceDest | Destination account balance after transaction |
| isFraud | Fraud label |
| isFlaggedFraud | Existing fraud flag indicator |
| origin_balance_change | Change in origin account balance |
| origin_balance_error | Difference between expected and observed origin balance movement |
| destination_balance_change | Change in destination account balance |
| destination_balance_error | Difference between expected and observed destination balance movement |
| origin_zero_balance | Indicates whether origin balance becomes zero |
| destination_zero_balance | Indicates whether destination balance becomes zero |
| amount_percentile | Relative percentile position of transaction amount |
| risk_score | Rule-based transaction risk score |
| risk_category | Categorized transaction risk level |
| balance_anomaly | Indicator for balance inconsistency |
