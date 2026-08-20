# VexarDrive Fleet Analytics Dashboard

## Overview

This project analyzes one week of delivery fleet operations using trip data and mobile sensor readings from VexarDrive Technologies. The goal was to identify safer and riskier driving behaviour across drivers and estimate vehicle health using telemetry data such as speed, acceleration, and gyroscope readings.

The solution was built using Excel for data preparation and Power BI for interactive dashboard development.

## Dashboard 1 – Driver Behaviour

This dashboard evaluates the riding behaviour of all 30 drivers by combining trip data with sensor events.

**Key metrics included:**
- Total Trips
- Average Trip Speed
- Total Overspeed Events
- Driver Safety Score
- Driver Safety Category (Safe, Moderate, Risky)

The Driver Safety Score was calculated using weighted penalties for overspeeding, harsh braking, harsh acceleration, and sharp turning.

## Dashboard 2 – Vehicle Health Status

This dashboard estimates the relative health of each vehicle by combining sensor-derived vibration, gyroscope instability, vehicle age, and odometer readings.

**Key metrics included:**
- Average Health Score
- Average Vibration
- Average Gyro Instability
- Vehicle Health Score Ranking
- Maintenance Status (Healthy, Monitor, Needs Maintenance)

The Vehicle Health Score helps prioritize vehicles that may require inspection or maintenance.

## Dataset Summary

| Metric | Value |
|--------|------:|
| Drivers | 30 |
| Vehicles | 30 |
| Trips | 450 |
| Telemetry Records | 12,987 |

## Tools Used

- Excel
- Power BI
- Power Query
- DAX

## Project Structure

```text
VexarDrive-Fleet-Analytics/
│
├── README.md
├── Report.pdf
├── VexarDrive_Dashboard.pbix
└── dashboard_images/
    ├── Driver_Behaviour_Dashboard.png
    └── Vehicle_Health_Status_Dashboard.png
```

## Key Outcomes

- Analyzed 450 trips across 30 drivers and 30 vehicles.
- Created a Driver Safety Score using driving behaviour events.
- Developed a Vehicle Health Score using telemetry-derived indicators.
- Built interactive Power BI dashboards with KPIs, rankings, filters, and summary tables.
- Documented the methodology, assumptions, and business insights behind each dashboard.
