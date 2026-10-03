# Customer Churn Analysis

Why are customers leaving a subscription business, and which segments put the most revenue at risk?

## Problem
Churn directly hits recurring revenue. This project measures overall churn, finds the customer segments driving it, and recommends where retention efforts would pay off most.

## Data
SQLite database (`customer_churn.db`) with 3 tables: [customers, subscriptions, usage], joined in SQL for analysis.

## Approach
1. Joined the 3 tables in SQL to build a single customer-level view.
2. Built 20+ KPIs in Python (Pandas, NumPy), including churn rate, tenure, usage frequency and revenue per customer.
3. Segmented customers by plan type and behaviour to find where churn concentrates.
4. Quantified the revenue at risk from churning segments.

## Key findings
- **28.6%** overall churn rate
- **18%** of revenue at risk
- Monthly subscribers churn **6x more** than [annual] subscribers

## Recommendations
- [e.g. Offer annual-plan incentives to engaged monthly users]
- [e.g. Run win-back campaigns for lapsed high-value customers]

## Tools
SQL (SQLite) · Python (Pandas, NumPy) · Jupyter Notebook [· Matplotlib / Seaborn]

## How to run
    git clone https://github.com/DeepanshuHanda7/churn-analysis.git
    cd churn-analysis
    jupyter notebook ChurnAnalysis_Project.ipynb
