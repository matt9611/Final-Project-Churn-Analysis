# KKBOX Churn and Retention Analysis

## Overview
This project analyzes subscription churn among KKBOX users in Taiwan. It combines customer profile, transaction and listening data to explore which behaviours and user segments are associated with churn.

## Project Workflow
1. **Data sources:** Started with three core datasets: `members_v3.csv`, `transactions.csv` and `user_logs.csv`. `train.csv` provided the churn label, `is_churn`.
2. **Python:** Cleaned and prepared the data, including profile fields, transaction values and dates, then exported the cleaned datasets.
3. **SQL:** Loaded and joined the data into analysis tables, recalculated churn metrics, and created summaries for demographic, subscription, spending and listening behaviour.
4. **Tableau:** Built dashboards to present the analysis and highlight retention priorities.

## Key Findings
- Users with Auto-Renew turned off show higher churn.
- Churn is higher in the lowest listening-activity quartile than in the highest.
- The 30-day plan with Auto-Renew off is a large segment at risk, representing about 9% of users with around 24.5% churn.

## Tools
Python · SQL · Tableau

## Limitations
The analysis is observational, so the findings show associations rather than causes. City-level results are exploratory because city names were manually mapped.
