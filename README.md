# 🏥 Hospital Emergency Room Analysis Dashboard

[![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=for-the-badge&logo=microsoft&logoColor=black)](https://learn.microsoft.com/power-query/)
[![Power Pivot](https://img.shields.io/badge/Power%20Pivot-217346?style=for-the-badge&logo=microsoft&logoColor=white)](https://support.microsoft.com/excel)
[![DAX](https://img.shields.io/badge/DAX-4472C4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/dax/)
[![PivotTables](https://img.shields.io/badge/PivotTables-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://support.microsoft.com/excel)

> An end-to-end **Excel Data Analytics project** built to analyze hospital emergency-room operations, patient flow, waiting time, satisfaction, admissions, demographics, and departmental referrals.

---

## 📊 Dashboard Preview

![Hospital Emergency Room Dashboard](screenshots/dashboard.png)

---

## 🎯 Business Problem

Hospital management needs a clear and interactive way to monitor emergency-room activity and understand where operational issues may exist.

This project analyzes patient-level emergency-room data to answer questions such as:

- How many patients are visiting the emergency room?
- What is the average patient waiting time?
- How satisfied are patients with the service?
- How many patients are admitted vs. not admitted?
- Which age groups and genders represent the highest patient volume?
- Which departments receive the most referrals?
- How many patients are attended within the defined 30-minute threshold?
- How does patient volume change over time?

The goal is to transform raw patient data into **actionable operational insights through an interactive Excel dashboard**.

---

## 🎯 Project Objectives

- Analyze emergency-room patient volume.
- Monitor average waiting time.
- Track patient satisfaction.
- Compare admitted and non-admitted patients.
- Analyze patients by age group and gender.
- Identify the most frequently referred departments.
- Measure patient attendance within the defined 30-minute threshold.
- Analyze daily patient trends.
- Build an interactive dashboard for stakeholder analysis.

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

## 🧹 Data Preparation

### Power Query

Power Query was used to prepare the raw data before building the dashboard.

Key preparation tasks included:

- Data quality checking
- Checking errors and blank values
- Merging patient initials and last-name fields
- Standardizing gender values
- Converting admission flags into readable categories
- Removing the duplicate satisfaction-score field
- Separating date and time information
- Creating fields required for analysis
- Preparing the cleaned dataset for the data model

---

## 📅 Calendar Table

A dedicated calendar table was created to support time-based analysis.

The calendar table enables:

- Date-based filtering
- Daily trend analysis
- Consistent time-based reporting
- Relationship between dates and patient records

---

## 🔗 Data Modeling

The project uses **Power Pivot** to create a data model containing:

- Emergency Room Patient Data
- Calendar Table

A relationship is established through the relevant date field to support time-based analysis and dashboard filtering.

---

## 🧮 DAX & Analytical Calculations

DAX was used to create analytical fields and calculations required by the dashboard.

The analysis includes logic for:

- Patient age groups
- Admission status
- Patient attendance status
- KPI calculations
- Time-based analysis
- Dashboard metrics

A key business rule is the **30-minute attendance threshold**, which is used to classify patient attendance as on-time or delayed.

---

## 📈 Dashboard Analysis

### 👥 Patient Volume

Tracks total patient visits and daily patient trends to identify changes in emergency-room activity.

### ⏱️ Waiting Time

Monitors the average time patients wait before being attended.

### ⭐ Patient Satisfaction

Tracks the average satisfaction score to evaluate patient service experience.

### 🏥 Admission Analysis

Compares:

- Admitted patients
- Non-admitted patients

### 👴 Age Group Analysis

Patients are grouped into age ranges to understand the distribution of emergency-room visits across different age groups.

### ⚥ Gender Analysis

Compares emergency-room patient volume by gender.

### 🩺 Department Referral Analysis

Identifies departments receiving the highest number of patient referrals.

### ⏱️ Attendance Timeliness

Measures how many patients were attended within the defined 30-minute threshold and how many experienced delays.

---

## 🔍 Key Findings

> These findings represent the overall dashboard output and are not based on a specific month or date filter.

### 1. Admission Pattern

**53.52% of patients were not admitted**, while **46.48% were admitted**.

Non-admitted patients therefore represent the larger share of the analyzed emergency-room visits.

### 2. Attendance Delays

- **394 patients** were classified as on-time.
- **630 patients** were classified as delayed.

The number of delayed patients is substantially higher than the number attended within the defined 30-minute threshold.

### 3. Age Distribution

The **60–69 age group** recorded the highest patient volume with **140 patients**.

### 4. Gender Distribution

- Male: **524**
- Female: **500**

The dataset contains a slightly higher number of male patient visits.

### 5. Department Referrals

**General Practice** recorded the highest number of referrals with **201 patients**, followed by **Orthopedics with 102**.

### 6. Overall Service Metrics

The overall dataset reports:

- **Average Wait Time:** 35.73
- **Average Satisfaction Score:** 5.12

These metrics provide a high-level view of emergency-room service performance.

---

## 📊 Detailed Distribution

### Age Group

| Age Group | Patients |
|---|---:|
| 0–09 | 133 |
| 10–19 | 136 |
| 20–29 | 123 |
| 30–39 | 133 |
| 40–49 | 120 |
| 50–59 | 123 |
| 60–69 | 140 |
| 70–79 | 116 |

### Attendance Status

| Status | Patients |
|---|---:|
| On-time | 394 |
| Delayed | 630 |

### Department Referrals

| Department | Patients |
|---|---:|
| General Practice | 201 |
| Orthopedics | 102 |
| Cardiology | 29 |
| Physiotherapy | 29 |
| Neurology | 22 |
| Gastroenterology | 18 |
| Renal | 13 |

---

## 🔄 Project Workflow

```text
Raw CSV Data
     ↓
Data Import
     ↓
Power Query
     ↓
Data Quality Check
     ↓
Cleaning & Transformation
     ↓
Calendar Table
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

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Microsoft Excel** | Analysis & dashboard |
| **Power Query** | Data import, cleaning & transformation |
| **Power Pivot** | Data modeling & relationships |
| **DAX** | Analytical calculations |
| **PivotTables** | Data aggregation |
| **PivotCharts** | Data visualization |
| **Excel Slicers/Filters** | Interactive analysis |

---



