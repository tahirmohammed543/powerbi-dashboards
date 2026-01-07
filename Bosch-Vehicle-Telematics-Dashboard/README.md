# Bosch Vehicle Telematics Performance Dashboard (Power BI)

## 1. Executive Summary
This Power BI dashboard analyses vehicle telematics data to monitor driving behaviour, fuel efficiency, vehicle health, and maintenance patterns. It enables operations and fleet managers to make data-driven decisions that optimise fleet performance, reduce operating costs, and proactively manage vehicle risks.

---

## 2. Business Objectives
- Monitor overall fleet utilisation and driving performance across time.
- Identify vehicles with abnormal engine behaviour or frequent maintenance alerts.
- Track fuel efficiency trends to control fuel consumption and costs.
- Enable proactive maintenance planning and safer driving practices.
- Support year-over-year and month-over-month performance comparison.

---

## 3. Key KPIs & Metrics
- **Average Speed (kmph)** – Overall fleet driving behaviour indicator.
- **Total Trips** – Vehicle utilisation and operational load.
- **Average Driver Score** – Composite indicator of driving quality and safety.
- **Total Distance (km)** – Fleet usage and asset wear indicator.
- **Average Fuel Efficiency (km/L)** – Cost and efficiency metric.
- **Average Engine Temperature (°C)** – Vehicle health and risk monitoring.
- **Maintenance Alert Count** – Reliability and preventive maintenance signal.

---

## 4. Dashboard Features & Insights
### Core Visuals
- **Trend Analysis**:  
  - Average Fuel Efficiency by Month and Year highlights seasonal and yearly variations.
  - Total Trips by Month identifies utilisation peaks and drops.
- **Vehicle-Level Diagnostics**:  
  - Average Engine Temperature by Vehicle ID helps flag overheating risks.
  - Maintenance Alert Count by Vehicle ID identifies high-risk vehicles.
- **Performance Distribution**:  
  - Average Speed by Year (donut chart) enables quick year-over-year comparison.
- **Operational Summary Table**:  
  - Consolidated view of distance, trips, fuel usage, speed, and driver score per vehicle.

### Key Insights
- Certain vehicles consistently show higher engine temperatures and maintenance alerts, indicating candidates for preventive servicing.
- Fuel efficiency fluctuates across months, suggesting impact from driving patterns or operating conditions.
- Average speed and driver scores remain relatively stable across years, indicating controlled driving behaviour with room for incremental improvement.

---

## 5. Data Model & Technical Approach
- **Data Model Structure**
  - Central fact table capturing trip-level telematics data.
  - Dimensions for Date (Year, Month, Quarter) and Vehicle.
- **Relationships**
  - One-to-many relationships between Date and Trip data.
  - One-to-many relationship between Vehicle master and Trip records.
- **DAX Measures**
  - Aggregated KPIs such as Average Speed, Average Fuel Efficiency, Average Driver Score.
  - Time-intelligence measures for year and month-based analysis.
- **Design Approach**
  - KPI cards for executive-level overview.
  - Combination of trend, categorical, and diagnostic visuals for layered analysis.

---

## 6. Tools & Skills Demonstrated
- Power BI Desktop
- DAX (aggregations, averages, time-based calculations)
- Data Modelling & Relationships
- Analytical Dashboard Design
- Business-Oriented KPI Framing
- Performance-focused visual storytelling

---

## 7. Real-World Use Case / Business Impact
In a real fleet or automotive operations environment, this dashboard can:
- Reduce fuel costs by identifying efficiency drops early.
- Improve vehicle uptime through proactive maintenance.
- Enhance driver safety monitoring using driver score trends.
- Support management decisions on vehicle replacement or servicing schedules.

---

## 8. How to Use the Dashboard
1. Use **Quarter slicer** to focus on specific operational periods.
2. Analyse KPI cards for quick fleet health assessment.
3. Drill into vehicle-level visuals to identify outliers.
4. Compare yearly trends to evaluate improvement or degradation.
5. Use the detailed table for operational and maintenance planning.

---

## 9. Portfolio Value (Why This Project Stands Out)
- Demonstrates end-to-end analytical thinking, not just visualisation.
- Strong alignment between KPIs and real operational decisions.
- Shows ability to translate raw telematics data into actionable insights.
- Reflects consultant-grade dashboard design suitable for enterprise use.

---

## 10. Author
**Mohammed Tahir**  
Aspiring Data Analyst | Power BI & Business Intelligence  
LinkedIn & GitHub-ready portfolio project

