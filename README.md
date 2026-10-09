# Indian Financial Fraud Analysis

## Project Overview

This project analyzes financial transactions to identify fraud patterns, understand payment behavior, and monitor transaction performance using Microsoft Excel and Tableau.

The dashboards present key performance indicators (KPIs), merchant-category analysis, payment-method distribution, monthly transaction trends, customer segments, and fraud reasons.

## Tools Used

* **Microsoft Excel:** Data analysis, PivotTables, KPI cards, charts, and dashboard creation.
* **Tableau:** Data visualization, calculated fields, KPI cards, and interactive dashboards.

## Key Performance Indicators

| KPI                        |         Value |
| -------------------------- | ------------: |
| Total Transactions         |       250,000 |
| Total Transaction Amount   | 4,151,881,350 |
| Fraud Transactions         |        13,473 |
| Fraud Rate                 |         5.39% |
| International Transactions |        12,572 |

*Values are based on the current dashboard and should be validated against the final workbook.*

## Analysis Performed

### 1. Payment Method Analysis

Analyzed transaction counts and transaction amounts across Credit Card, Debit Card, Net Banking, and UPI.

### 2. Fraud by Merchant Category

Compared fraud transaction counts across categories such as Airline, Ecommerce, Electronics, Fashion, Fuel, Grocery, Hospital, Hotel, Travel, and Utilities.

### 3. Monthly Transaction Trends

Analyzed monthly transaction counts and transaction amounts to identify changes in transaction activity throughout the year.

### 4. Fraud by Customer Segment

Compared transaction and fraud patterns across customer segments.

### 5. Fraud by Card Category

Examined fraud patterns across Basic, Gold, Platinum, and Standard categories.

### 6. Fraud Reasons

Analyzed recorded fraud reasons, including high-risk merchant activity, geographical and velocity anomalies, and suspicious transaction attempts.

### 7. KPI Dashboard

Created dashboards to monitor transaction volume, transaction amount, fraud count, fraud rate, and international transactions.

## Fraud Rate Calculation

Fraud Rate = (Number of Fraud Transactions / Total Number of Transactions) × 100

Using the current dashboard values:

Fraud Rate = (13,473 / 250,000) × 100 ≈ 5.39%

## Key Findings

* The dataset contains 250,000 transactions.
* There are 13,473 transactions flagged as fraudulent.
* The overall fraud rate is approximately 5.39%.
* Debit Card transactions represent the largest payment-method category by transaction count in the current Excel summary.
* Monthly transaction activity varies across the year.

## Project Files

* `excel/` — Excel dashboard and analysis workbook.
* `tableau/` — Tableau packaged workbook.
* `screenshots/` — Dashboard preview images.

## Business Objective

The objective is to make transaction and fraud patterns easier to monitor through visual reporting, helping analysts identify areas that may require further investigation.

## Disclaimer

This project is intended for educational and portfolio purposes. Fraud flags and recorded fraud reasons are analyzed as provided in the dataset; findings should not be interpreted as proof of criminal activity.

## Author

**Nakul Nagar**

GitHub: https://github.com/NAKUL-NAGAR
