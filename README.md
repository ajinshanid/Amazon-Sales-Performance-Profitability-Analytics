# Amazon Sales Performance & Profitability Analytics  
### Data Analysis Using Python, SQL (Snowflake), and Power BI

---

## Business Objective

Deliver a dashboard that **empowers Amazon sales and strategy teams** to:
- Pinpoint where and why revenue, profit, and margin shift across provinces and categories
- Plan ahead for seasonal changes using data-driven forecasting
- Reduce risk and optimize logistics by understanding shipment carrier dependencies
- Enable actionable decisions on investment, inventory, staffing, and promotions

---

## Target Audience & Value

**Audience:**
- Sales Managers: Prioritize growth strategies and promotions using region and category insights
- Business/Data Analysts: Spot patterns and communicate findings using robust KPIs and forecasts
- Operations & Logistics: Monitor carrier concentration, mitigate delivery risks

**Value:**  
- Vertically aligned KPIs provide an immediate view of commercial performance.
- Profit trend and forecast visuals inform forward-looking planning for stock and resourcing
- A structured layout guides high‑level results to detailed operational insights.

---

## Technical Architecture

**Workflow:**
1. **Data Sources:** Import a synthetic Amazon‑style sales dataset created by combining and reshaping multiple public e‑commerce samples
2. **Python (Pandas):** Clean, standardize, and enrich all records
3. **Snowflake:** Created star schema consisting of Fact table and dimensions for Date, Product, City, Manager and Carrier
4. **Power BI:**  
   - Direct Snowflake connector for live dashboards
   - DAX-calculated KPIs (Revenue, Cost, Profit, Profit Margin %)
   - Visual and time series forecasting
   - Slicers/filters for province, category, shipment carrier, month, and year

---

## Dashboard Structure

**Logical Visual Flow for Storytelling:**
- **KPI Cards (first column, top-to-bottom):** Revenue → Cost → Profit → Profit Margin % → Units Sold (vertically aligned)
- **Top Row:**  
  - **Revenue by Provence(Bar Chart):** Highlights the provinces contributing the highest share of revenue
  - **Category Price and Cost Distribution (Scatter Plot):** Plots categories by average price and cost to separate high‑margin from underperforming segments.
- **Bottom Row:**  
  - **Profit Trend and Forecast (Line Chart):** Shows monthly profit history and projected values.
  - **Units Sold by Shipment Carrier (Donut Chart):** Displays volume share by carrier to quickly assess logistics.

---

## Key Insights and Recommended Actions

| Findings                                    | Recommended Actions                                              |
|---------------------------------------------|------------------------------------------------------------------|
| Quebec and Ontario generate revenue comparable to several mid-tier provinces combined, underscoring a significant regional sales concentration.| Expand digital marketing and supply in leading regions          |
| Beauty & Personal Care has the highest margin, while Grocery has the highest price but a relatively smaller margin.|Focus growth efforts on high‑margin categories like Beauty & Personal Care through prioritized assortment and targeted promotions.|
|Revenue peaks sharply in early 2024, stabilizes, and is forecasted to grow moderately through 2026. | Align promotional campaigns, staffing, and stock to forecasted demand |
| Majority shipments via Intelcom (44%)       | Diversify carriers to reduce operational risk and negotiate better terms |
| Profit margin is over one-quarter of total revenue | Set target margin, monitor cost-by-city, and validate expansion feasibility |

---

## Summary

The dashboard and supporting analytics pipeline are purpose-built for business impact. Insights are presented in a clear, visually aligned format that ensures quick comprehension and drives targeted action. Forecasting capabilities, transparent KPIs, and a logically structured layout combine to make this solution a powerful asset for managers and executives, assisting smarter decisions from everyday operations to long-term strategic planning.

