---
layout: default
title: Portfolio
permalink: /portfolioDA/
---

### [About me (EN)](/) | [Обо мне (RU)](/about_ru/)
### Portfolio DA (EN) | [Портфолио DA (RU)](/portfolioDA_ru/)
### [Portfolio DS/ML/DL (EN)](/portfolioDS/) | [Портфолио DS/ML/DL (RU)](/portfolioDS_ru/) 

---

## Cases:

### [Analysis of 12.8 Million NYC Taxi Trips: ETL Pipeline and Demand Factor Research](https://vk.cc/d0P0tS)
- **Problem:** Identify factors influencing demand, fare, and tipping behavior.
- **Solution:** Built an ETL pipeline in Python: loaded data from cloud storage, performed cleaning, enriched with weather data and taxi zones, and visualized key metrics. Identified peak hours and days, determined areas with the highest tips, and analyzed airport trip patterns.

---

### [Product and Business Data Visualization in Analytical Dashboards: Marketplace Sales Analysis](https://vk.cc/cRIhh8)
- **Problem:** Lack of an automated pipeline for collecting, storing, and visualizing marketplace sales, customer, and product data.
- **Solution:** Developed an ETL pipeline in Python for daily API data collection and loading into PostgreSQL. Automated execution via cron. Built dashboards in Yandex DataLens with three tabs: overall sales, customers, products. The dashboard was featured in the DataLens Gallery. Ensured a stable data flow for analytics, implemented interactive filters, and conducted a 2023 sales study directly within the dashboard.

---

### [Identifying Users with Payment Chains Violating Payment System Policy](https://vk.cc/cNpZqb)
- **Problem:** Needed to detect users whose total successful payments within 24 hours exceed the established limit (20,000,000 units) to prevent fraud and ensure compliance with payment system policies.
- **Solution:** Developed an analytical SQL query for ClickHouse that uses window functions to compute a rolling sum of payments over a 24-hour interval for each transaction and identifies threshold violations. The query enables rapid detection of violations, allows adjustment of the time window and threshold, and supports analysis of suspicious payment chains for further investigation.

---

### [Unlimited Data Plan Recommendations Based on Traffic Analysis](https://vk.cc/cNq061)
- **Problem:** A telecom operator needed to proactively offer unlimited tariff options to subscribers to reduce the risk of data overages and improve customer experience.
- **Solution:** Developed an SQL script for ClickHouse that analyzes subscriber internet traffic consumption over a specified period, identifies the most expensive option, and forecasts monthly usage based on average daily traffic. The script automatically generates a list of subscribers whose forecasted traffic exceeds the limit, along with a recommendation for a specific unlimited option.

---

### [One-Day-Ahead Time Series Forecasting of Successful Payments](https://vk.cc/cNq1cE)
- **Problem:** Required daily forecasting of successful payment volumes for financial planning and anomaly detection.
- **Solution:** Developed an SQL script for ClickHouse that builds a stochastic linear regression model (SGD) on historical data (January–June 2024), using log transformation of the target variable and accounting for weekly seasonality. Forecasting is performed directly within the DBMS. The model provides next-day payment forecasts, evaluates deviations from actual values, and can be integrated into regular analytical workflows.

---

### [Exploratory and ABC Analysis for a Delivery Service](https://vk.cc/cNaRBY)
- **Problem:** Required a comprehensive analysis of sales and product assortment for a delivery service to identify key product groups, evaluate promotional effectiveness, and assess profitability.
- **Solution:** Performed data analysis using Pandas: calculated average order value, promotional share, and category-level margins. Conducted ABC analysis by sales volume and revenue for assortment prioritization. Identified the best-selling product group and high-margin subcategories, determined the promotional share in the "Cheeses" category, and created visualizations to support assortment policy decisions.

---

### [Identifying Payment Delinquencies in Credit Products](https://vk.cc/cNaRCt)
- **Problem:** A credit institution needed to monitor delinquency trends to forecast risks, manage the credit portfolio, and respond promptly to deteriorating payment discipline.
- **Solution:** Developed an analytical pipeline in Python to consolidate data from three sources (loan applications, scheduled payments, actual payments). Implemented algorithms for detecting overdue payments by timing and amount, with monthly and weekly aggregation and trend visualization. Identified a steady increase in delinquencies of ~4.4% from June to November 2022 (from 86.57% to 90.94%). Detected peak values in November–December, leading to recommendations for adjusting credit policy, strengthening collection efforts, and increasing provisions.

---

### [Pharmacy Chain Analytics: ABC/XYZ Analysis, KPI Dashboard, and Reporting Automation](https://vk.cc/cNaRph)
- **Problem:** A pharmacy chain needed automation for processing 1C invoices, assortment analysis, and visualization of key performance indicators for inventory and sales management.
- **Solution:** Developed a data processing pipeline: [processing 1C invoices](https://vk.cc/cNaRph) and [automated loading into PostgreSQL](https://vk.cc/cNaRpZ), building a sales data mart. Conducted [ABC/XYZ assortment analysis](https://vk.cc/cNaRnp), [Market Basket Analysis, and created a "product - pharmacy store - sales volume" table](https://vk.cc/cNaRok). [Visualized network KPIs in a Superset dashboard](https://vk.cc/cNaRqM). Identified non-performing items and categories for assortment optimization, discovered product affinities for cross-selling. The dashboard enabled daily monitoring of key network metrics.

---

### [Educational Portal Analytics: Activity Metrics, Retention, and Dashboards](https://vk.cc/cNaRFl)
- **Problem:** An EdTech platform needed to assess user engagement, identify factors affecting academic performance and retention, and automate monitoring of key metrics for product decisions.
- **Solution:** [Built an ETL pipeline to extract data from the website API into PostgreSQL](https://vk.cc/cNaRFl), [processed payment and student activity logs](https://vk.cc/cNaRt9). Calculated product metrics (MAU, WAU, DAU, retention), [analyzed activity patterns by time and marketing campaigns, and investigated the correlation between activity and academic performance](https://vk.cc/cNaRt9). [Visualized results in dynamic Metabase dashboards](https://vk.cc/cNaRDk). Identified user activity patterns, determined the correlation between engagement and academic performance, and discovered factors influencing internal balance recharges and deductions. Dashboards enabled the product team to improve user retention in a targeted manner.

---

### [IT-Resume: Corporate Client Analytics and ETL Pipelines](https://vk.cc/cNaRx4)
- **Problem:** Needed to provide B2B clients with analytics on their sales and implement automated data processing workflows to improve reporting efficiency.
- **Solution:** [Developed ETL pipelines to process corporate client sales data](https://vk.cc/cNaRxE). Configured automated data updates. [Ensured data transparency for corporate clients](https://vk.cc/cNaRx4), reduced reporting turnaround time, and improved analytics accuracy through automation.

---
 
### [Retail Chain Analysis: Data Exploration and Power BI Dashboard](https://vk.cc/cNaRyy)
- **Problem:** A retail chain required an in-depth sales analysis and a user-friendly tool for its analytics team to monitor key performance indicators.
- **Solution:** [Conducted exploratory data analysis: evaluated sales dynamics, product categories, and regional characteristics](https://vk.cc/cNaRyy). [Built an interactive Power BI dashboard](https://vk.cc/cNaRzt) for daily metric monitoring. The dashboard enabled analysts to track KPIs promptly, detect anomalies, and make data-driven decisions.

---

*Last updated: 2026-09-09*