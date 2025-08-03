# Data-Analysis-using-Power-bi
# 🧭 Adventure Works Sales Dashboard Project
# 🔍 Project Overview
This Power BI project analyzes the Adventure Works sales dataset to provide actionable insights for executives, sales teams, and marketers. The dashboard focuses on sales performance, product returns, customer demographics, and regional sales distribution. It utilizes data modeling best practices (Star and Snowflake schema) and advanced Power BI features like drillthrough pages, tooltips, DAX measures, and trend analysis.

# 🛠 Tools & Technologies
Power BI Desktop

DAX (Data Analysis Expressions)

Adventure Works Dataset

Star & Snowflake Schema Modeling

Power BI Map & Visuals

# 🗂 Data Sources & Preparation
Used Adventure Works dataset (Sales, Customers, Territories, Products, etc.)

Cleaned data using Power Query:

Removed nulls and duplicates

Standardized column names and formats

Established Star and Snowflake schemas to organize relationships:

Central Fact Tables: Sales, Returns

Dimension Tables: Customer, Product, Region, Date, etc.

# 📊 Dashboard Pages Overview
# 1️⃣ Executive Dashboard
# KPIs (Card Visuals):

Total Revenue

Total Quantity Sold

Total Customers

Return Rate (%)

Visuals:

Sales Trendline: Monthly revenue using a Line Chart

Top 10 Products Matrix: Quantity sold, revenue, return rate

Monthly Comparison Cards: Current month revenue, quantity, return rate

Bar Chart: Total orders by product category

Tooltip Page: Shows quick insights when hovering

Drillthrough Page (Top Products): Product-wise sales details and pricing impact on profit

![Adventure Works Executive Dashboard](Adventure%20Works%20project/Adventure%20Works%20excutive%20dashboard.png)


# 2️⃣ Territory Analysis
Map Visual: Shows sales revenue by geographic location (countries)

Bar/Column Charts: Compare total revenue by country and region

![Territory Analysis](Adventure%20Works%20project/Teritory%20Analysis.png)


# 3️⃣ Customer Analysis
KPIs:

Total Customers

Average Turnover per Customer

Breakdowns:

Customer Income Group

Customer Profession

Trendline Chart: Monthly new customer growth

Top Customers: Highest contributing individuals

![Customer Analysis](Adventure%20Works%20project/custormer%20Analysis.png)


# 4️⃣ Time-Based Performance Page
Running Totals and Averages:

Yearly, Monthly, and 3-Month Intervals

![Running Total](Adventure%20Works%20project/Running%20total.png)


Line and Column Charts

# 🔁 Drillthrough & Tooltip Pages
Product Analysis Page (Drillthrough):

View detailed sales and profit impact for each selected product from other visuals

Dynamic filters based on user selection

![Product Analysis](Adventure%20Works%20project/Product%20analysis.png)


Tooltip Page:

Compact, quick insights shown when hovering over charts/cards

![Tooltip](Adventure%20Works%20project/tooltip.png)


# 📈 Key Insights
Identified top 10 high-performing products by revenue and quantity

Found that return rate was higher in specific product categories

Observed steady revenue growth in key territories

Profession and income group trends helped understand target customers

Return rate trends and individual product profit margin insights support better pricing decisions

# 🎯 Business Impact
Helped stakeholders quickly grasp overall performance through the executive view

Provided granular insights for product managers and sales strategists

Enabled data-driven decision-making on pricing, customer targeting, and territory focus

# 📈 Cohort Analysis Dashboard
# 🔍 Project Overview
This Power BI project focuses on Cohort Analysis to track customer retention, churn, and recovery over time. The dashboard helps stakeholders identify behavioral trends, evaluate retention strategies, and assess churn risks. Cohort analysis groups customers based on their first purchase month and tracks their performance across future months.

# 🛠 Tools & Technologies
Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Cohort Modeling Techniques

# 🗂 Data Preparation & Modeling
Grouped customers by their first purchase month to create cohorts

Calculated key metrics using DAX:

Retained Customers

Churned Customers

Recovered Customers

Monthly Retention & Churn Rates

Created a date table and established relationships with sales and customer data for time intelligence



# 📊 Dashboard Sections
# 🧮 Cohort Matrix Table
Displayed customer retention and churn performance over time

Columns: Months after first purchase

Rows: Cohort (Customer start month)

Metrics in matrix:

Retention Rate (%)

Churned Customers

Churn Rate (%)

# 📊 Clustered Bar Chart
Compared the volume of:

New Customers (First-time)

Recovered Customers (Previously churned, now active)

Released Customers (Churned in current month)

# 📈 Monthly Trendline
Line chart comparing:

New Customers

Recovered Customers

Retained Customers

Helps visualize customer lifecycle trends month over month

# 📌 Key Insights
Identified critical churn points where most customers drop off

Recovered customer spikes aligned with specific campaigns or offers

Cohorts with stronger first-month engagement showed higher long-term retention

Seasonal patterns affected customer acquisition and churn behavior

# 🎯 Business Impact
Empowered marketing and CX teams with clear customer retention metrics

Enabled churn prediction modeling and re-engagement strategy planning

Improved ROI by identifying high-value cohorts worth targeting


