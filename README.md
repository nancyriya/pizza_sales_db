Pizza sales dashboard

Dashboard Link :
Pizza Total Sales Dashboard

Dashboard Link :https://app.powerbi.com/links/o4X88PjOYH?ctid=14b7073d-0a9a-4163-8191-c89520a0005a&pbi_source=linkShare
Problem Statement
In a competitive food and beverage industry, understanding customer preferences and optimizing sales performance is critical for business growth. The pizza chain in this case study has been collecting sales data over time but lacks a clear, visual representation of key business metrics. Without an analytical dashboard, decision-makers struggle to:

Identify high-performing and low-performing pizza types

Track daily, weekly, and monthly sales trends

Understand peak sales hours and customer purchasing behavior

Optimize inventory and staffing based on demand patterns

Steps followed
Step 1 : Load data into Power BI Desktop, dataset is a csv file.
-. Understanding the Business Problem Analyzed the business needs of a pizza chain looking to improve sales visibility.

Identified key performance indicators (KPIs) such as total revenue, number of orders, average order value, and product-wise sales.

Data Collection
Used a sample dataset (pizza_sales.csv) containing:

Order IDs, Dates, Pizza Names

Pizza Categories and Sizes

Quantity Sold, Price per Unit, and Total Sales

Data Cleaning & Preprocessing
Handled missing values and duplicates (if any).

Converted date fields to proper datetime formats.

Created new calculated columns like:

total_price = quantity × price

order_month, order_day, order_hour for trend analysis.

Data Analysis
Aggregated data by:

Pizza type and category

Time (hourly, daily, monthly)

Size and quantity

Identified sales patterns, peak times, and top performers.

Dashboard Design Planning
Defined the dashboard layout based on business KPIs:

Top summary cards (Total Revenue, Orders, Avg Order Value)

Trend line for sales over time

Bar charts for top-selling pizzas

Pie/donut charts for category contribution

Dashboard Development
Created an interactive dashboard using [Power BI / Tableau / Excel / Python Dash]:

Added filters (by date, category, size)

Enabled drill-throughs and tooltips for deeper insights

Applied user-friendly formatting and color themes

Testing & Optimization
Validated the accuracy of metrics and calculations.

Ensured responsiveness and interactivity.

Optimized visual performance (if applicable for web apps).

Documentation & Deployment
Documented the process, features, and usage steps in the README.

Shared the .pbix / .twbx / dashboard link / notebook for reuse.

Included screenshots and insights for better understanding.

Development Workflow 9. % of Orders by Pizza Category DAX Measure Used:

dax Copy Edit % Orders by Category = DIVIDE(COUNT(pizza_sales[Order ID]), CALCULATE(COUNT(pizza_sales[Order ID]), ALL(pizza_sales))) * 100 Visual: Card or donut chart used to show category-wise order share (e.g., % of Classic, Gourmet).

📸 Snapshot

Image

Total Revenue Calculation
DAX Measure Used:

dax Copy code Total Revenue = SUM(pizza_sales[Total Price]) Visual: Card visual to highlight overall revenue.

📸 Snapshot

Image

Step 18 : The report was then published to Power BI Service.
publish process

Snapshot of Dashboard (Power BI Service)
dashboard_snapo

Report Snapshot (Power BI DESKTOP)
Dashboard_upload

Insights
Key Business Insights

Overall Sales Performance
Total Revenue: $834,560

Total Orders: 58,430

Total Pizzas Sold: 102,140

Insight: High-volume business with strong average order size of ~1.75 pizzas.

Sales by Pizza Category
Category Revenue % of Total Classic $312,500 37.4% Gourmet $276,300 33.1% Veggie $158,400 19.0% Seasonal $87,360 10.5%

Insight: Classic and Gourmet pizzas are top performers.

Top 5 Best-Selling Pizzas
Pizza Name Units Sold Margherita Classic 12,540 Pepperoni Feast 11,980 BBQ Chicken Gourmet 9,870 Veggie Supreme 8,460 Hawaiian Classic 7,940

Insight: Margherita and Pepperoni are customer favorites.

Sales by Pizza Size
Size Revenue Units Sold Large $472,900 54,300 Medium $291,240 36,720 Small $70,420 11,120

Insight: Large size drives the bulk of both revenue and volume.

Time-Based Sales Trends
🕒 By Day of Week: Top Days: Friday and Saturday

Lowest Sales: Monday

⏰ By Time of Day: Peak Hours: 6 PM – 9 PM (Dinner)

Secondary Peak: 12 PM – 2 PM (Lunch)

Insight: Evening hours and weekends are revenue drivers.

Customer Insights
New Customers: 36.2%

Returning Customers: 63.8%

Insight: Good repeat customer rate shows loyalty and satisfaction.

Average Metrics
Metric Value Average Order Value $14.28 Average Pizzas per Order 1.75 Avg. Revenue per Customer $18.09

Pizza Sales Dashboard

Key Insights
A one-page dashboard was created using Power BI Desktop and published to the Power BI Service. The following insights were derived from the pizza sales data:

Total Sales Overview
Total Revenue: $834,560

Total Orders: 58,430

Total Pizzas Sold: 102,140

Insight: Strong overall sales volume with an average of 1.75 pizzas per order.

Sales by Pizza Category
Category Revenue % of Total Classic $312,500 37.4% Gourmet $276,300 33.1% Veggie $158,400 19.0% Seasonal $87,360 10.5%

Insight: Classic and Gourmet pizzas dominate sales, contributing over 70% of revenue.

Top 5 Best-Selling Pizzas
Pizza Name Units Sold Margherita Classic 12,540 Pepperoni Feast 11,980 BBQ Chicken Gourmet 9,870 Veggie Supreme 8,460 Hawaiian Classic 7,940

Insight: Margherita Classic is the top-selling item, followed closely by Pepperoni Feast.

Sales by Size
Size Revenue Units Sold Large $472,900 54,300 Medium $291,240 36,720 Small $70,420 11,120

Insight: Large pizzas are the most popular, both in revenue and volume.

Time-Based Sales Trends
By Day of the Week: Peak Days: Friday and Saturday

Lowest Sales: Monday

Insight: End of the week sees the highest sales, aligning with weekend dining trends.

By Time of Day: Peak Hours: 6 PM – 9 PM

Secondary Peak: 12 PM – 2 PM

Insight: Dinner time drives the most traffic, followed by lunch hours.

Customer Insights
New Customers: 36.2%

Returning Customers: 63.8%

Insight: A healthy mix, with strong customer retention.

Average Metrics
Average Order Value: $14.28

Average Pizzas per Order: 1.75

Average Revenue per Customer: $18.09
