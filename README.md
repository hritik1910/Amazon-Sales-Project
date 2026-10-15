# Amazon-Sales-Project
Analyzed Amazon sales data using Python, Pandas, NumPy, Matplotlib, and Seaborn. Performed data cleaning and exploratory analysis to identify trends in product categories, sizes, order status, buyer types, and state-wise sales, generating valuable business insights.

## 2. Short Description / Purpose
Sales Intelligence Dashboard is an interactive analytics project designed to analyze sales and order data to understand sales performance, product demand, order status, fulfilment operations, customer geography, and shipping patterns.
The analysis processes a dataset containing 128K+ sales records, performs data cleaning and transformation using Python, and derives meaningful insights from 37K+ complete records for deeper analysis.
#### Purpose:
To transform raw e-commerce transaction data into actionable insights that help identify top-performing products, demand patterns, high-performing locations, order fulfilment trends, and potential operational issues.

## 3. Tech Stack
**Python**
Pandas — Data loading, cleaning, transformation and analysis
NumPy — Numerical computations and data manipulation
Matplotlib — Data visualization
Seaborn — Statistical and categorical visualizations
Jupyter Notebook — Interactive analysis and documentation

**Data Processing**
Missing-value detection and treatment
Data type conversion
Date-time transformation
Column cleaning and restructuring
Descriptive statistical analysis

## 4. Features / Highlights
🔹 Business Problem
Raw sales data contains thousands of transactions across different products, sizes, locations, order statuses, fulfilment methods and shipping conditions. Without proper analysis, it becomes difficult to understand what is driving sales and where operational improvements are required.

The dataset contains fields such as Order ID, Date, Order Status, Fulfilment, Sales Channel, Category, Size, Courier Status, Qty, Amount, Ship City, Ship State, B2B and Fulfilled-by.
🔹 Key Visuals & Analysis

1. Sales & Order Overview
Analyze overall order volume and sales amount.
Track order activity across the available period.
Identify important sales and transaction patterns.

2. Product Category Performance
Compare performance across product categories.
Identify high-demand categories.
Understand which product segments contribute strongly to order volume.

**The dataset contains 8 product categories, with T-shirt appearing as the most frequent category in the cleaned dataset.**

3. Size-Wise Demand Analysis
Analyze customer demand by product size.
Identify the most frequently ordered sizes.
Useful for inventory and assortment planning.

**The project includes a Seaborn count plot specifically analyzing Size distribution.**

4. Order Status Analysis
Examine delivered, shipped, cancelled and other order statuses.
Identify the proportion of successful versus problematic orders.
Highlight potential areas for operational improvement.

**The cleaned dataset contains 11 distinct order-status values, with “Shipped - Delivered to Buyer” being the most frequent status.**

5. Regional Sales Analysis
Analyze sales/orders by state and city.
Identify high-demand geographical markets.
Support regional sales and distribution decisions.

**The dataset contains 58 states and 4,698 unique cities after cleaning.**

6. Fulfilment & Shipping Analysis
Compare fulfilment-related patterns.
Analyze courier status and shipping service levels.
Identify potential delivery and operational bottlenecks.

7. B2B vs Non-B2B Analysis
Separate business orders from regular customer orders.
Understand the contribution of B2B transactions.
Support targeted business-sales strategies.

**A major strength of the project is the data-preparation workflow:**

Identified missing values across the dataset.
Removed unnecessary columns such as New and PendingS.
Detected 7,800 missing values in both currency and Amount.
Converted postal codes from floating-point to integer.
Converted Date from object to datetime.
Removed incomplete records using dropna().
**This reduced the dataset from 128,976 rows to 37,514 complete records for the cleaned analysis.**

🔹 Business Impact & Insights
Identify high-performing product categories for better inventory allocation.
Understand size-wise demand to improve stock planning.
Identify high-demand states and cities for regional strategies.
Monitor cancelled and delivered orders to evaluate order performance.
Analyze fulfilment and courier patterns to identify operational inefficiencies.
Understand B2B demand and distinguish it from regular consumer orders.
Track sales amount and quantity patterns to support data-driven sales decisions.

## 5. Goal of the Dashboard
To provide a comprehensive view of Amazon.in sales and order performance by transforming raw transaction data into actionable insights across products, customers, geography, fulfilment and order status.


## End of project. 
