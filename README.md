📌 Project Overview
This project is an interactive Power BI dashboard designed to analyze and visualize sales data across multiple dimensions. It provides deep insights into revenue, profitability, product performance, and regional sales trends. The dashboard is divided into four main pages, each serving a specific analytical purpose, from high-level executive summaries to granular product and salesperson performance.
📊 Dashboard Pages & Features
Page 1: Executive Sales Overview
The primary landing page focuses on high-level Key Performance Indicators (KPIs) and filtering capabilities for dynamic exploration.
Core KPIs: Total Sales (2.3M), Total Order Quantity (38K), and Total Profit (286K).
Trend Analysis: Clustered column chart tracking sales by year (2014-2017) broken down by Category (Technology, Office Supplies, Furniture).
Detailed Data Tables: Two comprehensive matrices providing granular data on total sales, profit, order quantity, and discounts down to the City and specific Order Date levels.
Interactive Slicers: Deep-dive filtering by Category, Sub-Category, Region, and a date range slider.
Page 2: Time Intelligence & Customer Insights
This page leverages time-intelligence metrics to track current momentum and identifies key customer behaviors.
Time Intelligence KPIs: Displays Sales Year-to-Date (YTD), Month-to-Date (MTD), Quarter-to-Date (QTD), and Week-to-Date (WTD).
Customer Analysis: A donut chart highlighting the Top 5 Sales by Customer Name.
Risk Identification: A specialized bar chart tracking "Negative Profit by State" to quickly identify underperforming regions.
Moving Averages: A dual-line chart comparing 4-Week vs. 12-Week Sales by Year to visualize short-term versus long-term momentum.
Page 3: Product & Temporal Trends
Focused on how specific products perform over time and across geographical areas.
Temporal Trends: Line and area charts detailing Sales by Year and Sales by Month to identify seasonal peaks.
Product Performance: Bar and donut charts breaking down Sale by Product Name, Top Selling Product Name, and Order Quantity by Category.
Geospatial Mapping: A map visual displaying Sales by State and City.
Sub-Category Ranking: A table dynamically ranking sub-categories by total sales volume.
Page 4: Profitability & Team Performance
The final page breaks down the efficiency of the sales process, focusing on profit margins and individual contributor metrics.
Category Profitability: A donut chart showing Profit by Category, indicating which sectors yield the highest margins.
Sub-Category Volume: A Pareto-style bar chart detailing Quantity by Sub-Category (Binders, Paper, Furnishings leading).
Salesperson Performance: A dual-line chart evaluating individual team members (Anna, Chuck, Kelly, Cassandra) by comparing their Total Sales against Total Profit.
Regional Breakdown: A choropleth map highlighting Sales by State and Region (Central, East, South, West).
Year-over-Year Matrix: A detailed table comparing yearly performance (2014 vs 2015) by City.
🛠️ Tech Stack & Tools Used
Power BI Desktop: For data modeling, DAX calculations, and interactive visualizations.
Power Query: For data cleaning, transformation, and shaping.
DAX (Data Analysis Expressions): Used for creating custom measures, KPIs, and complex time-intelligence calculations (YTD, MTD, etc.).
💡 Key Learnings & Competencies Demonstrated
Designing user-friendly, multi-page interactive dashboards.
Implementing Time Intelligence DAX functions to track rolling metrics.
Utilizing geospatial data for regional performance mapping.
Creating dynamic slicers and filters for seamless user navigation.
Identifying business risks (e.g., negative profitability regions) through visual highlights.
🚀 How to Use This Dashboard
Download the .pbix file from this repository.
Open it using Power BI Desktop.
Use the global slicers on the left-hand panel of Page 1 to filter by date, region, or product category.
Navigate through Pages 1 to 4 using the left-hand navigation pane to explore different analytical perspectives.
