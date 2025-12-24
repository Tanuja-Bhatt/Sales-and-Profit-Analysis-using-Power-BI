# Sales-Profit-Analysis
<h1> Introduction </h1>

When I began learning Power BI, my understanding of dashboards was limited to building charts and visuals. However, as I progressed through this project, I realized that effective data analytics is not about visuals but it’s about answering business questions and supporting decision-making.

This project is an end-to-end Sales and Profit Analysis dashboard built using the Superstore dataset. What started as a simple sales analytics exercise gradually evolved into a profit-focused business intelligence solution, highlighting how discounts, categories, and regions influence overall profitability.

<h1>Project Objective</h1>

The primary objective of this project was to move beyond descriptive sales reporting and perform analytical evaluation of business performance.

The dashboard aims to answer key business questions such as:

1.How are sales and profit trending over time?

2.Which product categories and sub-categories drive profitability?

3.Which regions contribute the most to revenue and profit?

4.How do discount strategies impact sales and profit margins?

5.Where is profit leakage occurring despite high sales?

<h1>Dataset Overview </h1>

• Dataset Source: Superstore Sales Dataset (Kaggle)[https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales]

• Data Type: Transactional sales data

• Time Period: Multi-year sales history

• Key Features:

       • Order Date, Ship Date

       • Sales, Profit, Discount, Quantity

       • Category, Sub-Category

       • Region, Segment

This dataset is widely used for sales analytics, business intelligence, and profitability analysis, making it ideal for real-world BI practice.

<h1>Data Cleaning & Preparation</h1>

Before building the dashboard, the dataset was cleaned and transformed using Python (Pandas) and Power Query.

<h2>Key data preparation steps:</h2>

• Removed unnecessary identifiers (Row ID, Product ID, Postal Code, Customer ID)

• Checked and removed duplicate records

• Converted date fields to proper datetime formats

• Ensured numeric consistency for sales, profit, and discount fields

• Engineered discount slabs to analyze pricing strategies

• Created a dedicated Date Table to enable accurate time intelligence calculations

This step was critical to ensure data quality, reliability, and analytical correctness.

<h1>Tools & Technologies Used</h1>

• Power BI – Dashboard design, data modeling, and visualization

• DAX (Data Analysis Expressions) – Measures, KPIs, and time intelligence

• Python (Pandas) – Data cleaning and preprocessing

• Power Query – Data transformation

• Kaggle – Dataset source

<h1>Data Modeling & DAX Measures</h1>

A proper star-schema style model was implemented with a separate Date Table, enabling reliable time-based analysis.

<h2>Core Measures Created:</h2>

• Total Sales

• Total Profit

• Profit Margin %

• Sales Year-to-Date (YTD)

• Sales Year-over-Year (YoY) Growth %

<h3>Using explicit DAX measures instead of auto-aggregations ensured:</h3>

• Reusability

• Consistency across visuals

• Accurate filter and slicer behavior

• Correct time intelligence calculations

<h1>Dashboard Design & Key Visuals</h1>

The dashboard follows a top-down storytelling structure:

<h2>🔹 KPI Summary</h2>

Provides a quick snapshot of overall performance using:

• Total Sales

• Total Profit

• Profit Margin %

• Sales YTD

• YoY Growth %

<h2>🔹 Sales & Profit Trend Analysis</h2>

A time-series analysis showing:

• Sales vs Profit trends

• Volatility over time

Situations where sales growth did not translate into profit growth

<h2>🔹 Category & Sub-Category Performance</h2>

• Sales by Category to identify revenue drivers

• Profit by Sub-Category to expose loss-making products

<h2>🔹 Regional Performance Analysis</h2>

• Sales and profit comparison across regions

• Identification of strong and underperforming regions

<h2>🔹 Discount Impact Analysis (Advanced Insight)</h2>

One of the most critical insights from this project:

• Moderate discounts (11–20%) maximize sales

• Higher discounts (>30%) reduce both sales and profit

• High discount levels often indicate low-demand or overstocked products

This analysis highlights profit leakage caused by aggressive discounting.

<h1> Key Business Insights</h1>

• Technology category leads in both sales and profitability

• High sales volumes do not always result in high profit

• Moderate discounts offer the best balance between revenue and margin

• Deep discounts negatively impact long-term profitability

• West region consistently outperforms other regions

• Profit-focused analysis provides more actionable insights than sales-only reporting

<h1> Learnings & Takeaways</h1>

This project helped me understand that:

• Sales analytics alone is incomplete without profit analysis

• Data modeling and measure design are as important as visuals

• Business storytelling is a core skill for data analysts

• Challenging intuitive assumptions (e.g., higher discounts = higher sales) leads to better insights

• Dashboards should guide decisions, not just display numbers


<h1>Future Enhancements</h1>

•Customer-level and order-level analysis

•Advanced tooltips for deeper exploration

•Profit optimization recommendations

•Deployment on Power BI Service

•Integration of forecasting and trend analysis

<h1>Conclusion</h1>

This project represents my journey from learning Power BI as a tool to thinking like a data analyst who solves business problems.
It reflects my growing interest in Data Analytics, Business Intelligence, and decision-driven insights.

Feedback and suggestions are always welcome.😊
