# Namma Yatri – Data Visualisation & Storytelling

## ✅ Objective  
This project focused on analysing **ride demand, cancellations, revenue patterns, and operational inefficiencies** for **Namma Yatri**, a ride-hailing platform operating in Bengaluru. The goal was to generate **actionable insights** using data visualization to support **operational optimization, revenue growth, and improved customer experience**.

---

## 📊 Data Overview  
The analysis was performed on a relational dataset consisting of **5 interlinked tables**:

- **Fact Tables:** Trips, Trip_Details  
- **Dimension Tables:** Assembly (zones), Duration (time), Payment (method)

Key data covered:
- Trip requests → quotes → allotment → completion funnel  
- Fare, distance, time-of-day, pickup zones  
- Driver and customer cancellations  
- Payment method usage  

A **fact constellation schema** was built to ensure accurate aggregation and analysis.

---

## Tools & Techniques  
- **Power BI** – data modelling, dashboards, storytelling  
- **DAX** – KPIs, conversion metrics, cancellation rates  
- **Power Query (M)** – data cleaning, time binning  
- **Visualisation patterns** – heatmaps, funnels, tree maps, KPI cards  

---

## Key Insights  

### Demand & Revenue Patterns
- Peak ride demand occurs during **Forenoon and Afternoon**
- **Midnight (0–1 AM)** and **early morning (6–7 AM)** generate disproportionately high revenue per hour
- ~42% of total revenue is generated during standard business hours (7 AM–5 PM)

### Conversion & Cancellations
- Overall trip conversion rate is **~45%**
- **Cancellation rate ~23%**
- Nearly **46% of pickup zones** exceed the average cancellation rate
- High cancellations observed in zones with **longer distances but low fare/km**

### Zone-Level Insights
- High-performing zones: **Hoskote, Chamrajpet, Mahadevapura**
- Underperforming zones show:
  - High cancellations
  - Lower driver efficiency
  - Poor fare-to-distance economics

### Payment Behaviour
- **Digital payments dominate (~76%)**
- Cash rides form only ~24% of volume but contribute **disproportionately high revenue**, indicating premium or long-distance usage

---

## Key Recommendations  

- **Operational**
  - Optimise driver allocation using zone × time demand patterns
  - Reduce idle time with predictive matching during off-peak hours
  - Monitor high-cancellation zones with targeted interventions

- **Revenue & Growth**
  - Introduce time-based incentives for underutilised but high-fare slots
  - Hyperlocal promotions in high-performing zones
  - Encourage digital payments via targeted cashback campaigns

- **Product & UX**
  - Improve quote-to-ride conversion through A/B testing
  - Reduce wait times to improve completion rates

---
