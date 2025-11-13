# Customer Behavior Analysis

## Overview
This project analyzes 3,900 customer transactions to uncover insights into spending patterns, product preferences, loyalty behavior, and discount impact.  
The analysis helps guide data-driven marketing, customer retention, and subscription strategies for improved business growth.

---

## Dataset
**Source:** Transactional customer dataset  
**Records:** 3,900  
**Columns:** 18  

**Key Features**
- Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item Purchased, Category, Purchase Amount, Season  
- Behavioral: Discount Applied, Frequency of Purchase, Review Rating  

---

## Tools and Technologies

| Tool | Purpose |
|------|----------|
| Python (Pandas, NumPy, Matplotlib) | Data loading, cleaning, and exploratory analysis |
| MySQL | Querying and relational data analysis |
| Power BI | Interactive dashboard visualization |
| Gamma App | Report and presentation creation |
| Jupyter Notebook | Documentation and analysis execution |

---

## Project Workflow

### 1. Data Loading and Cleaning
- Loaded dataset into Pandas DataFrame.  
- Handled missing values using median imputation.  
- Standardized column names to snake_case.  
- Created new feature `age_group` (Young Adults, Adults, Middle-Aged, Seniors).  
- Removed redundant columns such as `promo_code_used`.

### 2. Exploratory Data Analysis (EDA)
- Explored purchase patterns by demographics.  
- Analyzed the effect of discounts and shipping preferences.  
- Visualized product performance and revenue distribution.

### 3. SQL Analysis
- Imported cleaned dataset into MySQL Server.  
- Ran 10 targeted SQL queries to analyze:
  - Revenue by gender and age group  
  - Impact of discounts on purchase value  
  - Subscription vs non-subscription spending  
  - Top-rated and top-purchased products  

### 4. Dashboard Creation (Power BI)
- Built an interactive Power BI dashboard to visualize:
  - Revenue by demographics  
  - Product category performance  
  - Discount effectiveness  
  - Customer loyalty segmentation  

### 5. Reporting and Presentation
- Compiled findings and visualizations into a Gamma App report and presentation.

---

## Key Insights
- Young Adults contribute 26.67% of total revenue (highest among all age groups).  
- 3,116 customers identified as loyal (≥5 purchases).  
- High spenders also use discounts — opportunity for “smart discounts.”  
- Top-rated products: Gloves, Sandals, and Boots.  

---

## Recommendations
- Boost Subscriptions: Target non-subscribers with exclusive benefits and free shipping.  
- Enhance Loyalty Programs: Introduce tier-based rewards for repeat customers.  
- Optimize Discounts: Implement “Spend More, Save More” offers to increase revenue.  
- Promote Top Products: Use high-rated products in marketing campaigns.  

---

## How to Run

### Prerequisites
- Python 3.9+  
- MySQL Server  
- Power BI Desktop  
- Jupyter Notebook  

### Steps
1. Clone or download this repository.  
2. Open and run `customer_behavior_analysis.ipynb` in Jupyter Notebook.  
3. Create a MySQL database:
4. Load the cleaned dataset into MySQL.
5. Run SQL queries from queries.sql.
6. Open Customer_Behavior_Dashboard.pbix in Power BI.
   
## Author
**Dinesh Kumar M**  
Data Analyst | Python | SQL | Power BI  
- Email: dineshkumarmmdr@gmail.com 
- LinkedIn: https://www.linkedin.com/in/dinesh-kumar-4b22672a7/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BN230MRQARyqCWVj4BTl8tA%3D%3D

