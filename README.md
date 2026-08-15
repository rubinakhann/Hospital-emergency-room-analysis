# 🏥 Hospital Emergency Room Analysis Dashboard

[![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=for-the-badge&logo=microsoft&logoColor=black)](https://learn.microsoft.com/power-query/)
[![Power Pivot](https://img.shields.io/badge/Power%20Pivot-217346?style=for-the-badge&logo=microsoft&logoColor=white)](https://support.microsoft.com/excel)
[![DAX](https://img.shields.io/badge/DAX-4472C4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/dax/)

> An interactive Excel dashboard analyzing hospital emergency-room operations, patient flow, waiting time, satisfaction, admissions, demographics, and departmental referrals.

---

## 📊 Dashboard

![Hospital Emergency Room Dashboard](screenshots/dashboard.png)

---

## 🎯 Business Problem

Hospital management needs a simple way to monitor emergency-room performance and identify potential operational bottlenecks.

This dashboard helps answer:

- How many patients are visiting the emergency room?
- What is the average waiting time?
- How many patients are admitted?
- How satisfied are patients?
- Which age groups and genders have the highest patient volume?
- Which departments receive the most referrals?
- How many patients are attended within the 30-minute threshold?
- How does patient volume change over time?

---

## 📌 Key KPIs

| KPI | Result |
|---|---:|
| **Total Patients** | 1,024 |
| **Average Wait Time** | 35.73 |
| **Average Satisfaction Score** | 5.12 |
| **Admitted Patients** | 476 |
| **Non-Admitted Patients** | 548 |
| **Admitted %** | 46.48% |
| **Non-Admitted %** | 53.52% |

---

## 🔍 Key Insights

> These findings represent the **overall dataset**, without applying a specific month or year filter.

- **53.52% of patients were non-admitted**, compared with 46.48% admitted.
- **630 patients were delayed**, while 394 were attended within the defined 30-minute threshold.
- The **60–69 age group recorded the highest patient volume** with 140 patients.
- **General Practice had the highest number of referrals** with 201 patients, followed by Orthopedics with 102.
- The dataset contains **524 male and 500 female** patient visits.
- Overall **average wait time was 35.73**, while the **average satisfaction score was 5.12**.

---

## 🔄 Analytics Workflow

```text
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Power Pivot Data Model
   ↓
DAX Calculations
   ↓
PivotTables / PivotCharts
   ↓
Interactive Dashboard
   ↓
Business Insights
```

Power Query was used for data preparation and transformation, while Power Pivot and DAX were used for data modeling and analytical calculations.

---

## 🛠️ Analytics Stack

**Microsoft Excel • Power Query • Power Pivot • DAX • PivotTables • PivotCharts • Slicers**

---


## 💼 Skills Demonstrated

**Data Cleaning • Data Transformation • Data Modeling • DAX • KPI Development • Dashboard Design • Data Visualization • Business Analysis • Insight Generation**

---

## 🎓 Project Type

**End-to-End Data Analytics | Microsoft Excel**

This project demonstrates how raw operational data can be transformed into an analytical data model and interactive dashboard to support data-driven decision-making.

---

