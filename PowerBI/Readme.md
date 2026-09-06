# Power BI Dashboard

This folder contains the Power BI dashboard developed for the Financial Transaction Risk & Fraud Analytics project.

## Dashboard Overview

The dashboard provides an interactive view of financial transaction activity, fraud patterns, transaction risk, high-value transactions, and account-level fraud concentration.

The report is designed to support fraud-risk monitoring and business decision-making through interactive KPIs, filters, charts, and analytical tables.

---

## Dashboard Pages

### 01 — Overview

The Overview page provides a consolidated view of transaction activity and fraud indicators.

#### Key KPIs

- Total Transactions
- Total Amount
- Fraud Transactions
- Fraud Amount
- Overall Fraud Rate
- High-Value Fraud Rate

#### Key Visuals

- Transactions by Type
- Transaction Volume by Type
- Fraud Amount by Transaction Type
- Transactions Over Time
- Fraud Rate by Risk Category
- Fraud Transactions by Balance Anomaly
- Top 5 Origin Accounts by Fraud Amount
- Top 5 Destination Accounts by Fraud Amount
- High-Value Fraud Transactions

---

### 02 — Insights & Recommendations

The second page focuses on interpreting the analytical findings and converting them into business-oriented actions.

#### Key Analysis Areas

- Fraud Risk Patterns
- High-Value Transaction Risk
- Transaction-Type Risk
- Balance Anomalies
- Risk Category Analysis
- Account-Level Fraud Concentration
- High-Risk Transactions

#### Business Recommendations

- Monitor high-risk transaction types.
- Prioritize high-value transactions for additional review.
- Investigate accounts with significant fraud contribution.
- Strengthen balance consistency checks.
- Use risk scoring to prioritize suspicious transactions.
- Continuously monitor fraud indicators through BI reporting.

---

## Interactive Features

The dashboard includes interactive filtering through:

- Step Range
- Transaction Type
- Risk Category

Users can apply filters to analyze specific transaction segments and risk groups.

---

## Power BI Techniques Used

### Data Transformation

- Power Query
- Data type validation
- Data transformation
- Feature-based analysis

### DAX

- KPI measures
- Fraud rate calculations
- Fraud amount calculations
- High-value fraud analysis
- Risk-based calculations
- Account-level ranking
- Top 5 account analysis

### Visualization

- KPI Cards
- Donut Charts
- Column Charts
- Line Charts
- Tables
- Slicers

---

## Dashboard File

`Financial_Transaction_Risk_Fraud_Analytics.pbix`

---

## Dashboard Preview

### Overview

![Dashboard Overview](Dashboard_Overview.png)

### Insights & Recommendations

![Insights & Recommendations](Dashboard_Insights_Recommendations.png)

---

## Purpose

The dashboard transforms transaction-level financial data into actionable risk insights, helping users identify potential fraud patterns, prioritize high-risk transactions, and understand where fraud exposure is concentrated.

> **Note:** The risk scoring framework is rule-based and intended for analytical prioritization. Risk categories should not be interpreted as confirmed fraud without appropriate validation.
