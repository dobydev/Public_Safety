# Public Safety Operations Analytics Dashboard

**Power BI · DAX · Excel · Data Modeling · Data Visualization**

## Overview
This project demonstrates the design and development of an executive-style analytics dashboard built in **Power BI** using **Excel data exported from a helpdesk database**. The focus is on transforming raw operational exports into **clear, accurate, decision-ready reporting** suitable for leadership review.

All data included in this repository is **sanitized, anonymized, and non-PII**, recreated solely to demonstrate analytics, modeling, and visualization techniques.

---

## Key Objectives
- Convert flat Excel exports into structured analytical models
- Standardize time-based reporting using a **dedicated Month dimension**
- Highlight workload trends, resolution performance, and category distribution
- Apply professional layout, color, and KPI design principles

---

## Dashboard Features

### KPI Cards
- Total tickets opened (YTD)
- Total tickets closed (YTD)

### Time-Series Analysis
- Tickets opened by month
- Tickets closed by month

### Distribution Analysis
- Tickets by department
- Tickets by category

### Data Modeling
- Star-schema style layout
- Central **Months** table to ensure correct sorting and filtering
- Calculated fields and measures using DAX

---

## Data Preparation & Modeling
- Imported Excel files exported from a helpdesk system
- Cleaned and standardized raw data:
  - Normalized month names and month ordering
  - Consolidated ticket statuses into Open vs Resolved logic
  - Removed inconsistencies and corrected aggregation issues
- Built reusable dimension tables (Months, Categories, Departments)
- Implemented DAX measures for:
  - YTD totals
  - Conditional status grouping
  - Percentage breakdowns

---

## Tools & Technologies
- Power BI Desktop
- DAX
- Microsoft Excel (source data)
- Data modeling and relationship management
- Executive dashboard design

---
## Screenshot
<img width="1629" height="795" alt="image" src="https://github.com/user-attachments/assets/4b7f6f94-5926-4d08-b8dd-10b1b40e2287" />

---

