# 📌 End-to-End-Data-Analytics
## Project Overview
This end-to-end data analytics project aims to analyze retail order data to extract meaningful business insights such as top-selling products, regional performance, sales trends, and profit growth. It demonstrates the complete data pipeline from data ingestion to transformation, storage, and analytical reporting using Python and SQL.

## Tools & Data-Set Used
1. Python (Pandas, SQLAlchemy)
2. SQL Server
3. SQL (Window Functions, Aggregations)
4. Data Source: Kaggle Dataset

## Step-by-Step Process
1. Data Collection and Preprocessing (Python) :
   
=> Downloaded retail order data from Kaggle.
   
=> Unzipped and read the CSV file into a Pandas DataFrame.

=> Cleaned null values ("Not Available", "unknown"), standardized column names, and converted date columns to proper datetime format.

=> Engineered new columns: sale_price, profit (from list price, cost price, and discount).

=> Removed unnecessary columns to streamline data for analysis.

2.  Data Storage (Python + SQL) :
   
=> Connected to SQL Server using SQLAlchemy.

=> Loaded the processed DataFrame into a SQL table df_orders using the to_sql() method.

3. Question Solved based on this Data-set :
   
=> Top 10 revenue-generating products.

=> Top 5 selling products in each region .

=> Identified the best month for sales in each product category.

=> Found the subcategory with the highest Year by Year growth in 2023 vs 2022.

## Key Insights Gained
a.) Identified best-selling products and regions to optimize inventory and marketing.

b.) Detected seasonal sales patterns for each category to improve forecasting.

c.) Evaluated subcategories driving the most profit growth year over year.



   
