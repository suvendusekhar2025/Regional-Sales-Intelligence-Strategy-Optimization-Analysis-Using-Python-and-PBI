# Regional-Sales-Intelligence-Strategy-Optimization-Analysis-Using-Python-and-PBI-and-MS Excel

📄 Project Description:
This data analytics project focuses on Acme Co.'s U.S. sales performance between 2014 and 2018, aiming to uncover revenue and profit drivers across products, customer segments, sales channels, and regions. The project involved end-to-end data processing, in-depth exploratory data analysis (EDA), anomaly detection, and strategic dashboard design using Power BI to support data-driven decision-making.

✅ What Was Done:
🔹 1. Data Integration & Cleaning
Unified 6+ raw datasets (Sales, Products, Budgets, Customers, Regions, States).

Cleaned and normalized 74,000+ transaction records.

Created derived fields like profit, profit_margin_pct, and order_month_num.

Ensured zero missing values or duplicates across key fields.

🔹 2. Exploratory Data Analysis (EDA)
Univariate & Bivariate Analysis: Analyzed revenue, cost, profit, quantity, unit price.

Trend Analysis: Identified seasonal peaks in May–June and dips in January.

Outlier Detection: Flagged unusually high or low order values and margin outliers.

Correlation Analysis: Found strong relationships:

Unit Price ↔ Revenue: 0.91

Unit Price ↔ Profit: 0.79

Revenue ↔ Profit: 0.87

Customer Segmentation: Clustered based on revenue and margins to identify high-value accounts and discount hotspots.

🔹 3. Strategic Insights Derived
Top Products: Products 26 & 25 contributed ~25% of revenue.

Top Channels: Wholesale drove 54.1% of total revenue; Export offered highest margins (~38% avg).

Top States: California alone generated $230M revenue with 7.6K+ orders.

Regional Trends: West dominated in volume; Northeast underperformed.

Order Distribution: AOV showed a right-skewed distribution, with high-value orders being rare but impactful.

🔹 4. Recommendations Formulated
Launch seasonal promotions in April and January to stabilize revenue dips.

Expand Export channel for margin gain; incentivize wholesale volume.

Replicate California’s sales model in Midwest & Northeast.

Phase out or reprice low-margin SKUs; double down on top performers.

Flag orders with <80% margin for closer cost analysis.

🔹 5. Power BI Dashboard Development
Built an interactive 3-page dashboard:

Performance Overview

Customer Segmentation

Revenue Scenarios

Enabled drilldowns by time, region, product, channel, supporting real-time executive insight.

🎯 What You’ll Learn from This Project:
Practical skills in real-world EDA using Pandas, Matplotlib, Seaborn, and Power BI.

How to design business-focused KPIs and dashboards for decision-makers.

Techniques for handling multi-source data, including data merging, feature engineering, and normalization.

How to uncover seasonality, concentration risk, and hidden revenue opportunities.

Applying correlation analysis and segmentation to enhance pricing and promotion strategies.

📌 Key Tools & Technologies Used:
Python (Pandas, NumPy, Matplotlib, Seaborn)

Power BI

Excel for initial data mapping

Statistical Metrics: Correlation coefficients, outlier thresholds, margin %, AOV, customer tiers
