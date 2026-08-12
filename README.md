# Customer Shopping Behavior Analysis

End-to-end data analysis project exploring customer shopping patterns, revenue drivers, and segmentation using Python, SQL Server, and Power BI.

## 📊 Project Overview

This project analyzes 3,900 customer transactions to uncover revenue drivers, customer segments, and shopping behavior patterns — providing actionable insights for business decision-making.

**Tools:** Python (Pandas) | SQL Server | Power BI (DAX) | Excel

## 🔑 Key Insights

- **Loyal customers (79.9% of customer base) drive the majority of revenue**, contributing $84K in Clothing alone — retention strategy should be a priority over acquisition.
- **Discount campaigns show minimal ROI**: customers without discounts spend only $0.85 more on average than those with discounts, suggesting current discount strategy may not be cost-effective.
- **Clothing is the top category (44.7% of total revenue / $104K)**, while Outerwear is the lowest performer (7.9% / $19K) — indicating a clear opportunity for targeted marketing on Outerwear.
- Revenue is nearly evenly distributed across age groups ($55K–$62K), showing no single demographic dominates — broad-based marketing appeal.
- Fall season shows slightly higher revenue across most categories, useful for inventory planning.

## 🛠️ Process

1. **Data Exploration (Python)** — Explored 3,900 rows x 18 columns, identified 37 missing values in review ratings, imputed using category-level median.
2. **Data Cleaning (Python)** — Standardized column names, removed duplicate discount/promo columns, engineered new features (`age_group`, `segment`, `purchase_frequency_days`).
3. **Database Import (SQL Server)** — Loaded cleaned data via SQLAlchemy into SQL Server for querying.
4. **SQL Analysis** — Answered 10 business questions using aggregations, window functions (`ROW_NUMBER`, `PARTITION BY`), and conditional logic.
5. **Power BI Dashboard** — Built a 4-page interactive dashboard with dynamic DAX measures, dynamic text insights, and cross-filtering.

## 📈 Dashboard Pages

| Page | Focus |
|------|-------|
| Revenue & Sales Performance | Overall KPIs, revenue by category/gender/location/age |
| Customer Intelligence | Customer segmentation, loyalty, subscription impact |
| Shopping Behaviour | Payment/shipping preferences, purchase frequency, seasonal trends |

## 📁 Repository Structure

```
customer-shopping-behavior-analysis/
│
├── README.md
├── Analyse Customer Shopping Behavior.ipynb
├── Customer_Behaviour.sql
├── customers_pehaviour2.pbix
├── customershoppingbehavior.csv
├── Page1_Revenue & Sales Performance.png
├── Page2_Customer Intelligence.png
└── Page3_Shopping Behaviour.png
```

## 🚀 How to Reproduce

1. Download the dataset (Customer Shopping Behavior, Kaggle)
2. Run the Jupyter notebook to clean the data and load it into SQL Server
3. Execute the SQL queries in `Customer_Behaviour.sql` to validate the analysis
4. Open the Power BI file and refresh the data connection

## 📬 Contact

**Bahija Babzine** — Data Analyst | Power BI Developer  
📧 bahijababezine@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bahija-babzine-a37285207/)  
🔗 [GitHub](https://github.com/babzine1999)
