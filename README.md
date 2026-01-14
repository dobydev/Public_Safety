# Public Safety Operations Analytics Dashboard

**Power BI · DAX · Excel · Data Modeling · Data Visualization**

## Overview
This project demonstrates the design and development of an executive-style analytics dashboard built in **Power BI** using **Excel data exported from a helpdesk database**. The focus is on transforming raw operational exports into **clear, accurate, decision-ready reporting** suitable for leadership review.

All data included in this repository is **sanitized, anonymized, and non-PII**, recreated solely to demonstrate analytics, modeling, and visualization techniques.

<img width="1420" height="796" alt="image" src="https://github.com/user-attachments/assets/1c1aa188-0948-4e6d-b432-2a110bc39e19" />

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
<img width="737" height="177" alt="image" src="https://github.com/user-attachments/assets/78c7c4af-b484-4cae-8947-125d1e5c557c" />

### Time-Series Analysis
- Tickets opened by month
<img width="681" height="222" alt="image" src="https://github.com/user-attachments/assets/131532d3-2fd3-4b1f-901e-b20efd06c694" />

- Tickets closed by month
<img width="712" height="223" alt="image" src="https://github.com/user-attachments/assets/e0a9a29e-53db-4716-b8cc-8b1ed8c15c76" />

### Distribution Analysis
- Tickets by department
<img width="694" height="326" alt="image" src="https://github.com/user-attachments/assets/7e643f6b-cead-49c6-9a71-b52c505abd01" />

- Tickets by category
<img width="716" height="328" alt="image" src="https://github.com/user-attachments/assets/52912ac4-42e4-441d-9a07-d7afcd9fbc9a" />

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


---

