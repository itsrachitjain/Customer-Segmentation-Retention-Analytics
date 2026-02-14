🚀 Customer Segmentation & Retention Analytics

End-to-end Customer Intelligence & Retention Analytics project using Python and Power BI to analyze large-scale transactional data and generate actionable business insights.

📌 Project Overview

This project analyzes:

📊 600,000 Transactions

👥 200,000 Customers

🔁 200,000 Churn Records

The goal is to identify high-value customers, churn risk segments, revenue concentration patterns, and cohort-based retention trends to support data-driven business strategy.

🎯 Objective

Perform customer-level aggregation and behavioral analysis

Build an RFM (Recency, Frequency, Monetary) segmentation model

Measure churn probability across customer segments

Conduct cohort-based retention analysis

Develop an executive-level interactive dashboard

📂 Dataset

Three primary datasets:

transactions.csv

customers.csv

churn_labels.csv

Key Features:

Customer ID

Transaction ID

Transaction Date

Revenue (Amount)

Signup Date

Churn Label

RFM Metrics

Cohort Month

Cohort Index

⚙️ Data Engineering & Processing
Data Cleaning

Removed duplicate transactions

Filtered negative/zero revenue entries

Converted date fields to datetime format

Validated null values

Data Integration

Merged transactions, customers, and churn datasets

Created snapshot date logic for Recency calculation

📊 RFM Modeling

Built a quantile-based RFM framework:

Recency → Days since last purchase

Frequency → Number of transactions

Monetary → Total revenue contribution

Applied weighted scoring:

R (50%)

F (30%)

M (20%)

Customer Segments:

Champions

Loyal

At Risk

Potential

🔁 Cohort & Retention Analysis

Derived CohortMonth (first purchase month)

Calculated CohortIndex (months since acquisition)

Built retention matrix

Measured Month 1, 3, 6 & overall retention

Retention Insights:

Month 1 Retention: ~10%

Month 3 Retention: ~17%

Month 6 Retention: ~27%

Overall Retention: ~54%

📈 Key Business Insights
Revenue Concentration

Top ~20% customers contributed 55–65% of total revenue

Loyal customers drove ~25–30% of recurring revenue

Churn Intelligence

“At Risk” segment showed 2–3x higher churn probability

Customer Value Growth

ARPU increased across mature cohorts

High-RFM customers demonstrated revenue stability

📊 Power BI Dashboard

Built a 3-page interactive Executive Dashboard:

Executive Overview

RFM & Customer Segmentation

Cohort & Retention Analytics

Features:

KPI Cards (Revenue, Customers, ARPU, Churn Rate)

Segment & Region slicers

Revenue trend analysis

Cohort retention heatmap

🛠 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Power BI

RFM Modeling

Cohort Analysis

Data Cleaning & Transformation

📁 Project Structure
├── transactions.csv
├── customers.csv
├── churn_labels.csv
├── Customer_Segments.csv
├── Cohort_Retention.csv
├── Final_Customer_Analytics.csv
├── customer_segmentation.ipynb
└── README.md

🚀 Business Impact

✔ Identified revenue-driving customer segments
✔ Enabled proactive churn detection
✔ Improved lifecycle retention visibility
✔ Built scalable segmentation framework for growth strategy

🔗 Future Improvements

Machine learning churn prediction model

CLV (Customer Lifetime Value) modeling

Automated retention campaign simulation

Deployment using Streamlit / Flask

👤 Author

Rachit Jain
Aspiring Data Analyst | Customer Analytics | Business Intelligence
