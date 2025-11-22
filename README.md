# Amazon Sales Performance & Profitability Analytics
### Data Analysis Using Python, SQL (Snowflake), and Power BI

## 1. Business Objective
The analysis focuses on uncovering:
- Regions generating the highest revenue and profit
- Product categories driving overall performance
- Month-over-month changes in profitability
- Shipment volume distribution across carriers

Insights are intended to support data-driven decisions in marketing, inventory management, and logistics planning.

## 2. Target Audience
Primary users include:
- Sales Managers
- Business Analysts
- Operations and Logistics Teams
- Leadership and Strategy Teams

## 3. Technical Architecture

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

## 4. Key Performance Indicators (KPIs)
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Units Sold

Profit Margin % provides a clearer view of financial efficiency beyond revenue totals.

## 5. Dashboard Structure and Insights

### A) Regional Performance
**Revenue by City (Bar Chart)**  
- Highlights top-revenue cities and demand patterns  
- Action: Prioritize marketing and inventory in high-performing regions.

### B) Category Performance
**Revenue by Category (Scatter Plot with Legend)**  
- Compares product categories by revenue and volume  
- Action: Apply targeted pricing and promotional strategies to high-value categories.

### C) Profitability Over Time
**Monthly Profit Trend (Line Chart)**  
- Shows changes in monthly profit  
- Action: Align promotional and resource planning with seasonal peaks.

### D) Shipment Carrier Dependency
**Units Sold by Shipment Carrier (Donut Chart)**  
- Intelcom accounts for ~44% of shipments  
- Action: Assess alternate carriers to reduce dependency risk.

## 6. Key Insights and Recommended Actions

| Insight | Recommended Action |
|--------|--------------------|
| Revenue concentrated in top cities | Focus marketing and inventory in leading regions |
| Electronics and similar categories lead revenue | Use pricing strategies to drive additional unit sales |
| Profit peaks in July | Align inventory and promotions with mid-year demand |
| 44% handled by Intelcom | Explore additional carrier partnerships |
| Strong profit margin % | Consider expansion into mid-tier cities with controlled risk |

## 7. Skills Demonstrated
- Data cleaning and preparation (Python, Pandas)
- SQL-based analytical querying (Snowflake)
- Dimensional modeling and star schema design
- KPI development and performance measurement
- Dashboard design and visualization (Power BI, DAX)
- Trend analysis and insight generation
- Business-focused recommendations and storytelling

## 8. Summary
The project highlights the transformation of raw sales data into clear, actionable insights using modern analytics tools. It reflects strengths in data analysis, KPI reporting, visualization, and business-oriented decision support.
