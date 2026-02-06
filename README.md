# Transaction Risk Prioritization System

## Problem Statement
Payment networks process millions of transactions daily, but manual risk review capacity is limited.  
This project simulates a real-world risk operations framework to prioritize anomalous transactions and merchants while minimizing operational workload.

## Objective
- Detect anomalous transaction behavior using behavioral deviation signals
- Aggregate risk at transaction and merchant levels
- Prioritize manual review effort based on risk concentration
- Simulate reduction in manual review volume

## Analytics Approach
1. Data cleaning and validation to ensure operational reliability
2. Behavioral feature engineering:
   - Transaction velocity
   - Amount deviation
   - Time-of-day deviation
   - Composite risk scoring using Z-score normalization
3. Risk bucket classification aligned with operations:
   - High Risk – Manual Review
   - Medium Risk – Monitor
   - Low Risk – Auto Clear
4. Risk aggregation at merchant level
5. Executive dashboard for risk operations decision-making

## Key Insights
- Only ~0.09% of transactions require manual review
- Risk is highly concentrated among a small subset of merchants
- Prioritized review framework reduces simulated manual review load by ~99%

## Business Relevance
This framework mirrors how payment networks and banks prioritize fraud and risk operations, enabling scalable review processes without sacrificing risk coverage.

## Tools Used
- Python (Pandas, NumPy)
- Power BI
- GitHub

## Dashboard Preview
![Risk Operations Dashboard](dashboard/dashboard_screenshot.png)
