**Customer Shopping Behavior Analysis: End-to-End Data Pipeline**
**📌 Project Overview**

This project demonstrates a complete data analytics lifecycle, transforming 3,900 raw consumer transactions into actionable business strategies. It showcases a multi-tool approach using Python for cleaning, SQL for deep-dive querying, and Power BI for executive-level visualization.

**🛠️ Tech Stack**
Languages: Python (Pandas, NumPy, Matplotlib, Seaborn)
Databases: PostgreSQL, MySQL, SQL Server, Oracle
BI & Reporting: Power BI, Gamma (AI Presentations)
Environment: Jupyter Notebook

**🚀 Key Technical Workflow**
Data Engineering (Python):
Data Cleaning: Handled 37 missing values in Review Rating using median imputation per category.
Feature Engineering: Created age_group bins and purchase_frequency metrics to improve segmentation.
Standardization: Renamed columns to snake_case for database compatibility.

**Multi-Database SQL Analysis:**
Migrated cleaned data to PostgreSQL to perform complex business queries.
Used CTEs and Window Functions to rank top products and compare revenue by gender and shipping type.
Interactive Dashboard (Power BI):
Visualized key KPIs: $59.76 Average Purchase Amount and 3.75 Average Rating.
Built dynamic slicers for Gender, Category, and Shipping Type.

**💡 Business Insights & Impact**
Revenue Drivers: Identified Young Adults as the highest revenue contributors ($62,143).
Discount Sensitivity: Found that Hats and Sneakers are "Discount-Dependent," with ~50% of sales requiring promos..
Customer Segmentation: Successfully categorized the database into Loyal (3,116), Returning (701), and New (83) segments.
Shipping Strategy: Confirmed Express Shipping users spend more on average ($60.48) than Standard users ($58.46)..

**📂 Repository Structure**
data/: Raw and cleaned datasets.
notebooks/: Python scripts for EDA and Cleaning.
sql_queries/: Scripts for PostgreSQL, MySQL, and SQL Server.
dashboard/: Power BI .pbix file.


👤 Author

JEBIN R
Data Analyst
LinkedIn: https://www.linkedin.com/in/jebin-dataanalyst/
Email: poomanijebin@gmail.com
