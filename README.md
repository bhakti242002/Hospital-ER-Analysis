# Hospital-ER-Analysis

# 🏥 Hospital Emergency Room Dashboard - Monthly Report

<img width="1795" height="659" alt="Screenshot 2025-07-22 120148" src="https://github.com/user-attachments/assets/7d34e9d8-2bbb-4f94-8fda-e3edf204fab0" />


This repository presents a monthly Emergency Room (ER) dashboard created using **Microsoft Excel**. The dashboard offers valuable insights into hospital performance, patient flow, and service quality using charts, formulas and slicers.

---

## 📊 Dashboard Overview

### 📌 Key Metrics Tracked

- **Number of Patients**
  - Total patient visits for the selected month.
  - Includes a daily sparkline trend to identify busy days and potential seasonal patterns.

- **Average Wait Time (Minutes)**
  - Calculates the average time a patient waits before being seen by a medical professional.
  - Includes daily trends to help pinpoint inefficiencies or bottlenecks in patient processing.

- **Patient Satisfaction Score**
  - Displays the average satisfaction rating given by patients.
  - Helps correlate satisfaction with workload and wait times.

---

## Additional Analytical Insights

### Patient Admission Status
- Breakdown of **Admitted vs. Not Admitted** cases.
- Presented as both count and percentage to evaluate ER effectiveness and load.

### Age Distribution
- Visualizes the number of patients grouped by age brackets:
  `0–9, 10–19, 20–29, 30–39, 40–49, 50–59, 60–69, 70–79`

### Timeliness of Care
- Percentage of patients attended **within 30 minutes**.
- Pie chart representation showing **Delayed vs. On-Time** care.

### Gender Analysis
- Number of patients by **Gender**.
- Pie chart showing male and female patient distribution.

### Department Referrals
- Tracks patient referrals across departments:
  - General Practice
  - Orthopedics
  - Cardiology
  - Physiotherapy
  - Neurology
  - Renal
  - Gastroenterology
  - None

---
## About the Dataset

This dataset consists of **9,216 rows** and **12 columns**, covering detailed information about ER visits in 2023 and 2024.

The dataset used for this dashboard is stored in `Hospital Emergency Room Data.xlsx`. It includes anonymized patient-level data with the following key fields:

- Visit Date
- Patient ID
- Gender
- Age
- Wait Time (minutes)
- Satisfaction Score (1–5)
- Admission Status
- Referral Department
- Time Attended (minutes)

This raw data has been:
- Cleaned and loaded using **Power Query** for efficient processing
- Modeled using Excel’s **Data Model**
- Calculated using **DAX-like formulas** via **Measures** and **Calculated Columns**
- Visualized using **Pivot Tables**, **Charts**, and **Slicers**

##  Tools Used
- **Microsoft Excel**
- **Power Query** – for data import, cleansing, and transformation
- **Data Model** – to manage relationships across fields
- **Measures** – for dynamic calculations like averages and counts
- **Calculated Columns** – for logic-based grouping and flags
- **Sparklines, Pivot Charts & Tables** – for dynamic, interactive visuals
- **Slicers** – to filter by time, gender, and departments

---

## 📁 Files in This Repo


| File Name | Description |
|-----------|-------------|
| [`Hospital ER Analysis.xlsx`](./Hospital%20ER%20Analysis.xlsx) | Contains Pivot report and interactive Dashboard |
| [`Hospital Emergency Room Data.xlsx`](./Hospital%20Emergency%20Room%20Data.xlsx) | Raw Dataset |
| [`README.md`](./README.md) | You are here! |


---

## 📈 Insights & Impact

✅ Identify ER crowding patterns  
✅ Monitor and optimize patient wait times  
✅ Improve patient satisfaction and resource allocation  
✅ Align department staffing with referral volume

---


## Note on Interactivity

If you download the Excel dashboard (`Hospital ER Analysis.xlsx`) and find it non-interactive:

- Open the file in Microsoft Excel.
- Click **“Enable Editing”** at the top.
- If prompted, also click **“Enable Content”** to activate interactivity.
- Now you can use slicers, filters and refresh options seamlessly.

## Contributions

Feel free to fork, analyze or contribute by adding Excel tips or dashboard improvements for healthcare analytics.

---

