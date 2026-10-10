# ITC Hotels: Revenue Performance & Business Intelligence

An interactive Power BI project analyzing hotel revenue, occupancy, booking behavior, and cancellations to identify business trends and opportunities for revenue optimization.

## Project Overview

This project explores hotel booking and revenue data for **May–July 2022** to understand financial performance, room occupancy, customer booking patterns, and cancellation-related revenue.

The dashboard transforms raw data into interactive visualizations and KPIs that help stakeholders compare hotel properties, monitor performance, and identify areas for improvement.

## Business Objectives

- Analyze revenue trends across months, properties, and room categories.
- Evaluate occupancy, Average Daily Rate (ADR), and Revenue per Available Room (RevPAR).
- Understand weekday versus weekend demand and booking lead-time patterns.
- Examine cancellation rates, cancellation charges, and potential unrecovered booking value.
- Provide actionable recommendations to improve revenue performance and operational efficiency.

## Tools & Technologies

- **Power BI Desktop** — interactive dashboards and data visualization
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures and KPI development
- **Data Modeling** — relationships and date-based analysis

## Dashboard Pages

### 1. Executive Summary
Provides an overview of hotel performance through key metrics, revenue trends, occupancy, ADR, RevPAR, and cancellation rate.

### 2. Revenue Performance Analysis
Compares monthly revenue, hotel property performance, and revenue contribution by room category.

### 3. Occupancy & Revenue Efficiency
Evaluates occupancy across properties and tracks revenue efficiency using ADR and RevPAR.

### 4. Booking Behavior & Demand
Analyzes booking lead time, length of stay, and differences between weekday and weekend demand.

### 5. Cancellation & Revenue Leakage
Examines cancellation patterns, cancellation charges, and the estimated portion of cancelled booking value not recovered through those charges.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Revenue | ₹1.71 billion |
| Occupancy Rate | 43.50% |
| Average Daily Rate (ADR) | ₹14.92K |
| Revenue per Available Room (RevPAR) | ₹7.35K |
| Cancellation Rate | 24.83% |
| Average Booking Lead Time | 3.71 days |
| Average Length of Stay | 2.38 days |

*Figures reflect the dashboard calculations for the analyzed period.*

## Key Insights

- **Revenue trend:** Revenue was approximately ₹582M in May, ₹554M in June, and ₹573M in July. June declined by 4.81% month over month, followed by a 3.43% recovery in July.
- **Property performance:** ITC Exotica recorded the highest revenue at approximately ₹320.31M.
- **Room-category contribution:** Elite rooms generated the highest revenue, at approximately ₹560.27M.
- **Weekend demand:** Weekend occupancy was 55.57%, compared with 38.49% on weekdays—a difference of 17.08 percentage points.
- **Booking patterns:** Approximately 85.10% of bookings fell within the 0–5 day lead-time groups, indicating a strong short-lead-time booking pattern.
- **Cancellations:** The cancellation rate was 24.83%, highlighting an opportunity to investigate cancellation drivers and improve booking retention.

## Cancellation Revenue Analysis

The dashboard compares:

- Cancelled booking gross value: approximately ₹497.96M
- Cancellation charges: approximately ₹199.18M
- Estimated unrecovered gross booking value: approximately ₹298.78M

The estimated unrecovered value is calculated as cancelled booking gross value minus cancellation charges. **It is an analytical estimate, not a verified financial loss**, because the calculation does not establish whether cancelled rooms were resold or whether other revenue was recovered.

## Business Recommendations

1. **Improve weekday occupancy:** Test targeted promotions, corporate packages, and weekday offers to address the gap between weekday and weekend demand.
2. **Optimize cancellation policies:** Analyze cancellation timing and booking channels to identify where policy adjustments or reminders could improve retention.
3. **Leverage short-lead-time demand:** Monitor near-term booking trends and use demand-based pricing where appropriate.
4. **Replicate successful property strategies:** Investigate the practices of higher-revenue properties and evaluate their applicability across other hotels.
5. **Monitor performance continuously:** Track revenue, occupancy, ADR, RevPAR, and cancellation rates to support timely decisions.

## Dashboard Features

- Five interactive report pages
- KPI cards and monthly trend analysis
- Property and room-category comparisons
- Booking behavior and cancellation analysis
- Interactive slicers and page-navigation buttons
- Consistent navy, gold, and cream visual theme

## Project Files

The repository include:

- `ITC_Hotels_Dashboard.pbix` — Power BI report file
- `README.md` — project documentation
- `screenshots/` — dashboard page previews
- `ITC_Hotels_Project_Presentation.pptx` — project presentation
- `ITC_Hotels_Project_Documentation.txt` — supporting documentation


## Conclusion

This project demonstrates how Power BI, Power Query, and DAX can turn hotel booking data into an interactive business intelligence solution. It connects revenue performance, occupancy efficiency, booking behavior, and cancellations to practical recommendations for hotel revenue management.

---

**Project Title:** ITC Hotels: Revenue Performance & Business Intelligence  
**Tools:** Power BI | Power Query | DAX  
**Analysis Period:** May–July 2022
