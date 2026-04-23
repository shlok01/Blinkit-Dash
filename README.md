🛒 Blinkit Grocery Sales Analysis Dashboard
A dynamic and interactive Power BI dashboard built to analyze Blinkit's sales performance, customer satisfaction, and inventory distribution — uncovering key insights and optimization opportunities across outlets, item types, and locations.

📋 Short Description / Purpose
The Blinkit Analysis Dashboard is a data-driven Power BI report designed to provide a comprehensive view of grocery sales across Blinkit's outlet network. It evaluates critical KPIs such as total revenue, average sales, item count, and customer ratings — broken down by fat content, item type, outlet size, location, and establishment type. This dashboard is intended for business analysts, retail strategists, and operations teams looking to optimize inventory, outlet performance, and customer satisfaction.

🛠️ Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main platform for report creation and interactive visualizations.
📂 Power Query – Data transformation and cleaning layer for reshaping raw CSV data.
🧠 DAX (Data Analysis Expressions) – Used for calculated KPI measures, dynamic aggregations, and conditional logic.
📝 Data Modeling – Relationships and structured column types established for cross-filtering and drill-down analysis.
📁 File Formats – .csv for source data, .pbix for development, .png for dashboard previews.


📂 Data Source
Source: BlinkIT Grocery Dataset (CSV)
The dataset contains 8,523 records across 10 outlets, covering grocery item sales with the following attributes:
ColumnDescriptionItem Fat ContentLow Fat / RegularItem IdentifierUnique item codeItem TypeCategory (e.g., Fruits, Snacks, Dairy, etc.)Outlet Establishment YearYear the outlet was set upOutlet IdentifierUnique outlet codeOutlet Location TypeTier 1 / Tier 2 / Tier 3 cityOutlet SizeSmall / Medium / HighOutlet TypeGrocery Store / Supermarket Type 1/2/3Item VisibilityShelf visibility scoreItem WeightWeight of itemTotal SalesRevenue generated per item soldRatingCustomer rating for the item downloaded from Kaggle.

✨ Features / Highlights
🔴 Business Problem
Blinkit operates across multiple outlet types, sizes, and city tiers — making it challenging to identify where sales are strong, which item categories underperform, and how customer satisfaction varies. Decision-makers needed a single, unified view to:

Understand how fat content affects purchasing behavior.
Identify top and bottom performing item categories.
Compare sales across outlet types, sizes, and locations.
Evaluate how outlet age correlates with revenue generation.


🎯 Goal of the Dashboard
To deliver a clean, interactive Power BI report that:

Tracks core business KPIs in real time.
Enables filtering and drill-down by outlet and item attributes.
Surfaces actionable insights to support inventory, marketing, and expansion decisions.


📊 Walkthrough of Key Visuals
Key KPIs (Summary Cards)
KPIValue💰 Total Sales$1.20M📈 Average Sales$141📦 Number of Items1,559⭐ Average Rating3.97
1. Total Sales by Fat Content (Donut Chart)
Breaks down revenue between Low Fat and Regular items to reveal customer health preferences and their impact on sales.
2. Total Sales by Item Type (Bar Chart)
Ranks all 16 item categories — including Fruits & Vegetables, Snack Foods, Household, Dairy, and more — by revenue. Helps identify top-selling and underperforming product lines.
3. Fat Content by Outlet for Total Sales (Stacked Bar / Matrix)
Compares fat content sales split across different outlets, with additional KPI breakdowns (Average Sales, Number of Items, Average Rating) per outlet.
4. Total Sales by Outlet Establishment Year (Line / Area Chart)
Evaluates how outlet age influences sales performance — revealing whether newer or older establishments generate more revenue.
5. Sales by Outlet Size (Donut / Pie Chart)
Shows the percentage contribution to total sales from Small, Medium, and High-sized outlets — highlighting which size tier drives the most revenue.
6. Sales by Outlet Location (Funnel / Bar Chart)
Assesses geographic sales distribution across Tier 1, Tier 2, and Tier 3 cities to guide location-based strategy.
7. All Metrics by Outlet Type (Matrix / Table)
A comprehensive breakdown of Total Sales, Average Sales, Number of Items, and Average Rating across all four outlet types: Grocery Store, Supermarket Type 1, Type 2, and Type 3.

💡 Business Impact & Insights

Inventory Optimization: Identifying top-selling item types helps Blinkit prioritize stocking decisions and reduce waste on slow movers.
Outlet Strategy: Sales patterns by outlet size and location type can guide decisions on where to open new outlets or expand existing ones.
Health Trend Analysis: The fat content split reveals consumer preference shifts, informing product assortment and private label decisions.
Customer Experience: Average rating by item and outlet type highlights areas needing quality improvements to boost satisfaction and retention.


📸 Dashboard Preview
Screenshot: (https://github.com/shlok01/Blinkit-Dash/blob/main/blinkit_screenshot.png)
