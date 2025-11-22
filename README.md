# Amazon Sales Performance & Profitability Analytics
### Data Analysis Using Python, SQL (Snowflake), and Power BI

## 1. Business Objective
This project provides a structured analysis of Amazon sales data to help sales and operations teams understand:
- Which regions generate the highest revenue and profit
- Which product categories contribute most to performance
- How profitability shifts over time
- How shipment volume is distributed across carriers

The dashboard supports data-driven decisions related to marketing, inventory management, and logistics planning.

## 2. Target Audience
This analysis is intended for:
- Sales Managers
- Business Analysts
- Operations and Logistics Teams
- Leadership and Strategy Teams

## 3. Key Performance Indicators (KPIs)
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Units Sold

Profit Margin % is included to evaluate financial efficiency, not just revenue volume.

## 4. Dashboard Structure and Insights

### A) Regional Performance
**Revenue by City (Bar Chart)**  
- Highlights top-revenue cities and regional demand patterns  
- Recommended Action: Prioritize marketing and inventory investments in high-demand regions.

### B) Category Performance
**Revenue by Category (Scatter Plot with Legend)**  
- Compares product categories by revenue and volume  
- Recommended Action: Apply targeted pricing and promotional strategies to high-value categories.

### C) Profitability Over Time
**Monthly Profit Trend (Line Chart)**  
- Shows month-to-month profit changes  
- Recommended Action: Align promotional activities and resource planning with seasonal demand peaks.

### D) Shipment Carrier Dependency
**Units Sold by Shipment Carrier (Donut Chart)**  
- Shows carrier volume distribution; Intelcom accounts for ~44% of shipments  
- Recommended Action: Evaluate secondary carriers to reduce operational dependency risks.

## 5. Key Insights and Recommended Actions

| Insight | Recommended Action |
|--------|--------------------|
| Revenue concentrated in top cities | Focus marketing and inventory allocation in high-performing regions |
| Electronics and similar categories lead revenue | Optimize pricing to drive incremental unit sales |
| Profit peaks in July | Plan inventory and promotions around mid-year demand |
| 44% shipments managed by Intelcom | Explore additional carrier partnerships |
| Strong overall profit margin % | Consider expanding into mid-tier cities with controlled cost impact |

## 6. Technical Architecture

Raw CSV  
→ Python (Pandas): Data cleaning and formatting  
→ Snowflake: Star schema (1 fact, 5 dimensions) and SQL-based analysis  
→ Power BI: DAX measures and dashboard visualization  

### Star Schema Components
- FACT_SALES
- DIM_PRODUCT
- DIM_LOCATION
- DIM_MANAGER
- DIM_CARRIER
- DIM_DATE

## 7. Tools and Skills Demonstrated
- Power BI: KPI reporting, DAX, dashboard development
- SQL (Snowflake): Analytical querying and dimensional modeling
- Python (Pandas): Data preparation and cleaning
- Data Analysis: Trend analysis, insight generation, business storytelling

## 8. Summary
This project demonstrates how raw sales data can be transformed into clear, actionable business insights through modern analytics tools. It highlights capabilities in data analysis, KPI reporting, visualization, and business-focused storytelling.
