# DATA-ANALYST-INTERNSHIP-TASK-8
Simple Sales Dashboard
======================

Objective:
----------
Build a basic interactive sales dashboard to analyze performance by 
Product Category, Region, and Month, including KPIs like 
Total Sales, Total Quantity, and Total Profit. 
Data was cleaned in Jupyter Notebook using Python (Pandas) before loading into Power BI.

Dataset:
--------
- Superstore_Sales.csv (sample data)
- Columns:
  Order Date, Region, Category, Sales, Profit, Quantity

Data Cleaning (Python + Pandas):
--------------------------------
- Removed null values and duplicates
- Converted Order Date to proper datetime format
- Created Month-Year column for trend analysis
- Ensured numeric columns (Sales, Profit, Quantity) were correct datatype
- Exported cleaned dataset as Superstore_Sales_Cleaned.csv

Dashboard Steps in Power BI:
----------------------------
1. Import cleaned data (Superstore_Sales_Cleaned.csv) into Power BI
2. Create KPIs:
   - Total Sales = SUM(Sales)
   - Total Profit = SUM(Profit)
   - Total Quantity = SUM(Quantity)
3. Build visualizations:
   - Line Chart: Sales over Months
   - Bar Chart: Sales by Region
   - Donut Chart: Sales by Category
   - Slicer: Region filter
4. Formatting:
   - Place KPIs at top
   - Apply consistent colors (Green = High, Red = Low)
   - Add insights panel

Dashboard Features:
-------------------
- Cleaned dataset for accurate reporting
- KPI Cards for Sales, Profit, Quantity
- Interactive Region filter
- Monthly Sales trend line
- Sales breakdown by Region & Category
- Insights panel summarizing findings

Key Insights:
-------------
1. West region had the highest sales in Q3, contributing 35% of total revenue.
2. Technology category shows consistent month-over-month growth, while Furniture lags.
3. Sales peaked in November, likely due to holiday promotions.
4. South region underperformed, despite high order volumes, due to lower profit margins.

Deliverables:
-------------
- Cleaned Dataset (Superstore_Sales_Cleaned.csv)
- Jupyter Notebook (DataCleaning.ipynb)
- Power BI Dashboard (PDF/Screenshot)
- Insights.txt or README.txt
