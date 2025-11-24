# Amazon Sales Performance & Profitability Analytics  
### Data Analysis Using Python, SQL (Snowflake), and Power BI

---

## Overview

This project turns Amazon’s raw sales data into **clear, actionable insights** for decision-makers. The dashboard highlights where revenue is strongest, which products and regions deliver the most growth, how profits fluctuate seasonally, and how much operations rely on each shipment carrier. With profit margins near 50%, leaders can confidently pursue growth and optimize business strategy.

---

## 1. Business Objective

Give managers, analysts, and leaders a **practical dashboard** to:
- Find the regions and products making the biggest impact
- Track month-to-month profit and margin trends for smart planning
- Spot risks from shipment carrier dependency and take action
- Pinpoint the best targets for investment and business expansion

---

## 2. Key Business Questions

- Which cities and regions drive the highest sales and profit?
- Which product categories outperform others?
- When do profits peak or dip—and how to respond?
- Are we exposed to risk by depending on a single carrier?
- Do our margins support expansion and investment in new areas?

---

## 3. Target Audience

- **Sales Managers:** Set plans and budgets based on the dashboard’s hottest regions and products
- **Business Analysts:** Spot patterns, challenges, and opportunities in the data
- **Operations & Logistics:** Manage carrier mix, plan for resilience, and optimize shipping
- **Executive Leadership:** Make investment and growth decisions using clear, reliable KPIs

---

## 4. Technical Architecture

**Data Pipeline:**
1. **Raw CSV:** Source files
2. **Python (Pandas):** Cleans and prepares the data for analysis
3. **Snowflake:** Stores the data in a star schema—1 fact table, 5 dimensions for rapid analytics
4. **Power BI:** Connects to Snowflake, calculates KPIs, and enables interactive dashboard reporting

**Star Schema Model:**
- `FACT_SALES` (transactions, revenue, cost, profit)
- `DIM_PRODUCT` (category/type)
- `DIM_LOCATION` (city/province)
- `DIM_MANAGER` (warehouse manager/contact)
- `DIM_CARRIER` (shipment provider)
- `DIM_DATE` (calendar/time intelligence)

Built for fast filtering, deep analysis, and future scalability.

---

## 5. Key Performance Indicators (KPIs)

- **Total Revenue**
- **Total Cost**
- **Total Profit**
- **Profit Margin %**
- **Units Sold**

**Profit Margin %** is key: it puts efficiency and expansion potential front and center for any strategy conversation.

---

## 6. Dashboard Structure & Strategic Insights

- **Revenue by City (Bar Chart):**
  - *Shows:* Top revenue regions
  - *Use it to:* Focus marketing, inventory, and growth strategies on these cities

- **Product Category Performance (Scatter Plot):**
  - *Shows:* Category revenue versus volume
  - *Use it to:* Optimize product mix and pricing for top sellers

- **Profit Trends Over Time (Line Chart):**
  - *Shows:* Monthly profit and margin movements, identifying peak seasons
  - *Use it to:* Schedule promotions, hiring, and inventory to match demand

- **Shipment Carrier Dependency (Donut Chart):**
  - *Shows:* Reliance on dominant carriers (like Intelcom at 44%)
  - *Use it to:* Diversify partners and renegotiate contracts to protect against risk

---

## 7. Key Insights & Recommended Actions

| Insight                                   | Action to Take                                               |
|--------------------------------------------|--------------------------------------------------------------|
| Revenue concentrated in top cities         | Invest more in leaders; test expansion in promising markets  |
| Electronics & key categories are dominant  | Promote and optimize pricing for top profit segments         |
| Profit peaks in July                       | Align staff, inventory, and campaigns for seasonal highs     |
| High dependency on Intelcom (44%)          | Build relationships with more carriers for resilience        |
| Profit Margin ~49%                         | Confidently expand to new regions, use as a benchmark        |

---

## 8. Skills Demonstrated

- Data cleaning and preparation (Python, Pandas)
- Advanced SQL analytics & star schema design (Snowflake)
- KPI calculation, time series, and trend analysis
- Dashboard design & visualization (Power BI, DAX)
- Ability to turn raw data into practical, business-focused recommendations

---

## 9. Summary

The dashboard connects every chart and KPI with actionable business decisions: from investing in the right city and products, to managing logistics risk, to planning for seasonal sales surges. It’s built for clarity, speed, and strategic analytics accessible to every audience, from analyst to executive.

---


