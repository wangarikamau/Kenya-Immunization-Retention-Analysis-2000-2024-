## Kenya Immunization Retention Analysis (2000-2024)

# Project Overview
This project evaluates the performance of Kenya’s routine immunization program using WHO/UNICEF Estimates of National Immunization Coverage (WUENIC) data.

The analysis focuses on the Retention Gap  the proportion of children who begin a vaccination schedule (Dose 1) but fail to complete it (Dose 3). In public health Monitoring & Evaluation (M&E), this metric is widely used to assess:

Health system effectiveness
Continuity of care
Service utilization
Program stability

Rather than analyzing vaccination access alone, this project evaluates whether the healthcare system successfully retains patients throughout the full immunization cycle.

# Public Health Problem

High immunization dropout rates can indicate weaknesses in healthcare delivery systems, including:

poor follow-up mechanisms,
operational inefficiencies,
reporting gaps,
or barriers to healthcare access.

Monitoring retention performance helps public health stakeholders identify areas where intervention strategies may be needed to improve continuity of care and reduce vulnerability to vaccine-preventable diseases.

# Key Analytical Questions
How has immunization dropout changed in Kenya from 2000 to 2024?

Has Kenya consistently met the WHO-recommended dropout threshold?

What historical patterns suggest system shocks or recovery periods?

How effective is the immunization system in retaining patients after first contact?


# Key Metrics & KPIs
## Dropout Rate (%)

Measures the proportion of children who received Dose 1 but failed to complete Dose 3.

## WHO Benchmark Threshold

WHO recommends maintaining dropout rates below 10% to indicate stable immunization system performance.

## Retention Efficiency

Measures the healthcare system’s ability to ensure continuity after initial vaccination contact.

## Missed Opportunities

Represents the absolute gap between Dose 1 and Dose 3 immunization coverage

# Dataset Information
## Data Source

WHO/UNICEF Estimates of National Immunization Coverage (WUENIC), 2025 Revision

## Dataset Features
Reporting Year

Vaccine Dose Coverage

Dropout Rate

Retention Indicators

## Data Format
Excel

CSV

# Tools & Technologies Used
Power BI

Power Query

DAX

Excel

# Data Cleaning & Preparation

The data transformation process involved:

Cleaning and reshaping multi-row WUENIC datasets

Applying pivoting and grouping techniques to align vaccination doses by year

Standardizing time-series structures for longitudinal analysis

Preparing datasets for dashboard integration and KPI calculation

Power Query was extensively used for preprocessing and transformation workflows.

# Data Analysis & Dashboard Development
## Data Analysis (DAX)

Built dynamic analytical measures for:

longitudinal trend analysis,
dropout rate calculations,
year-over-year comparisons,
WHO threshold monitoring
and conditional performance highlighting.

# Dashboard & Visualizations
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a471293a-da2f-4619-831c-26ae4952eeb8" />

dashboard_preview.png

# Key Insights
1. Improved System Stability

Since 2016, Kenya has consistently maintained dropout rates below the WHO 10% threshold, indicating stronger follow-up systems and improved immunization continuity.

2. Historical System Volatility

Between 2003 and 2005, dropout rates increased significantly, suggesting possible programmatic disruptions such as:

funding instability,
operational inefficiencies,
or healthcare system challenges.
3. Strong Current Performance

Recent data (~4% dropout rate) reflects high retention efficiency and positions Kenya well within WHO-recommended performance standards.

4. Continuity of Care Improvements

The declining dropout trend suggests improvements not only in vaccine access, but also in continuity of care — a critical healthcare M&E indicator.

# Recommendations
Strengthen monitoring systems in regions with fluctuating retention performance

Improve early follow-up mechanisms for incomplete vaccination schedules

Expand district-level dropout monitoring using DHIS2 reporting systems

Implement automated data quality validation checks

Conduct localized analysis to identify high-risk populations

# Repository Contents
Kenya_Immunization_Retention_Analysis.pbix — Interactive Power BI dashboard

dashboard_preview.png — Snapshot of key visuals

# Potential Extensions
District-level analysis using DHIS2 datasets

Correlation analysis between dropout rates and health workforce density

Predictive modeling of immunization dropout risk using machine learning

Integration with GIS mapping for regional visualization

# Why This Project Matters
This project demonstrates how healthcare analytics can support evidence-based decision-making in public health systems.

By focusing on retention rather than simple coverage metrics, the analysis provides insights relevant to:
NGO program evaluation

Immunization program monitoring

Health system strengthening

Policy and intervention planning

Monitoring & Evaluation (M&E)

# Author

June Wangari Kamau

Junior Data Analyst | Healthcare M&E Enthusiast
