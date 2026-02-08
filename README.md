Myanmar Food Price Intelligence Analytics

Data Science Portfolio Project — Nay Win Hlaing

Project Overview

This project analyzes food price trends across Myanmar to understand inflation patterns, regional price differences, and their impact on business decision-making.

Due to frequent price volatility and limited reliable market data, businesses and policymakers need data-driven insights to reduce risk and improve planning. This project demonstrates how analytics can support those needs.

Business Problem

Myanmar businesses face:

Rapid inflation

Supply chain disruptions

Unstable commodity prices

Key Question:

How can data analytics help businesses monitor price changes and make smarter purchasing and pricing decisions?

Objectives

Track monthly price changes

Identify price spikes and anomalies

Analyze regional differences

Provide decision-support insights

Tools & Technologies

Python (Pandas, Matplotlib)

R (Statistical Analysis)

SQL (Data aggregation)

Jupyter / DataCamp DataLab

Dataset Description

Includes:

Monthly prices of staple foods (rice, oil, eggs, vegetables)

Region-level market data

Inflation indicators

Methodology
Data Cleaning

Removed missing values

Standardized currency units

Filtered extreme outliers

Analysis

Trend analysis

Correlation analysis

Price distribution visualization

Example SQL
SELECT product, AVG(price)
FROM food_prices
GROUP BY product;

Key Insights

Staple food prices drive major cost increases.

Significant regional price variation exists.

Price spikes occur during supply disruptions.

Business Applications
Retail & SMEs

Adjust pricing strategy

Plan procurement timing

Agriculture

Decide optimal selling period

Government / NGOs

Monitor cost of living trends

Visualizations

Monthly price trend charts

Regional comparison graphs

Inflation movement analysis

(Add screenshots from your notebook here)

Future Improvements

Time-series forecasting (ARIMA / ML)

Real-time dashboard (Power BI/Tableau)

Automated data pipeline

Project Structure
myanmar-food-price-intelligence/
│
├── data/
├── notebooks/
├── R_analysis/
├── SQL_queries/
├── visuals/
└── README.md

Portfolio Value

This project demonstrates:

Real-world economic analytics

Multi-tool workflow (Python + R + SQL)

Business-focused insights

Regional market intelligence

Author

Nay Win Hlaing
Aspiring Data Scientist | Data Analytics | Market Intelligence
