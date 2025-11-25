# Blinkit-Sales-Performance-Dashboard

🛒 Blinkit Sales Performance Dashboard

📊 Project Overview

An interactive Power BI dashboard designed to analyze Blinkit's sales performance, customer satisfaction, and operational efficiency. This project transforms raw transactional data into actionable business insights, enabling data-driven decisions for inventory optimization, outlet expansion strategies, and customer experience enhancement.

🎯 Business Objective

Blinkit needed comprehensive insights into sales drivers across product categories, outlet types, and geographic locations. The challenge was to identify:

Which product categories and outlet configurations generate maximum revenue Geographic performance patterns across location tiers Customer satisfaction trends and improvement opportunities Operational efficiency metrics for strategic planning Goal: Build an interactive dashboard that empowers stakeholders to make informed decisions on inventory management, outlet expansion, and customer satisfaction initiatives.

📁 Dataset Description

Source: Excel workbook Volume: 8,523 rows × 12 columns Coverage: Blinkit transactional data including:

Product Dimensions: Item type, fat content classification Outlet Attributes: Establishment year, size, location tier, outlet type Performance Metrics: Sales revenue, customer ratings, item visibility

🛠Tools & Technologies Power BI Components:

Power Query Editor: Data cleaning and transformation DAX (Data Analysis Expressions): Calculated measures and KPIs Visualizations: Donut charts, bar charts, line charts, funnel charts, matrix tables Interactivity Features: Field parameters, slicers, edit interactions

Key Techniques: Data quality validation and standardization Dynamic metric switching with field parameters Custom DAX calculations for business metrics Cross-filtering configuration for drill-down analysis

🔄 Development Process

Business Analysis Phase
Stakeholder interviews to define requirements KPI identification and metric prioritization

Data Quality Management
Imported Excel dataset into Power BI Quality Issues Addressed:

Standardized inconsistent fat content labels ('LF' → 'Low Fat', 'reg' → 'Regular') Handled 16% missing values in non-critical fields Validated 100% accuracy in dimension attributes

Data Modeling & Calculations
Created DAX measures:

DAX Total Sales = SUM(Sales[Amount]) Average Sales = AVERAGE(Sales[Amount]) Item Count = COUNTROWS(Items) Average Rating = AVERAGE(Ratings[Score]) 4. Dashboard Design

Designed canvas with Blinkit brand colors Implemented KPI cards for at-a-glance metrics Built interactive slicers (Location Tier, Outlet Size, Item Type) Configured cross-filtering behavior between visuals Applied professional formatting and tooltips

💡 Key Insights & Findings

Financial Performance

$1.2M Total Sales Revenue $141 Average Order Value 8,523 Total Items Sold

Customer Satisfaction

3.9/5 Average Rating (indicating improvement opportunities)

Product Analysis

Low-fat products dominate sales volume Top Categories: Fruits & Vegetables, Snack Foods, Household Items

Outlet Performance (Critical Insights)

Medium-sized outlets outperform small and large locations Tier 3 locations generate highest revenue (contradicts conventional Tier 1 assumptions) 2018-established outlets show superior performance metrics Outlet Type Breakdown: Supermarket Type 1 leads in sales contribution

📈 Business Impact

Operational Efficiency

70% reduction in reporting time vs. manual Excel analysis Real-time multi-dimensional sales analysis capabilities Instant identification of underperforming outlets and high-potential categories

Strategic Value

Expansion Strategy: Data supports focusing on medium-sized, Tier 3 outlets Inventory Optimization: Guided by category-wise performance metrics Customer Experience: Rating insights direct satisfaction improvement initiatives Quick Market Response: Dynamic filtering enables rapid decision-making

Stakeholder Benefits

Executive leadership: Strategic planning insights Operations teams: Performance benchmarking Sales teams: Category and location targeting Inventory managers: Stock allocation optimization
