🛍️ Customer Behavior Analysis
📘 Overview

This project analyzes 3,900 customer transactions to uncover patterns in spending behavior, product preferences, loyalty, and discount impact.
The goal is to provide data-driven recommendations to improve customer retention, optimize marketing, and strengthen subscription programs.

📊 Dataset

Source: Transactional customer dataset

Records: 3,900

Columns: 18

Key Features:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season

Behavioral: Discount Applied, Frequency of Purchase, Review Rating

🧰 Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy, Matplotlib)	Data loading, cleaning, and exploratory analysis
MySQL	Querying and relational data analysis
Power BI	Dashboard creation and visualization
Gamma App	Report and presentation generation
Jupyter Notebook	Analysis and documentation
⚙️ Steps Followed
1. Data Loading & Preparation

Loaded dataset into a Pandas DataFrame.

Cleaned and transformed data:

Handled missing values using median imputation.

Standardized column names to snake_case.

Created new feature age_group (Young Adults, Adults, Middle-Aged, Seniors).

Removed redundant columns like promo_code_used.

2. Exploratory Data Analysis (EDA)

Analyzed distributions of purchase amount, discounts, and reviews.

Identified top-spending segments by age and gender.

Visualized product category performance and shipping preferences.

3. SQL Analysis

Loaded clean dataset into MySQL Server.

Executed 10 SQL queries to extract insights:

Revenue by gender and age group

Impact of discounts on purchase value

Subscription vs non-subscription spending

Top-rated and top-purchased products

4. Dashboard Creation (Power BI)

Designed an interactive dashboard for:

Revenue by demographics

Product category performance

Discount analysis

Customer loyalty segmentation

5. Report & Presentation

Summarized findings and recommendations in a Gamma App report and PPT for stakeholders.

📈 Dashboard Highlights

Revenue Breakdown: Young Adults contributed 26.67% of total revenue.

Loyalty Segments: 3,116 customers identified as “Loyal” (≥5 purchases).

Discount Insights: High-value spenders also use discounts—suggesting smart discount strategies can increase basket size.

Top Products: Gloves, Sandals, and Boots had the highest review ratings.

💡 Results & Recommendations

Boost Subscriptions: Target non-subscribers with benefits like free shipping.

Enhance Loyalty Programs: Create tier-based rewards for repeat customers.

Optimize Discounts: Introduce “Spend More, Save More” models.

Highlight Top Products: Use high-rated items in campaigns to attract new buyers.

🚀 How to Run the Project
Prerequisites

Python 3.9+

MySQL Server

Power BI Desktop

Jupyter Notebook

Steps

Clone or download this repository.

Open and run customer_behavior_analysis.ipynb in Jupyter Notebook.

Load the cleaned dataset into MySQL (CREATE DATABASE customer_behavior;).

Execute SQL queries from queries.sql.

Open Customer_Behavior_Dashboard.pbix in Power BI to explore visuals.

View the final report and presentation in Gamma (customer_behavior_report.gamma).

🧑‍💼 Author

Dinesh Kumar M
Data Analyst | Python | SQL | Power BI
