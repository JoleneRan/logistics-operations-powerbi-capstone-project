# Logistics Operations & Performance Dashboard

A Power BI capstone project analyzing logistics operations across revenue, fleet utilization, delivery performance, maintenance, downtime, and safety.

## Project Overview

This project transforms a multi-table logistics operations database into an interactive Power BI dashboard suite designed to help operations teams monitor performance and identify operational trends.

The analysis covers **2022–2024** and combines operational, financial, fleet, delivery, and safety data into four focused dashboards.

## Dashboard Suite

### 01 — Executive Overview

Provides a high-level view of financial and commercial performance.

- Total Revenue
- Total Loads
- Revenue per Load
- Fuel Surcharge
- Accessorial Charges
- Revenue trend over time
- Top 10 customers by revenue
- Revenue by customer type

### 02 — Operations & Fleet Performance

Focuses on fleet activity, utilization, maintenance, and downtime.

- Total Trip Miles
- Total Trips
- Average Trip Miles
- Average MPG
- Trip volume trend
- Fleet utilization trend
- Monthly maintenance cost
- Monthly fleet downtime

### 03 — Delivery Performance

Evaluates service reliability and delivery-event performance.

- On-Time Deliveries
- Total Delivery Events
- On-Time Delivery Rate
- Average Detention Time
- On-time delivery trend
- Average detention by event type
- Delivery events by type

### 04 — Safety & Driver Performance

Provides visibility into safety incidents and their operational impact.

- Total Safety Incidents
- Preventable Incidents
- Injury Incidents
- Safety incident trend
- Safety incidents by type
- Vehicle damage cost by incident type

## Dashboard Preview

![Dashboard Preview](screenshots/dashboard-preview.png)

## Key KPIs

| KPI | Result |
|---|---:|
| Total Revenue | $262.5M |
| Total Loads | 85.4K |
| Revenue per Load | ~$3,075 |
| Total Trip Miles | 122.2M |
| Total Trips | 85.4K |
| Average Trip Miles | 1,430 |
| Average MPG | 6.50 |
| On-Time Delivery Rate | 55.7% |
| Average Detention Time | 92 min |
| Total Safety Incidents | 170 |
| Preventable Incidents | 64 |
| Injury Incidents | 33 |

## Data Model & DAX

The Power BI model contains operational tables covering:

- Customers
- Loads
- Trips
- Drivers
- Trucks
- Trailers
- Facilities
- Routes
- Delivery Events
- Fuel Purchases
- Maintenance Records
- Safety Incidents
- Fleet Utilization Metrics
- Driver Monthly Metrics
- Date dimension

A dedicated DateTable supports time-based analysis and chronological reporting.

Key DAX measures include:

- Total Revenue
- Total Loads
- Revenue per Load
- Total Fuel Surcharge
- Total Accessorial Charges
- Total Trip Miles
- Total Trips
- Average Trip Miles
- Average Utilization Rate
- Average MPG
- Total Maintenance Cost
- Total Downtime Hours
- On-Time Deliveries
- On-Time Delivery Rate
- Average Detention Minutes
- Total Safety Incidents
- Preventable Incidents
- Injury Incidents
- Cargo Damage Cost
- Vehicle Damage Cost

## Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX**
- **Microsoft Excel**
- Data modelling and relationship design
- Time-series analysis
- KPI reporting
- Interactive dashboard design

## Project Structure

```text
logistics-operations-powerbi-capstone-project/
│
├── README.md
├── Logistics Operations Dashboard.pbix
│
├── screenshots/
│   ├── 01-executive-overview.png
│   ├── 02-operations-fleet-performance.png
│   ├── 03-delivery-performance.png
│   ├── 04-safety-driver-performance.png
│   └── dashboard-preview.png
│
├── assets/
│   └── portfolio-cover.png
│
└── .gitignore
```

## How to View the Project

1. Download the `.pbix` file.
2. Open it with **Power BI Desktop**.
3. Use the page tabs to navigate between the four dashboards.
4. Interact with the visuals and filters to explore the underlying analysis.

> Note: Power BI Desktop is required to open and edit the PBIX file.

## Portfolio Highlights

This project demonstrates practical skills in:

- Data modelling
- DAX measure development
- KPI design
- Time-series analysis
- Operational analytics
- Fleet performance analysis
- Delivery performance monitoring
- Safety analytics
- Dashboard UX and visual storytelling

## Author

**Jolene Rankin**

Power BI | Data Analytics | Business Intelligence

---

*Built as a logistics operations analytics capstone and portfolio project.*
