# Bank Churn Analytics

End-to-end customer churn analysis pipeline for a retail bank dataset — 
from raw data to a production-style BI dashboard.

## Goal

Simulate a real analyst task: given raw customer and transaction data, 
identify why customers churn, validate hypotheses with data, and deliver 
actionable insights through a dashboard a stakeholder could actually use.

## What this project demonstrates

- Relational schema design (Postgres) for customer + monthly balance/transaction data
- Redis caching layer for frequently queried aggregates
- Data cleaning and ETL with pandas
- Hypothesis-driven analysis (SQL + pandas) rather than exploratory-only EDA
- Business metric calculation (churn rate, retention, customer segmentation)
- Interactive BI dashboard (Metabase/Superset)

## Status

🚧 In progress — see commit history for current stage.

## Tech stack

Python (pandas), PostgreSQL, Redis, Docker, [Metabase/Superset — TBD]

## Roadmap

- [ ] Database schema + ETL
- [ ] Redis caching layer
- [ ] Exploratory analysis + hypotheses
- [ ] Hypothesis testing + business metrics
- [ ] BI dashboard
- [ ] Written case-study report
