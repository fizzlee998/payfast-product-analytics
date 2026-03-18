# PayFast Nigeria — Product Analytics Project

## Overview

A complete end-to-end product analytics project for a fictional Nigerian
fintech called PayFast, analysing 10,000 users, 26,241 transactions,
and ₦474.8M in revenue across January to September 2024.

This project demonstrates the full product analytics workflow — from raw
data generation and Python analysis to an interactive HTML dashboard and
a professional case study report.

---

## Analyses Covered

| Analysis | Description |
|---|---|
| Retention and Cohort Analysis | 6 monthly cohorts tracked across 5 months |
| Funnel Analysis | App open to signup to onboarding to KYC to first transaction |
| User Segmentation | Power Users, Regular, Casual, At-Risk, Churned |
| A/B Test Interpretation | Onboarding redesign — statistically significant +11% lift |
| Revenue Analysis | Monthly trends, transaction types, plan and geography breakdown |

---

## Key Findings

- Only 4.7% of acquired users complete a first transaction — KYC is the primary barrier
- Variant B onboarding delivers a statistically proven +11% activation lift (p < 0.0001)
- 288 At-Risk users represent ₦65M in recoverable revenue this month
- Revenue per active user is strong at ₦91k to ₦103k per month
- 141 Power Users (2.6% of base) drive a disproportionate share of total revenue

---

## Project Files

| File | Description |
|---|---|
| PayFast_Analysis.ipynb | Full Python analysis in Jupyter notebook |
| PayFast_Dashboard.html | Interactive dashboard — download and open in any browser |
| payfast_users.csv | 10,000 synthetic user records |
| payfast_transactions.csv | 26,241 transaction records |
| payfast_funnel.csv | 35,574 funnel events |


---

## How to View the Dashboard

1. Download PayFast_Dashboard.html
2. Open it in any browser — Chrome, Firefox, or Edge
3. No installation or internet connection needed

---

## How to Run the Analysis

Install dependencies first:

pip install pandas matplotlib jupyter

Then launch Jupyter:

jupyter notebook

Open PayFast_Analysis.ipynb and run all cells from top to bottom.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Python with pandas | Data generation, cleaning, and analysis |
| Jupyter Notebook | Analysis environment |
| Chart.js | Dashboard visualisations |
| SQL via BigQuery | Querying and aggregating large datasets |
| GitHub | Version control and portfolio hosting |

---

## Dataset Note

This is a synthetic dataset generated with realistic Nigerian fintech
patterns — including channel-based retention differences, A/B test
effects, device-based funnel variations, and geographic revenue
distribution. All names, IDs, and figures are fictional.

---

## Skills Demonstrated

Cohort analysis, funnel analysis, user segmentation, A/B test
interpretation, revenue analysis, data storytelling, dashboard design,
Python, SQL, Jupyter, Chart.js.
