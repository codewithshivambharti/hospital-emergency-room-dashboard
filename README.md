🏥 Hospital Emergency Room Analysis Dashboard (Excel)

📌 Project Overview
This project focuses on building an Interactive Hospital Emergency Room Analysis Dashboard in Microsoft Excel using Power Query, Power Pivot, DAX, Pivot Tables, and Charts.
The dashboard helps stakeholders monitor patient flow, waiting times, satisfaction scores, admissions, and department referrals to improve hospital efficiency and decision-making.

🎯 Project Objectives
Track daily ER patient visits.
Monitor average patient wait times.
Analyze patient satisfaction scores.
Measure admission and non-admission rates.
Evaluate patient demographics.
Monitor referral trends across departments.
Improve operational efficiency through data-driven insights.

🛠 Tools & Technologies Used
Microsoft Excel
Power Query
Power Pivot
DAX (Data Analysis Expressions)
Pivot Tables
Pivot Charts
Dashboard Design & Visualization

📊 Key Performance Indicators (KPIs)
1. Number of Patients
Total patients visiting the ER.
Daily trend analysis using sparklines.
2. Average Wait Time
Average waiting time before seeing a medical professional.
Daily trend monitoring.
3. Patient Satisfaction Score
Average satisfaction rating.
Trend analysis to identify service quality issues.

📈 Dashboard Features
Patient Admission Status
Admitted vs Not Admitted patients.
Patient Age Distribution
Patients grouped by age categories.
Timeliness Analysis
Percentage of patients seen within 30 minutes.
Gender Analysis
Male vs Female patient count.
Department Referrals
Most referred departments.

🔄 Project Workflow
Business Requirement Gathering
Understanding the Dataset
Data Import using Power Query
Data Cleaning & Quality Checks
Calendar Table Creation
Data Modeling with Power Pivot
DAX Calculations
Pivot Table Creation
Chart Development & Formatting
Dashboard Development
Insight Generation

📅 Calendar Table Formula
= List.Dates(#date(2023,01,01),731,#duration(1,0,0,0))

🧮 DAX Formulas
Age Group
=IF([Patient Age]>=70,"70-79",
IF([Patient Age]>=60,"60-69",
IF([Patient Age]>=45,"45-59",
IF([Patient Age]>=30,"30-44",
IF([Patient Age]>=15,"15-29",
IF([Patient Age]>=5,"05-14","0-4"))))))

Patient Attend Status
=IF([Patient Waittime]<30,"Within Time","Delay")

📌 Insights Generated
Peak patient visit periods identified.
Average waiting time trends monitored.
Satisfaction score fluctuations analyzed.
Most common referral departments highlighted.
Age and gender demographics understood.
Service delays detected for operational improvements.

🚀 Business Impact
This dashboard enables hospital management to:
Improve patient experience.
Reduce waiting times.
Optimize resource allocation.
Monitor ER performance effectively.
Make data-driven decisions.

Shivam Bharti
📧 bhartishivam5676@gmail.com
📱 +91 7802071119
