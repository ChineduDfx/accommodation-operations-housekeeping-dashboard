# Accommodation Operations & Housekeeping Performance Dashboard

## Project Overview

This project analyses accommodation operations and housekeeping performance using a synthetic dataset covering 2025. The objective is to demonstrate how spreadsheet-based data analysis can help operational teams monitor occupancy, housekeeping productivity, room completion delays and cleaning quality.

The project uses Microsoft Excel to calculate key performance indicators (KPIs), summarise monthly performance and present findings through a dashboard.

**Data disclaimer:** All data used in this project is synthetic and does not represent a real hotel, its employees, guests or operational performance.

## Business Questions

The analysis explores the following questions:

1. How did occupancy rates vary throughout 2025?
2. How did housekeeping productivity change by month?
3. Which months recorded the highest and lowest late-room rates?
4. How consistently did rooms pass their first inspection?
5. What operational areas could benefit from further investigation?

## Tools and Techniques

- Microsoft Excel
- Excel Tables and structured references
- Formulas and calculated KPI columns
- PivotTables and PivotCharts
- Percentage and numerical formatting
- Monthly performance analysis
- Dashboard design and data visualisation
- Business interpretation and recommendations

## Dataset

The synthetic workbook contains:

- **Daily_Operations:** 365 daily records covering 2025, including occupancy, room cleaning, inspections, housekeeping hours, late rooms, maintenance delays and guest complaints.
- **Cleaning_Tasks:** 900 synthetic cleaning-task records.
- **Data_Dictionary:** KPI definitions and calculation notes.
- **Read_Me:** Project context, analytical questions and data limitations.

## KPI Methodology

The dashboard reports four principal KPIs.

| KPI | Calculation |
|---|---|
| Annual occupancy rate | Total rooms occupied ÷ total rooms available |
| Housekeeping productivity | Total rooms cleaned ÷ total housekeeping labour-hours |
| Annual late-room rate | Total late rooms ÷ total rooms cleaned |
| First-pass inspection rate | Total rooms passed at first inspection ÷ total rooms inspected |

Monthly rates are calculated from the relevant monthly totals rather than by simply averaging daily percentages. This approach accounts for differences in daily volumes.

Housekeeping productivity is expressed as rooms cleaned per labour-hour.

## Key Findings

### Occupancy
- Highest month: March, 78.15%.
- Lowest month: November, 64.50%.

### Housekeeping Productivity
- Highest month: March, 1.32 rooms per labour-hour.
- Lowest month: November, 1.13 rooms per labour-hour.

### Late-Room Rate
- Highest month: July, 5.11%.
- Lowest month: February, 3.75%.

### First-Pass Inspection Rate
- Highest month: March, 94.86%.
- Lowest month: November, 92.60%.

### Annual KPI Summary

| KPI | Annual result |
|---|---:|
| Occupancy rate | 70.01% |
| Rooms per labour-hour | 1.22 |
| Late-room rate | 4.43% |
| First-pass inspection rate | 93.59% |

## Recommendations

- **Occupancy planning:** Investigate monthly demand patterns and room availability to support staffing and housekeeping planning.
- **Productivity:** Examine differences in workloads, room types, staffing and operational delays between higher- and lower-productivity months.
- **Late-room management:** Investigate daily records, checkout volumes, staffing and maintenance delays during months with higher late-room rates.
- **Cleaning quality:** Review inspection failures and rework patterns to identify potential opportunities to improve first-pass performance.

These are recommendations for further investigation. The synthetic data identifies patterns but does not establish their causes.

## Dashboard Preview

## Dashboard Preview

### 1. Dashboard Overview
![Dashboard overview showing KPI cards](screenshots/01-dashboard-overview.png)

### 2. Monthly Performance Charts
![Monthly accommodation performance charts](screenshots/02-performance-charts.png)

### 3. Key Findings and Recommendations
![Key findings and operational recommendations](screenshots/03-key-findings.png)


## Limitations

- The dataset is synthetic and intended for learning and portfolio demonstration.
- Observed patterns cannot be generalised to real accommodation businesses.
- Monthly comparisons identify differences but do not establish causation.
- The project currently demonstrates Excel-based analysis and visualisation; it does not claim to include a Power BI implementation.

## Future Improvements

- Rebuild the dashboard in Power BI.
- Use Power Query for data preparation.
- Create DAX measures for the principal KPIs.
- Add interactive filters and drill-down analysis.
- Extend the analysis to investigate relationships between occupancy, workload, delays and inspection outcomes.

## Project Status

**Completed:** Excel KPI calculations, monthly validation tables, dashboard visualisations and operational recommendations.

**Planned:** Power BI dashboard and further analytical exploration.
