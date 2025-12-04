# Dominos-Pizza-Sales-Analysis


📊 Dominos Pizza Sales Analysis Dashboard

This project analyzes pizza sales data using SQL and Excel.
I extracted, cleaned, and transformed the dataset using SQL queries and exported the results into Excel to build a visualization-rich dashboard.
The goal was to uncover meaningful patterns in customer behavior, product performance, and revenue trends so the business can make smarter decisions.



 📌 1. Business Problem

The business wanted clear visibility into:

* When customers place the most orders
* Which pizza categories and sizes generate the most revenue
* What products perform poorly
* How to optimize operations and marketing
* How to improve overall order value

To address these questions, I wrote SQL queries to prepare the data and then used Excel to analyze and visualize it in the form of KPIs and charts.



 🧮 2. KPI Requirements

Using SQL, I calculated the key performance indicators required for the dashboard:

* Total Revenue – Total amount generated from all orders
* Total Orders – Count of all orders placed
* Total Pizzas Sold – Quantity of pizzas sold
* Average Order Value (AOV) = Total Revenue ÷ Total Orders
* Average Pizzas Per Order = Total Pizzas Sold ÷ Total Orders

These KPIs give the business a top-level view of performance and customer spending behavior.



 📊 3. Chart Requirements

I designed charts in Excel to visualize essential trends:

* Daily Trend of Orders
* Hourly Trend of Orders
* % of Sales by Pizza Category
* % of Sales by Pizza Size
* Total Pizzas Sold by Category
* Top 5 Best Sellers
* Bottom 5 Worst Sellers



 🔍 4. Insights From My Analysis

Below are the insights I derived after building and reviewing the dashboard.



 💰 Revenue & Order Behavior

* Total Revenue: $817,860
* Total Orders: 21,350
* Total Pizzas Sold: 49,574
* AOV: $38.31
* Avg Pizzas/Order: 2.32

Interpretation:
Customers typically order 2–3 pizzas per purchase, meaning they're already open to larger orders and bundles.

Recommendation:
Introduce pizza-plus-side bundles and checkout upsells to lift AOV beyond $40.



 📅 Daily Trend Insights

* Tuesday to Friday show high ordering activity.
* Friday is the busiest day of the week.
* Sunday shows noticeably lower demand.

Recommendation:

* Push mid-week offers to capitalize on strong demand.
* Launch Friday specials for premium items.
* Use Sunday family deals to stimulate low-demand days.



 ⏰ Hourly Trend Insights

* Lunch peak: 12 PM – 1 PM
* Evening peak: 5 PM – 8 PM (highest traffic)

Recommendation:

* Increase staffing and delivery partner availability during the evening peak.
* Promote lunch combos to boost the midday window.
* Introduce a “Happy Hour” pizza deal from 3–5 PM to grow pre-peak sales.



 🍕 Category Performance

* Classic pizzas lead with the highest sales volume.
* Chicken pizzas are popular but slightly under-optimized.

Recommendation:
Expand Classic variants and modernize Chicken flavors (Peri-Peri, Chipotle, Cajun) to tap into stronger demand.



 📏 Size Preferences

* Large pizzas dominate sales at over 45%.
* Medium and Regular sizes follow.
* XL and XXL contribute very little.

Recommendation:
Focus marketing on Large pizzas.
Reprice or reposition XL/XXL sizes—or remove the XXL size to simplify operations.



 🏆 Top Best Sellers

* Classic Deluxe
* Barbecue Chicken
* Hawaiian
* Pepperoni
* Thai Chicken

Recommendation:
Highlight these best sellers across menus and promotional campaigns. Use them in combo deals since customer trust is already high.



 📉 Worst Sellers

* Brie Carre
* Mediterranean
* Calabrese
* Spinach Supreme
* Soppressata

Recommendation:
Revamp recipes or reposition these items.
If sales remain low, retire the bottom performers to reduce inventory waste.



 🚀 5. My Recommendations 

* Optimize operations for the 5–8 PM evening peak.
* Introduce bundle offers to increase Average Order Value.
* Improve or retire underperforming pizzas.
* Promote Large pizzas as the flagship size.
* Use best sellers for menu placement and customer acquisition.
* Tailor promotions to specific days of the week for maximum impact.



 🛠️ 6. Tech Stack Used

| Component                        Tools                              
 
| Database & Querying          SQL Server           
| Data Cleaning & Aggregation  Null checks, date extraction, CAST-based type conversion, CTEs for readable queries, DISTINCT to prevent duplicates .         
| Analysis                     Excel (Pivot Tables, Calculations) 
| Visualization                Excel Charts & Dashboard Design    
| Version Control              Git & GitHub                       



 🎯 7. What I Learned

* Applying SQL to extract meaningful business metrics
* Creating KPIs from raw transactional data
* Designing dashboards that executives can directly act on
* Converting data into insights and recommendations
* Presenting analysis in a business-friendly, decision-oriented way


