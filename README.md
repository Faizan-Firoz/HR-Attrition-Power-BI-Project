# HR Analytics Dashboard 📊

A Power BI dashboard analyzing employee attrition trends, 
built to help HR teams identify patterns and risk factors behind employee turnover.

## Overview

This project explores an HR dataset of **1,470 employees** to understand where and why attrition is happening. 
The dashboard breaks attrition down by demographics, compensation, tenure, and job role, giving a quick, 
visual read on where the biggest turnover risks lie.

## Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16.1% |
| Average Age | 37 |
| Average Salary | 6.5K |
| Average Years at Company | 7.0 |

## Dashboard Features

- **Attrition by Age** — Split by gender (Male/Female) and by age brackets (26-35, 18-25, 36-45, 46-55, 55+),
-   highlighting that the 26-35 age group sees the highest attrition.
- **Attrition by Education Field** — Donut chart showing attrition share across Life Sciences, Medical, Marketing,
-   Technical Degree, and Other fields.
- **Attrition by Salary Slab** — Bar chart comparing attrition across salary bands (Upto 5k, 5k-10k, 10k-15k, 15k+),
-   showing attrition is concentrated in lower salary slabs.
- **Attrition by Years at Company** — Line/area chart tracking how attrition changes with tenure,
-   with a sharp spike among newer employees.
- **Attrition by Job Role** — Bar chart ranking roles by attrition count (Laboratory Technician, Sales Executive,
-   Research Scientist, Sales Representative, etc.).
- **Job Role Matrix** — Cross-tab of attrition counts by job role and category, with row/column totals for quick comparison.
- **Interactive Slicers** — Filter the entire dashboard by department: Human Resources, Research & Development, and Sales.

## Tools Used

- **Power BI Desktop** — data modeling, DAX measures, and visualization
- **Power Query** — data transformation and cleaning

## Insights

- Employees in the **26-35 age group** and those with **less than 2 years of tenure** show the highest attrition,
- suggesting onboarding and early-career engagement are key risk areas.
- Attrition is heavily weighted toward **lower salary slabs**, pointing to a possible link between compensation and retention.
- **Laboratory Technician** and **Sales Executive** roles have the highest attrition counts among job roles.

## How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Use the department slicers (HR / R&D / Sales) at the top to filter the dashboard by business unit.
4. Hover over visuals for tooltips, or click on a data point to cross-filter the rest of the dashboard.

## File Structure

```
├── HR Analytics Dashboard.pbix   # Power BI report file
├── data/                          # Source dataset (if included)
└── README.md                      # Project documentation
```

## About

This project was built as part of hands-on Power BI practice, focused on turning raw HR data into a clear, decision-ready attrition analysis.
