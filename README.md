# 🦄 Unicorn Sales Analysis Report (2015–2018)

# 📌 Project Title

Unicorn E-Commerce Sales Performance Analysis (2015–2018)

# 📊 Project Summary

This project analyzes Unicorn’s sales performance (2015–2018) across categories (Furniture, Office Supplies, Technology), customer segments, and regions. The goal was to identify profit drivers, bottlenecks, and inefficiencies.

**Key insights include:**

	•	Technology (50.79% profit) and Office Supplies (42.77%) are the main profit drivers.
	•	Furniture (Tables & Bookcases) caused losses due to ~24% avg. discounts.
	•	West region generated the highest profit ($108K, 37.85% share), while the South region lagged due to 5–8 day shipping delays.
	•	Consumer segment contributed 50% of sales and 46% of profit, with strong repeat purchases.

**Recommendations:** Promote high-margin products, cap discounts at 20%, improve logistics in South (reduce shipping delays by 2 days), and build customer loyalty programs.

**Impact:** By addressing these areas, Unicorn could boost profit by 10–15% next year, while improving customer satisfaction and operational efficiency.

⸻

# 🎯 Goal

To analyze Unicorn’s e-commerce sales data and identify key drivers of negative profit, inefficiencies in discounting and shipping strategies, and provide actionable recommendations to improve overall profitability and customer retention.

⸻

# 🚨 Problem Statement

Between 2015 and 2018, Unicorn experienced profitability challenges despite steady sales growth. Certain products and categories consistently generated negative profit margins, while inefficient shipping methods and aggressive discount policies further reduced revenue. Without corrective measures, Unicorn risks margin erosion, customer dissatisfaction, and long-term competitiveness.

⸻

# 💡 Business Insights & Key Findings

**1. Top-Performing Regions**

	•	West → Highest profit share (37.85%), fastest deliveries (1–7 days), and most orders.
	•	Central → Negative profit in Furniture but most efficient shipping.
	•	South → Longest and most variable shipping times → logistics need improvement.
	•	East/West → Good performance but can reduce delivery variability.

**2. Product Performance**

	•	Technology (50.8%) and Office Supplies (42.8%) drive profits.
	•	Furniture (6.4%) lags due to heavy discounts (avg. 24%) on Tables & Bookcases → negative profits.
	•	Top Products: Canon Copiers, Fellowes Binding Machine, Hon Deluxe Chairs.

**3. Customer Insights**

	•	Consumer Segment = 50% sales & 46% profit → largest base.
	•	Top Customers:
	•	Tamara Chand (Corporate, +$9K profit),
	•	Sean Miller (Home Office, $25K sales),
	•	Emily Phan (Consumer, 17 repeat orders).
	•	Regional Insight: West leads in Consumer & Corporate profits; South weak in Home Office.

**4. Operational Bottlenecks**

	•	South region suffers long shipping delays (5–8 days) → hurting retention.
	•	West region faster shipping (1–7 days) → boosting sales & satisfaction.
	•	Furniture discounts misaligned with demand → key driver of negative profits.

⸻

# 🌍 Real-World Impact

If addressed effectively, Unicorn can:

	•	Increase net profit by focusing on high-margin products and adjusting discount policies.
	•	Improve customer satisfaction by refining shipping strategies for faster and more cost-effective deliveries.
	•	Strengthen loyalty through data-driven segmentation, ensuring marketing resources target the right customer groups.
	•	Optimize operations and reduce costs, helping Unicorn remain competitive in the growing e-commerce landscape.

⸻

# 🔎 Analysis Process


**1.  Data Preparation**

	•	Imported and cleaned sales data (2015–2018).
	•	Checked missing values, duplicates, and standardization of product categories.
 
**2.	Exploratory Data Analysis (EDA)**

	•	Revenue and profit trends by region, category, and sub-category.
	•	Customer segmentation by purchase frequency and discount sensitivity.
	•	Shipping cost vs. profit analysis.
 
**3.	Business Analysis**

	•	Identified loss-making products and categories.
	•	Evaluated discount patterns and their correlation with profit.
	•	Highlighted shipping bottlenecks and their financial impact.
 
**4.	Recommendations**

	•	Focus marketing on high-margin products like Copiers.
	•	Refine discount strategy by limiting excessive discounts on already popular items.
	•	Optimize logistics in underperforming regions.
	•	Implement customer segmentation for personalized offers and loyalty programs.91

# 🔎 Database Link and SQL queries

1. Unicorn Database access process: postgres:
   
	Use the provided link in the "Import URL" section in Beekeeper to connect to Unicorn Data. Don’t forget to click on Enable SSL toggle before Connect.

	postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Unicorn

