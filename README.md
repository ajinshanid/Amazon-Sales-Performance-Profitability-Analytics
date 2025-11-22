# Amazon Sales Performance & Profitability Analytics
### Data Analysis Using Python, SQL (Snowflake), and Power BI

## Overview
Analysis shows that revenue is concentrated in major cities, profits rise seasonally, and operations rely heavily on a single logistics provider. With profit margins nearing nearly half of total revenue, the business is positioned to pursue growth in additional regions and product segments.

## 1. Business Objective
The analysis aims to:
- Identify high-performing regions and product categories
- Understand month-over-month profit trends
- Evaluate shipment carrier dependency
- Highlight growth opportunities and operational risks

## 2. Business Questions Answered
- Which cities contribute most to revenue and profit?
- Which product categories drive performance?
- When are profits highest or lowest throughout the year?
- Is the business overly dependent on a single shipment carrier?
- Do financial margins support expansion into additional regions?

## 3. Target Audience
- Sales Managers
- Business Analysts
- Operations and Logistics Teams
- Leadership and Strategy Teams

## 4. Technical Architecture

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

This architecture supports fast querying, flexible filtering, and scalable analytics.

## 5. Key Performance Indicators (KPIs)
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Units Sold

Profit Margin % provides a clearer measure of financial efficiency beyond revenue totals and supports feasibility assessments for expansion.

## 6. Dashboard Structure and Insights

### A) Regional Performance
**Revenue by City (Bar Chart)**  
- Reveals concentration in top cities  
- Action: Focus marketing and inventory efforts in leading regions.

### B) Category Performance
**Revenue by Category (Scatter Plot with Legend)**  
- Compares categories by revenue and volume  
- Action: Target high-value categories with optimized pricing and promotions.

### C) Profitability Over Time
**Monthly Profit Trend (Line Chart)**  
- Shows mid-year profit peak  
- Action: Align promotional and staffing plans with seasonal demand spikes.

### D) Shipment Carrier Dependency
**Units Sold by Shipment Carrier (Donut Chart)**  
- Intelcom handles ~44% of shipments  
- Action: Assess additional carriers to reduce dependency and operational risk.

## 7. Key Insights and Recommended Actions

| Insight | Recommended Action |
|--------|--------------------|
| Revenue concentrated in top cities | Prioritize investment in high-performing regions |
| Electronics and similar categories lead revenue | Use pricing strategies to drive incremental unit sales |
| Profit peaks in July | Plan inventory and promotions around mid-year demand |
| 44% handled by Intelcom | Explore additional carrier partnerships |
| ~49% profit margin | Expansion into mid-tier regions is financially viable |


## 8. Skills Demonstrated
- Data cleaning and preparation (Python, Pandas)
- SQL-based analytical querying (Snowflake)
- Dimensional modeling and star schema design
- KPI development and performance measurement
- Dashboard design and visualization (Power BI, DAX)
- Trend and profitability analysis
- Business-focused recommendations and storytelling

## 9. Summary
The analysis delivers a clear view of sales performance, profitability patterns, and carrier dependency, turning raw data into insights that inform regional focus, product strategy, and operational planning. It reflects strong analytical thinking and the ability to translate data into business decisions.
