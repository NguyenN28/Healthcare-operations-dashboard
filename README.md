**🏥 Massachusetts General Hospital: Patient Outcomes & Operational Analysis**

Role: Healthcare Data Analyst

Tool: Power BI (Advanced Data Modeling, DAX, Trend Analysis)

📋 Project Overview

This analysis evaluates patient admissions, readmission rates, and financial coverage at Massachusetts General Hospital. The goal is to provide hospital administrators with a clear view of operational efficiency, patient demographics, and the financial impact of different insurance payers.

🎯 Business Objectives:

Operational Efficiency: Monitor Average Length of Stay (ALOS) and total procedures.

Patient Care: Track the readmission rate to identify potential gaps in discharge planning.

Financial Analysis: Analyze revenue coverage by insurance payers and identify the "Rate of Covered by Insurance."

🚀 Key Insights from the Dashboard

High Readmission Rate: The dashboard identifies a 87.68% readmission rate (854 out of 974 patients). This is a critical metric for hospital efficiency and suggests a need for deeper investigation into post-discharge care.

Revenue Leadership: Medicare is the dominant payer, contributing over $12.9M in procedure coverage, followed by Medicaid.

Procedure Volume: The hospital managed 47.70K total procedures, with a revenue of cover reaching $31.1M.

Length of Stay: The average length of stay is 7.25 hours, though the distribution shows a significant peak in the 30-50 second category, indicating a high volume of quick outpatient procedures or emergency screenings.

🛠️ Technical Implementation

1. Data Visualization & UI
KPI Header: Implemented a clean, top-row KPI card system for immediate visibility of vital stats (Total Patients, Cost per Visit, etc.).

Demographic Segmentation: Used a Donut chart for Gender distribution and a Bar chart for Age-based Length of Stay to provide a multifaceted view of the patient population.

Advanced Filtering: Added slicers for Year/Month, County, Gender, Age Group, Race, and Payer for granular data exploration.

2. DAX & Analytics
Readmission Rate: Created a measure to calculate the percentage of unique patients who returned for additional admissions.

Financial Coverage: Developed logic to compare "Total Revenue" vs. "Revenue of Cover" to determine the 31% insurance coverage rate.

Time Intelligence: Utilized line charts to track the correlation between Average Cost per Visit and Length of Stay over a 10-year historical period (2012–2022).

📊 Dashboard Preview
![Healthcare Dashboard](images/hospital.png)

💡 Recommendations

Reduce Readmissions: Implement a follow-up protocol for the 854 readmission patients to understand if early discharge is contributing to the high return rate.

Payer Strategy: Since only 31% of costs are covered by insurance, the hospital should review billing efficiency or negotiate better rates with private payers like Blue Cross Blue Shield.

Resource Allocation: With admissions peaking in February and March, the hospital should consider temporary staffing increases during these months to maintain the average length of stay.
