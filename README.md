# AdventureWorks Sales Dashboard — Power BI

A multi-page interactive business intelligence dashboard built in Power BI
using the AdventureWorks dataset. Designed to give business stakeholders
a clear view of sales performance, product trends, and customer behaviour
through clean visuals and custom DAX measures.

## Dashboard Pages

### 1. Adventure Dashboard (Main Overview)
- KPI cards: Total Revenue, Total Profit, Total Orders, Return Rate
- KPI tiles: Monthly Revenue vs. previous month, Monthly Profit vs. 
  previous month, Monthly Returned Orders vs. previous month
- Most Ordered Product & Most Returned Product cards
- Revenue Over Time and Profit Over Time line charts
- Orders by Category (donut chart)
- Quantity by Gender breakdown (donut chart)
- Interactive navigation buttons to switch between views

### 2. Product Details
- Total Orders and Returns Over Time (line chart)
- Revenue Target vs. Actual (gauge)
- Profit Target vs. Actual (gauge)
- Geographic sales distribution (map visual)
- Product-level drill-down table

### 3. Customer Details
- Total Sales and Total Returns Over Time (area chart)
- Quantity Sold vs. Quantity Returned by Gender
- Top 5 Customers by Total Orders (treemap)
- Top 5 Customers by Revenue (treemap)
- Customer segmentation by orders (column chart)

## DAX Measures Built
- Revenue, Cost, Profit
- Revenue vs. Previous Month / Profit vs. Previous Month
- Quantity Sold / Quantity Returned / Return Rate
- Returned Orders vs. Previous Month
- Total Orders / Total Customers

## Tools & Techniques
- Power BI Desktop
- DAX (Data Analysis Expressions) for custom measures
- Data modelling across multiple related tables
  (Orders, Customers, Products, Calendar, Territory)
- Time intelligence functions (month-over-month comparisons)
- Custom navigation with action buttons
- Gauge visuals for target tracking
- Map visual for geographic analysis

## Skills Demonstrated
- End-to-end BI report development
- Data modelling and table relationships
- Writing DAX measures including time intelligence
- Dashboard layout and UX design
- Translating business questions into visual insights
