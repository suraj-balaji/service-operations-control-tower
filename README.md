# Service Operations Control Tower Dashboard

## Business Problem

Healthcare operations teams often struggle to monitor patient demand, staffing pressure, repeat visits, and operational risk in a centralized view. Decision-makers require real-time visibility into workload distribution, patient flow, and high-risk operational periods to improve staffing allocation, throughput efficiency, and service quality.

Without centralized operational analytics:

* Peak-hour overloads remain unmanaged
* Repeat-user demand increases unnoticed
* High-risk cases may not receive timely attention
* Staffing allocation becomes reactive instead of data-driven
* Patient flow inefficiencies impact service quality

---

# Project Objective

The objective of this project was to build an executive-level operational dashboard that helps hospital management:

* Monitor patient workload trends
* Identify peak operational periods
* Track repeat-user demand
* Analyze patient risk distribution
* Improve staffing and capacity planning
* Support operational decision-making using data

The dashboard was designed as a centralized control tower for operational monitoring and management reporting.

---

# Dataset Overview

The project used multi-source healthcare operational datasets containing:

### Patient Information

* Patient ID
* Age
* Gender
* Insurance Status
* Arrival Information

### Operational Data

* Admission / Discharge records
* Arrival Shift & Time
* Repeat Visit Counts
* Surgeries
* Admissions

### Clinical Data

* Triage Vitals
* EWS Risk Indicators
* Heart Rate
* Blood Pressure
* Respiratory Rate

### Additional Service Metrics

* Medication usage
* Complaint records
* Shift-level workload patterns

The final operational model was built using cleaned and transformed healthcare records integrated through Power Query.

---

# Tools & Technologies

* Microsoft Excel 2024
* Power Query
* Pivot Tables
* Pivot Charts
* KPI Cards
* Conditional Formatting
* Slicers
* Dashboard Design Techniques

---

# Data Cleaning Process

The raw healthcare data contained multiple disconnected operational tables. The following cleaning and transformation steps were performed:

### Data Preparation

* Imported multiple raw operational datasets
* Removed duplicates and null inconsistencies
* Standardized column names
* Corrected data types

### Power Query Transformations

* Appended admission and discharge records
* Merged triage vitals into master operational model
* Added helper intelligence columns
* Built shift categorization logic
* Created risk classification flags

### Feature Engineering

Created operational helper columns such as:

* Shift Groups
* Repeat User Flags
* EWS Risk Categories
* Vital Sign Flags
* Age Bands
* Operational KPI Fields

The optimized master operational dataset was reduced and structured for efficient dashboard reporting.

---

# KPI Definitions

### Total Cases

Total distinct patient records processed in the operational model.

### Repeat User %

Percentage of patients with multiple emergency visits indicating recurring operational demand.

### High Risk %

Percentage of patients classified under elevated EWS risk conditions.

### Admissions

Total admission-related operational load observed in the dataset.

### Average EWS Score

Average operational risk severity based on triage indicators.

### Average Medication Usage

Average medication utilization per patient interaction.

---

# Dashboard Overview

The dashboard was designed as an executive operational control center with the following analytical sections:

### Operational Demand Monitoring

* Cases by Shift
* Monthly Volume Trends
* Age Band Demand Distribution

### Risk & Throughput Monitoring

* Risk Levels by Shift
* Admission vs Discharge Trends
* High-Risk Operational Windows

### Resource Utilization

* Repeat User Analysis
* Workload Distribution
* Patient Volume by Segment

### Interactive Features

* Dynamic slicers
* Cross-filtering
* Executive KPI cards
* Operational drill-down capability

The layout was designed for fast executive-level decision-making and operational monitoring.
</br>
<img width="434" height="272" alt="Serive_operation_Dashboard_1" src="https://github.com/user-attachments/assets/a972c724-2e47-4240-82b5-d2a142eb4f36" />

---

# Key Insights

### 1. Peak Demand Window

Patient workload was highest between 11:00–18:00, indicating increased operational pressure during midday and evening periods.

### 2. Repeat Users Created Significant Operational Load

Repeat users represented a major share of total demand, highlighting recurring service utilization patterns.

### 3. Senior Age Groups Drove Highest Demand

Patients aged 51+ generated the largest operational burden across admissions and resource utilization.

### 4. Discharges Exceeded Admissions

Operational throughput remained relatively efficient as discharge volume exceeded admissions across most periods.

### 5. High-Risk Cases Clustered in Specific Shifts

Certain operational windows experienced higher concentrations of elevated-risk patients requiring stronger staffing readiness.

---

# Root Cause Analysis

### Operational Congestion During Midday

Midday peaks likely resulted from overlapping outpatient referrals, emergency arrivals, and staffing concentration gaps.

### Recurring Patient Demand

High repeat-user percentages suggest gaps in preventive care, chronic disease management, or outpatient follow-up processes.

### Senior Patient Resource Burden

Older age groups naturally required higher operational resources due to increased admission probability and treatment intensity.

### Shift-Level Risk Concentration

Uneven risk distribution across shifts may indicate staffing mismatch or operational timing patterns affecting patient intake.

---

# Business Recommendations

### Staffing Optimization

Increase staffing allocation during peak operational windows between 11:00–18:00.

### Repeat User Intervention Programs

Develop chronic-care follow-up and preventive management programs to reduce recurring emergency demand.

### Senior-Care Readiness

Allocate additional operational resources for higher-demand senior age segments.

### Risk-Based Shift Planning

Strengthen high-risk shift coverage with experienced staff and faster triage workflows.

### Operational Monitoring

Implement continuous KPI tracking for workload balancing and throughput management.

---

# Expected Business Impact

If implemented operationally, the dashboard could support:

* Improved staffing efficiency
* Reduced operational congestion
* Faster identification of high-risk periods
* Better workload balancing
* Improved patient throughput
* Enhanced operational decision-making
* Stronger visibility into repeat-user demand

The dashboard provides a scalable framework for operational intelligence and service monitoring.

---

# Future Improvements

Potential future enhancements include:

* Real-time data refresh integration
* SQL-based backend automation
* Power BI enterprise deployment
* Predictive workload forecasting
* Readmission prediction models
* Advanced patient segmentation
* Automated operational alerts
* Service-level agreement (SLA) monitoring

---
## Author
Suraj Balaji Bhagaye </br>
bhagayesuraj@gmail.com
