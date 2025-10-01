# Global Retail Analytics Dashboard

## 📌 Project Overview
The **Global Retail Analytics Dashboard** is a data analytics project designed to unify sales data from 6 countries (Canada, China, India, Nigeria, UK, US). By combining SQL transformations with interactive Power BI dashboards, it provides insights into revenue, profit, category performance, store trends, and customer payments to support strategic decision-making.

## ⚙️ Tech Stack
- **Excel** – Initial data cleaning (removed nulls, handled missing values).  
- **PostgreSQL** – Data storage, SQL transformations, deduplication.  
- **Power BI** – Data modeling, DAX calculations, and dashboard visualization.

  ## 📂 Data Sources
- `sales_Canada.csv`  
- `sales_China.csv`  
- `sales_India.csv`  
- `sales_Nigeria.csv`  
- `sales_UK.csv`  
- `sales_US.csv`

Each dataset includes transaction-level details such as **Transaction ID, Date, Country, Store Location, Product, Quantity, Amount, Profit, Sales Rep**.

## 🛠️ Process Workflow
1. Cleaned CSV files in Excel.  
2. Imported all datasets into **PostgreSQL**.  
3. Combined into one master table `"Sales Data"` using SQL.  
4. Executed SQL queries for:
   - Country-wise revenue & profit.  
   - Top 5 products.  
   - Top 5 sales reps.  
   - Store-level performance.  
   - Aggregate sales statistics.  
5. Imported cleaned data into **Power BI**.  
6. Built **interactive dashboards** with KPIs, charts, filters and time-series analysis.

7. ## 📊 Dashboard Highlights
- **KPIs:** Total Revenue, Profit, Units Sold.  
- **Country Comparison:** Revenue & Profit by country.  
- **Top Performers:** Best categories, stores, and sales reps.
- **Time-Series Analysis:** Revenue & Profit trends.
- **Customer Insights:** Payment method distribution.

🔗 **View Dashboard**: [Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYmViYjgxZjktYzZmMi00NzQ0LWE1OTAtOWI4YzM1NTIwYzlhIiwidCI6ImYyN2Y5NWZjLTFmNjEtNGZiYy1hN2UzLTliMzYwODc0MTUyNiJ9)

## 🚀 Outcomes
- Unified **global sales data** into one analytics solution.  
- Identified **top revenue-generating countries & products**.  
- Enabled **data-driven decisions** for sales strategy and inventory planning.

## Global Retail Dashboard Visuals
<img width="1570" height="823" alt="Screenshot 2025-10-01 114859" src="https://github.com/user-attachments/assets/2dc7b3cc-ae71-40ad-8c3f-a9e6b4986c75" />


