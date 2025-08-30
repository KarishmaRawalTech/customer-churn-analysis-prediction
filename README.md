Customer Churn Prediction Project
🚀 Project Overview

This project analyzes 10,000+ customer records to predict churn and help businesses retain high-risk customers. It involves data cleaning, transformation, and feature engineering using SQL, preparing data for Machine Learning modeling, and creating Power BI-ready views for visual insights.

📂 Project Structure

stg_Churn – Raw staging data (50+ columns)

prod_Churn – Cleaned and transformed production data

vw_ChurnData – View for Churned (2,500+) / Stayed (6,500+) customers

vw_JoinData – View for newly joined customers (1,000+)

churn_analysis_pipeline.sql – SQL script for ETL, null handling, and view creation

🛠️ Technologies Used

SQL Server – Data extraction, transformation, and aggregation

Python – For Machine Learning modeling

Power BI – Dashboard visualization

🔍 Key Features

Handled 30+ null columns efficiently

Segmented customers by Gender, State, Contract type, and Internet usage

Analyzed revenue contribution: Churned = 25% revenue, Stayed = 70%, Joined = 5%

Created 2 main views for Power BI dashboards

💡 Insights

Identified 2,500+ high-risk churn customers

Revenue distribution analyzed across customer statuses

Dashboards provide actionable insights for decision-making

⚡ How to Use

Run the SQL script churn_analysis_pipeline.sql to create production tables and views

Connect Power BI to vw_ChurnData and vw_JoinData for dashboards

Use the cleaned dataset for ML model training and churn prediction

📈 Outcome

Predict which customers are likely to churn

Enable data-driven strategies to retain valuable customers

Support business growth through analytics and visualization
