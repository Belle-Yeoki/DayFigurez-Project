## SIP AND SCALE BUSINESS PERFORMANCE
![](Sip&Scale.png)

## INTRODUCTION
This report analyzes business data focusing on customer behavior, product performance, store targets, and salesperson efficiency using Power BI. The project involved building interactive dashboards that provide key insights to guide business strategy. This analysis leveraged five distinct data tables: Customer, Salesperson, Product, Fact, and Date, with a focus on creating a model that can drive business decisions through actionable insights.

## PROBLEM STATEMENT
The business faced challenges in identifying key drivers of profitability, understanding customer demographics, optimizing store performance, and aligning sales strategies with revenue targets. The objective of this analysis was to:

Assess revenue generation across customer segments.
Identify top and non-profitable products.
Understand store performance in relation to revenue targets.
Determine the effectiveness of salespersons and revenue generation patterns across time (weekdays vs. weekends).
By analyzing these areas, we aim to offer recommendations to improve operational efficiency, enhance profitability, and better align business goals with performance.

## SKILLS DEMONSTRATED
In this project, the following skills were applied:

Data Modeling: Structured the relationship between tables in Power BI, linking Customer, Salesperson, Product, and Store Target data for cross-analysis.
Data Transformation: Cleaned and prepared raw data using Power BI’s Power Query Editor, handling missing values, and ensuring data consistency for accurate analysis.
Data Visualization: Created intuitive dashboards and charts to present key metrics clearly, such as total revenue, profitability, and product performance.
Critical Thinking & Analytical Approach: Interpreted the data to identify business trends and offer recommendations for strategic improvements.

## DATA SOURCING
The dataset comprised the following tables:

Customer Table: Provides demographic data (age, gender).
Salesperson Table: Contains salesperson details such as ID, shifts, and store assignments.
Product Table: Includes product details like name, category, price, and refund data.
Fact Table: Contains transactional data such as sales amount, cost of goods sold (COGS), and revenue.
Date Table: Captures time-based data for analyzing trends over months, quarters, and weekdays.
The data was collected from the company’s internal transaction records and customer management systems.

## DATA MODELLING AND TRANSFORMATION
![](DimensionalModel(Dim).png)
1[](PowerQueryTables.png)
Data Cleaning: Irrelevant or incomplete data entries were removed or imputed. Categorical variables such as gender and product categories were standardized.
Data Modeling: Relationships were established between the Fact Table and the Customer, Product, Salesperson, and Date tables using foreign keys like customer ID, product ID, and salesperson ID.
Calculations and Measures: Created measures for key performance indicators (KPIs) such as total revenue, profit, refund rates, revenue by gender, and revenue vs. store targets using DAX (Data Analysis Expressions).

## ANALYSIS AND VISUALS
Dashboard 1: Customer and Product Performance
![](CustomerBehaviourDashboard(Dim).png)

Overview of Key Metrics:

Total Revenue: ₦5.45 million from 600 customers.
Profit: ₦2.3 million, with ₦3.15 million in COGS.
Average Revenue per Customer: ₦9,083.
Revenue Distribution:
By Gender:
Male customers contributed 51.7% of total revenue.
Female customers contributed 48.53%.
By Age Group:
26-50 years: ₦2.65M (largest contributor).
51-72 years: ₦2.15M.
19-25 years: ₦643K.
Top-Selling Products:
Begin Brew generated ₦410,819.97, the highest revenue, followed by Over Splash and Side Brew.
Refunded Products:
Pm Fusion led refunds with 428 units returned, highlighting a need to improve product quality or marketing strategy.
Monthly Profit Trends:
Profits grew steadily in August, May, and March, while January and February underperformed, indicating potential seasonal effects.

Dashboard 2: Store Performance & Revenue Targets
![]()
Key Insights:
Total Stores: 10 stores analyzed.
Annual Target: ₦5.3 million.
Revenue Variance: ₦191.8k (monthly variance).
Target % Difference from Revenue: -3.52%.
Store Revenue Insights:
Store with ID 3 had the highest revenue target, yet all stores generated nearly equal revenue. This suggests potential inefficiencies in the target-setting process.
Monthly Target vs Revenue Fluctuations:
The analysis of monthly revenue reveals peaks in months like August, May, and March, while other months failed to meet expectations, suggesting opportunities to optimize performance during off-peak months.

Dashboard 3: Salesperson & Revenue Breakdown
![](SalesPerson AnalysisDashboard(Dim).png)
Salesperson Performance:

Total Salespersons: 10 distinct salespeople working across shifts.
Sales performance was consistent, indicating balanced staffing across the week.
Revenue by Day of the Week:
Weekday Sales: ₦4 million, far higher than weekend sales at ₦1.6 million, suggesting room for growth through weekend promotions.
Quarterly Revenue vs Target Analysis:
Q3 generated the highest revenue of ₦1.38M, exceeding the target of ₦1.33M. All quarters performed consistently, though Q3 was the peak performer.
Payment Method Insights:
Revenue was evenly spread across all payment channels, demonstrating that customers use various payment methods effectively.
Actionable Insights and Recommendations
Boost Weekend Sales:

Implement weekend promotions to drive sales, as current weekend revenue (₦1.6 million) lags significantly behind weekday revenue (₦4 million).
Review Product Strategy:

High refunds for Pm Fusion suggest the need for a review of product quality or marketing strategy to reduce return rates and improve profitability.
Re-Evaluate Store Targets:

Despite different revenue targets, stores generated similar revenue, indicating that the target-setting process may need adjustment to better reflect store-specific performance.
Capitalize on Seasonal Trends:

With strong revenue growth in August, May, and March, the company should increase marketing efforts and optimize inventory during these peak months.
Improved Forecasting and Goal Setting:

Revenue fluctuations across months suggest the need for more dynamic forecasting and target-setting processes that adapt to market conditions and seasonal trends.
Conclusion
This Power BI-driven analysis provided a comprehensive look at customer demographics, product performance, store efficiency, and sales trends. The insights generated can be directly applied to business strategy, offering clear recommendations for improving sales performance, product profitability, and operational efficiency.

Next Steps:
Implement promotional strategies for weekends, reassess underperforming products, and refine store targets to align with actual performance. These actions will help drive better business outcomes in future quarters.

