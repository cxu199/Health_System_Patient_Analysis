# 🏥 Healthcare Waiting List Analysis Dashboard

![Portfolio](https://img.shields.io/badge/Project-Portfolio-important)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue)
![SQL](https://img.shields.io/badge/SQL-Analytics-lightgrey?logo=postgresql)
![Python](https://img.shields.io/badge/Python-Data%20Prep-blue?logo=python)
![Domain](https://img.shields.io/badge/Domain-Healthcare-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A multi-page Power BI dashboard analysing inpatient, outpatient, and day-case waiting lists (2018–2021)...

---

# 📌 Dashboard Overview

This project includes **5 key pages**, each serving a distinct analytical purpose.

---

## 🥇 Summary Page
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/Waiting%20Patients%20Analysis%20-%20Summary.PNG)
### 🎯 Purpose
Provide a high-level overview of waiting list performance and key drivers.

### 📊 Key Elements
- Latest Month Wait List vs Previous Year  
- Case Type Distribution (Inpatient / Outpatient / Day Case)  
- Time Band vs Age Profile analysis  
- Top 5 specialties by waiting list  
- Monthly trend analysis  

### 🧠 Key Insight
Waiting list growth is primarily driven by outpatient demand, with long-wait patients (18+ months) contributing significantly to backlog pressure.

---

## 🥈 Executive Page (Long Wait Focus)
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/Executive.PNG)
### 🎯 Purpose
Highlight critical backlog risk (18+ months) and support executive decision-making.

### 📊 Key KPIs
- YoY Growth %  
- Long Wait YoY %  
- Long Wait %  
- P90 Long Wait List  
- Median Long Wait List  

### 📈 Key Visuals
- Treemap → Top 10 specialties driving backlog  
- Scatter Plot → Risk segmentation (Median vs P90)  
- Case Type breakdown  
- Age profile analysis  

### 🧠 Executive Insight
Backlog is concentrated in long-wait patients and a small number of specialties (e.g. ENT), indicating targeted bottlenecks rather than system-wide pressure.

---

## 🥉 Detailed Page
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/Waiting%20Patients%20Analysis%20-%20Detail.PNG)
### 🎯 Purpose
Enable drill-down analysis of waiting list trends.

### 📊 Features
- Full monthly breakdown (Day Case, Inpatient, Outpatient)  
- Interactive filters:
  - Date  
  - Case Type  
  - Specialty  
  - Age Profile  
  - Time Bands  

### 🧠 Use Case
Supports detailed investigation and validation beyond the executive view.

---

## 🧩 KPIs Explained Page
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/KPIs%20Explained.PNG)
### 🎯 Purpose
Provide clear definitions and business context for key metrics.

### 📌 Metrics Covered
- YoY Growth % → Demand trend  
- Long Wait % → Backlog severity  
- Median → Typical performance  
- P90 → Extreme pressure  

### 🧠 Key Concept
Combining Median and P90 reveals whether backlog is evenly distributed or concentrated.

---

## 🧾 Long Wait Detailed Page
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/Long%20WL%20Detailed%20View.PNG)
### 🎯 Purpose
Provide a granular view of long-wait (18+ months) performance by specialty.

### 📊 Key Fields
- YoY Growth %  
- Long Wait %  
- P90 Long Wait List  
- Median Long Wait List  
- Latest Month Long Wait Patients  

### 🧠 Insight
Helps identify both high-volume backlog and high-risk specialties for targeted intervention.

---

## 💡 Tooltip (Summary Page)
![image alt](https://github.com/cxu199/Health_System_Patient_Analysis/blob/9791db8d4a5529d5d76936516b6c2d9fecdbbde0/images/Drilldown%20tooltip%20for%20Summary%20page%20line%20chart.PNG)
### 🎯 Purpose
Enhance usability with on-hover explanations.

### 📊 Content
- KPI definitions  
- Interpretation guidance  
- Business meaning  

### 🧠 Benefit
Improves clarity without adding visual clutter.

---

# 📊 Key Analytical Concepts

- **Median (50th percentile)** → Typical performance  
- **P90 (90th percentile)** → Extreme pressure  
- **Long Wait %** → Backlog risk indicator  
- **Segmentation (Scatter Plot)** → Risk classification  

---

# 📌 Key Insights

- Backlog is not evenly distributed across specialties  
- Long-wait patients (18+ months) drive system pressure  
- A small number of specialties (e.g. ENT) contribute disproportionately  
- Most specialties remain stable  

---

# 🎯 Business Recommendations

- Prioritise 18+ month backlog clearance  
- Focus on top 10% specialties (P90 group)  
- Expand outpatient capacity  
- Monitor Long Wait % and P90  

---

# 🛠️ Tools & Skills

- Power BI (DAX, dashboard design)  
- Data Modelling (star schema)  
- Analytics (distribution, segmentation)  
- SQL / Python (data preparation)

---

# ⭐ Why This Project Stands Out

- Uses Median + P90 to uncover backlog concentration  
- Moves beyond reporting to decision-making  
- Applies segmentation logic for prioritisation  
- Designed for executive usability  

---

# 👤 Author

Cong Xu  
Data Analyst | Power BI | SQL | Python
