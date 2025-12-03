`# Amazon Sales Performance & Profitability Analytics  
### Data Analysis Using Python, SQL (Snowflake), and Power BI

---

## Business Objective

Deliver a dashboard that **empowers Amazon sales and strategy teams** to:
- Pinpoint where and why revenue, profit, and margin shift across cities and categories
- Plan ahead for seasonal changes using data-driven forecasting
- Reduce risk and optimize logistics by understanding shipment carrier dependencies
- Enable actionable decisions on investment, inventory, staffing, and promotions

---

## Target Audience & Value

**Audience:**
- Sales Managers: Prioritize growth strategies and promotions using region/category insights
- Business/Data Analysts: Spot patterns and communicate findings using robust KPIs and forecasts
- Operations & Logistics: Monitor carrier concentration, mitigate delivery risks
- Leadership/Executives: Drive strategic expansion, cost control, and resource planning using predictive analytics

**Value:**  
- Clear, vertically aligned KPIs: Revenue, Cost, Profit, Profit Margin %
- Forecast charts enabling *forward-looking* decisions
- Storytelling layout: All visuals in logical left-to-right, top-to-bottom flow for intuitive navigation and understanding

---

## Technical Architecture

**Workflow:**
1. **Data Sources:** Import sales/order CSVs; gather operational logistics data
2. **Python (Pandas):** Clean, standardize, and enrich all records
3. **Snowflake:** Created star schema consisting of Fact table and dimensions for Date, Product, City, Manager, Carrier
4. **SQL Analytics:** Efficient queries to extract and aggregate KPIs, join dimension tables
5. **Power BI:**  
   - Direct Snowflake connector for live dashboards
   - DAX-calculated KPIs (Revenue, Cost, Profit, Profit Margin %)
   - Visual and time series forecasting
   - Slicers/filters for city, category, shipment carrier, month, and year

---

## Dashboard Structure

**Logical Visual Flow for Storytelling:**
- **KPI Cards (first column, top-to-bottom):** Revenue → Cost → Profit → Profit Margin % → Units Sold (vertically aligned)
- **Top Row:**  
  - **Revenue by City (Bar Chart):** Focused comparison, not timeline. *
  - **Category Price and Cost Distribution (Scatter Plot with Legend):** Compares categories clearly; legend for instant interpretation.
- **Bottom Row:**  
  - **Profit Trend and Forecast (Line Chart):** Monthly profit history + future predictions.
  - **Units Sold by Shipment Carrier (Donut Chart):** Instantly see logistics risk profile.

---

## Strategic Insights & Business Impact

| Finding                                      | Recommended Actions                                              |
|-----------------------------------------------|---------------------------------------------------------------------|
| Top cities concentrate revenue                | Expand digital marketing and supply in leading regions              |
| Electronics/categories outperform others      | Increase promotions, optimize pricing and inventory in these lines  |
| Profit peaks in July, forecast suggests growth| Align promotional campaigns, staffing, and stock to forecasted demand|
| Majority shipments via Intelcom (44%)         | Diversify carriers to reduce operational risk and negotiate better terms |
| Profit Margin represents over one-quarter of total revenue             | Set target margin, monitor cost-by-city, and validate expansion feasibility |

---

## Summary

The dashboard and supporting analytics pipeline are purpose-built for business impact. Insights are presented in a clear, visually aligned format that ensures quick comprehension and drives targeted action. Forecasting capabilities, transparent KPIs, and a logically structured layout combine to make this solution a powerful asset for managers and executives, assisting smarter decisions from everyday operations to long-term strategic planning.

`
