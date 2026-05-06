## Kenya Immunization Retention Analysis (2000-2024)

# Project Overview

This project evaluates the performance of Kenya’s routine immunization program using WHO/UNICEF (WUENIC) data.

The analysis focuses on the Retention Gap—the proportion of children who begin a vaccination schedule (Dose 1) but fail to complete it (Dose 3). This metric is widely used in public health Monitoring & Evaluation (M&E) to assess health system effectiveness, continuity of care, and service utilization.

The goal is to move beyond surface-level coverage metrics and assess whether the system successfully retains patients full immunization cycle.

# Key Analytical Questions
How has immunization dropout changed in Kenya from 2000–2024?
Has Kenya met the WHO-recommended dropout threshold over time?
What historical patterns indicate system shocks or recovery periods?
How efficient is the current immunization system in retaining patients?

# Key Metrics & KPIs
Dropout Rate (%)
WHO Threshold: 10% benchmark for identifying potential system instability
Retention Efficiency: Ability of the system to ensure completion after first contact
Missed Opportunities: Absolute gap between Dose 1 and Dose 3

# Technical Skills Demonstrated
Data Transformation (Power Query)
Cleaned and reshaped multi-row WUENIC datasets
Applied pivoting and grouping to align vaccination doses by year
Standardized time-series structure for analysis
Data Analysis (DAX)
Built time-based measures for longitudinal trend analysis
Created dynamic calculations for dropout rate and year filtering
Implemented conditional logic to highlight WHO threshold breaches
Data Visualization (Power BI)

Developed an interactive dashboard with:

Trend Analysis: 24-year dropout rate vs WHO benchmark
Gap Analysis (Area Chart): Visualizing cumulative missed vaccinations
KPI Indicator: Current-year performance against global standards
Comparative Insights: Historical vs recent system performance
# Key Insights
1. System Maturity

Since 2016, Kenya has consistently maintained dropout rates below the WHO 10% threshold, indicating improved system stability and stronger follow-up mechanisms.

2. Historical Volatility

Between 2003–2005, dropout rates spiked significantly—suggesting programmatic disruptions, such as funding gaps, policy shifts, or operational inefficiencies.

3. Current Performance

The most recent data (~4% dropout rate) reflects high retention efficiency, placing Kenya well within global safety standards.

4. Programmatic Interpretation

The declining dropout trend suggests that improvements are not just in access—but in continuity of care, a key indicator in healthcare M&E frameworks.

# Repository Contents
Kenya_Immunization_Retention_Analysis.pbix — Interactive Power BI dashboard
dashboard_preview.png — Snapshot of key visuals

# Data Source
WHO/UNICEF Estimates of National Immunization Coverage (WUENIC), 2025 Revision

# Why This Project Matters

This project demonstrates how data analytics can support evidence-based decision-making in public health.

By focusing on retention rather than just access, the analysis provides insights that are directly relevant to:

NGO program evaluation
Health system strengthening
Policy and intervention design

# Potential Extensions
District-level analysis using DHIS2 data
Correlating dropout rates with health workforce or facility density
Predictive modeling of dropout risk using machine learning

# Author

June Wangari Kamau
Junior Data Analyst | Healthcare M&E Enthusiast
