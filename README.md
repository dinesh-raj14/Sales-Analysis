# Sales-Analysis

### Project Overview

This  project focuses on analyzing sales data  for improving business decisions. By integrating multiple datasets, the dashboard provides a comprehensive view of Revenue trends, regional performance, and product analysis

### Data Sources

Calendar Data- This dataset  "MavenMarket_Calendar.csv" file, Contains calendar-related information for date-based analysis.

Products Data - This dataset "MavenMarket_Products.csv" file, Details on products, including categories and pricing.

Regions Data- This dataset "MavenMarket_Regions.csv" file , contains Regional and geographic information for sales distribution analysis.

Stores Data- This dataset "MavenMarket_Stores.csv" file, Includes information about store locations and performance.

Returns Data- This dataset "MavenMarket_Returns.csv" file, Tracks product returns and their reasons.

Customers Data- This dataset "MavenMarket_Customers.csv" file, Contains customer demographics and purchasing behavior.

### Tools

Power Query Editor: For data cleaning and exploration.

DAX (Data Analysis Expressions): For writing measures and calculated columns.

Power BI: For creating dashboards and visualizations.

###  Data cleaning/Preparing

imported csv files into Power Query Editor.

confirmed the datatypes are accurate and cosistency like wholenumber,text,decimalnumbers.

Added  relevant new column in calendar includes,
Start of Week 
Name of Day
Start of Month
Name of Month
Quarter of Year
Year 

Replace the null values into 0 

### Build Relationship

connect the fact tables like transaction data and returns data to dimensions tables.

Established a relationship between them.

### DAX Calculations

Created Measures for ,

Total Transactions

Total Returns

Return rate

Total Profit

Total Revenue 

Total cost

Unique Products

Last Month Revenue/Returns DAX: Last Month Revenue = CALCULATE([Total Revenue],DATEADD('Calendar'[date],-1,MONTH))

Revenue Target

### Dashboard

Developed a Dashboard with following;

created KPI cards for Total revenue,Returns,Transactions,Profit.

Created Matrix Table to show Top 30 Products .

Created a Map visualisation to know region Transactions along with a slicer.

Created a Gauge chart to show Revenue against Target.

Created Barchart to know the Monthly Revenue.

Created KPI for Current Month Revenue & Returns.

Added Bookmark to Clear Filters.

###  Findings

Identified the months/quarters with the highest revenue, showing clear seasonality in sales.

Highlighted regions with lower sales for targeted improvement strategies.

Specific product Brand contribute the most to overall revenue.

Identified product  with frequent returns, pointing to potential quality or satisfaction issues.











