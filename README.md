# Health_System_Patient_Analysis

A multi-page Power BI dashboard analysing inpatient, outpatient, and day-case waiting lists (2018–2021), designed to identify backlog trends, concentration, and high-risk areas.

The dashboard combines trend analysis, distribution metrics (Median & P90), and segmentation logic to support data-driven decision-making.

📌 Dashboard Overview

This project includes 5 key pages, each serving a distinct analytical purpose:

🥇 1. Summary Page
🎯 Purpose

Provide a high-level overview of waiting list performance and key drivers.

📊 Key Elements
Latest Month Wait List vs Previous Year
Case Type Distribution (Inpatient / Outpatient / Day Case)
Time Band vs Age Profile analysis
Top 5 specialties by waiting list
Monthly trend analysis
🧠 Key Insight

Waiting list growth is primarily driven by outpatient demand, with long-wait patients (18+ months) contributing significantly to overall backlog pressure.

🥈 2. Executive Page (Long Wait Focus)
🎯 Purpose

Highlight critical backlog risk (18+ months) and support executive decision-making.

📊 Key KPIs
YoY Growth %
Long Wait YoY %
Long Wait %
P90 Long Wait List
Median Long Wait List

📈 Key Visuals
Treemap → Top 10 specialties driving backlog
Scatter Plot → Risk segmentation (Median vs P90)
Case Type breakdown
Age profile analysis
🧠 Executive Insight

Backlog is concentrated in long-wait patients and a small number of specialties (e.g. ENT), indicating targeted bottlenecks rather than system-wide pressure.

🥉 3. Detailed Page
🎯 Purpose

Enable drill-down analysis of waiting list trends.

📊 Features
Full monthly breakdown (Day Case, Inpatient, Outpatient)
Interactive filters:
Date
Case Type
Specialty
Age Profile
Time Bands
🧠 Use Case

Supports data validation and deep-dive investigation beyond executive summaries.

🧩 4. KPIs Explained Page
🎯 Purpose

Provide clear definitions and business context for all key metrics.

📌 Metrics Covered
YoY Growth % → Demand trend
Long Wait % → Backlog severity
Median → Typical backlog level
P90 → Extreme backlog pressure
🧠 Key Concept

Combining Median and P90 reveals whether backlog is evenly distributed or concentrated in a small number of specialties.

🧾 5. Long Wait Detailed Page
🎯 Purpose

Provide a granular view of long-wait (18+ months) performance by specialty.

📊 Key Fields
YoY Growth %
Long Wait %
P90 Long Wait List
Median Long Wait List
Latest Month Long Wait Patients
🧠 Insight

Enables identification of both high-volume backlog and high-risk specialties for targeted intervention.

💡 Tooltip (Summary Page)
🎯 Purpose

Enhance usability by providing on-hover explanations for key visuals.

📊 Content
KPI definitions
Interpretation guidance
Business relevance
🧠 Benefit

Improves dashboard clarity without adding visual clutter.

📊 Key Analytical Concepts
Median (50th percentile) → Typical performance
P90 (90th percentile) → Extreme pressure
Long Wait % → Backlog risk indicator
Segmentation (Scatter Plot) → Identifies:
Critical bottlenecks
Emerging risks
Capacity-driven backlog

📌 Key Insights
Backlog is not evenly distributed across specialties
Long-wait patients (18+ months) drive system pressure
A small number of specialties (e.g. ENT) contribute disproportionately
Most specialties remain stable, confirming targeted rather than systemic issues

🎯 Business Recommendations
Prioritise 18+ month backlog clearance
Focus on top 10% specialties (P90 group)
Expand outpatient capacity in high-demand areas
Monitor Long Wait % and P90 to prevent re-accumulation

🛠️ Tools & Skills
Power BI — Dashboard design, DAX, data modelling
DAX — Time intelligence, percentile analysis, KPI logic
Data Modelling — Star schema
Analytics — Distribution analysis, segmentation, business insights

⭐ Why This Project Stands Out

This project demonstrates:

Moving beyond averages to distribution-aware analytics
Using P90 and Median together to uncover hidden backlog risk
Translating data into actionable business strategy
Designing dashboards for executive decision-making

👤 Author

Cong Xu
Data Analyst | Power BI | SQL | Python