2. SQL Queries for business analysis: [Click here](https://docs.google.com/document/d/1HdGKNBeXT8zJ1HxpT-oSyGSVtKK8hEzWZa1ZjDTXE6c/edit?tab=t.0)
 
3. Final dataset: You can find the dataset [here](https://drive.google.com/file/d/1gtp88oCBU1UACYYybjWgB1K55xOg-au4/view?usp=sharing)
  
# 🔎 Google Sheet Analysis

**📊 1. Daily Monitoring Dashboard (Google Sheets)**

**Link for Google Sheet:** [Click here](https://docs.google.com/spreadsheets/d/126F3HeCnNYX5u7FQmS0PWIk2nav5kglyfFxwRCNbq9A/edit?gid=1956504790#gid=1956504790)

In addition to the main analysis, I built a dynamic monitoring dashboard in Google Sheets to help the Unicorn DA team track sales and profit performance by year and region.

	• Regional KPIs: Visualized total sales, profit, and average discount per region using formulas + conditional formatting.
 
	• Category Trends: Monthly sales, profit, and profit margin calculated for each category/sub-category with supporting charts.
 
	• Dynamic Year Filter: A dedicated tab allows users to filter by year, automatically updating all metrics and charts.
 
	• Profit Dashboard:
 
		•Histogram of profit distribution with outlier handling.
		•Line/waterfall chart showing profit trend across months.
		•Top 5 & Bottom 5 profitable subcategories.
		•Top 10 & Bottom 10 customers by profitability.
  
	• Dynamic KPIs included:
 
		•✅ Sum of positive profit
		•❌ Sum of negative profit
		•📦 Number of distinct orders

This Google Sheets dashboard makes it easy for non-technical users to interactively explore profitability trends and identify problem areas in real-time.

**📑 2. Additional Google Sheets Analysis**

**Link for Google Sheet:** [Click here](https://docs.google.com/spreadsheets/d/1AaaG0Gh6HVU84gtUj-r0LKzDfWaEyqkdm7i7oYX6TM8/edit?gid=1131846199#gid=1131846199)

I also performed hands-on business analysis directly in Google Sheets, answering operational and strategic questions using formulas, pivot tables, and conditional formatting.

Key Analyses Performed:

	•	📍 Identified the city with the highest sales and the state with the most profit.
	•	💸 Calculated the average discount across all orders and analyzed shipping costs by order.
	•	👥 Found the most popular product in the Consumer segment and the top customer by number of purchases.
	•	📦 Measured total profit for Office Supplies and the number of orders shipped via Standard Class.
	•	📊 Regional insights: identified which region had the highest June sales.
	•	🧮 Created price per unit (before discount) to find the most expensive product.
	•	🔄 Built pivot tables for manufacturer + category sales (e.g., second highest sales manufacturer in Technology).
	•	🏷️ Classified orders into High / Low / Loss using IFS + conditional formatting.
	•	⏳ Calculated order-to-shipping days per order with a color-scale visualization.
	•	🔽 Added interactive dropdowns (category & product) to dynamically return price per unit.

Outcome:

This sheet-based analysis provided quick operational insights — from identifying loss-making orders and over-discounted products to tracking profitable customers and regions. It also enabled real-time interactive reporting for decision-making without requiring advanced tools.

# 🔎 Visualization and Dashboard in Tableau

I built interactive dashboards in Tableau to analyze Unicorn Sales Data (2015–2018). These dashboards highlight key performance trends, product profitability, customer insights, and operational bottlenecks.

**Tableau public link:** [Click here](https://public.tableau.com/app/profile/thofa.tazkia/viz/UnicornSalesPerformanceProject2015-2018/stateperformance?publish=yes&showOnboarding=true)

## 🔹 Dashboard 1 (Overall Sales & Profit Insights)

![Dashboard 1](dataset/Dashboard1.png)

	•	Displays total sales, profit, number of customers, and orders over years.
	•	Shows profit & sales by category and sub-category, identifying profitable vs. loss-making products.
	•	A map view highlights total sales and profit distribution across U.S. states, uncovering high and low-performing regions.

## 🔹 Dashboard 2 (Operational & Discount Insights)

![Dashboard 2](dataset/Dashboard2.png)

	•	Trend analysis of sales and profit over months.
	•	Discount vs. Profit Ratio scatterplot shows how over-discounting reduces profitability.
	•	Average shipping time analysis across states, highlighting delivery inefficiencies.
	•	Sales & Profit breakdown by region and customer segment, showing which customer groups contribute most to profit.

⸻

**👉 These dashboards provided actionable insights into:**

	•	Promoting high-margin products (e.g., copiers, phones, accessories).
	•	Refining discount strategy to reduce losses in Furniture (Tables & Bookcases).
	•	Optimizing shipping logistics, especially in the South region.
	•	Enhancing customer segmentation to target profitable customer groups effectively.

# 📌 Recommendations for Unicorn to maximize the profit

	1.	Promote High-Margin Products
 
	•	Focus on Technology (50.79% of total profit) and Office Supplies (42.77%), especially in the South region where sales are weaker.
 
	2.	Optimize Discount Strategy
 
	•	Cap discounts for Furniture items at ≤20% (current avg. ≈24%), which could recover ~42% of losses from Tables & Bookcases.
 
	3.	Improve Shipping Efficiency
 
	•	South region has longest delays (5–8 days) vs. Central (3–5 days).
	•	Reducing delays by 2 days could improve customer retention and boost revenue by 10–15% in lagging states.
 
	4.	Customer Segmentation & Loyalty
 
	•	Consumer segment = 50% sales / 46% profit.
	•	Loyalty programs for Corporate & Home Office could lift profits by 5–7% annually.

⸻

# 📌 Conclusion 

By focusing on high-margin categories, reducing over-discounts, and cutting shipping delays (esp. in South), Unicorn can improve net profit by 10–15% next fiscal year. Strengthening customer segmentation and loyalty will further ensure sustained growth and higher retention, maximizing long-term profitability.
