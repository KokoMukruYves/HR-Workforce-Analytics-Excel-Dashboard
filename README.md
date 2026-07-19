# HR-Workforce-Analytics-Excel-Dashboard
An interactive HR Analytics Dashboard built in Microsoft Excel using Power Query, PivotTables, PivotCharts, KPI cards, and dynamic slicers to transform raw workforce data into actionable business insights and strategic HR recommendations.

<img width="1067" height="562" alt="ezgif com-gif-maker" src="https://github.com/user-attachments/assets/347b0e87-22c2-48aa-8604-30a8804f40f3" />
 

---

# 📖 Project Overview

This project was developed as part of the **DataVerse Africa – July 2026 HR Analytics Challenge**.

The objective was to transform a raw HR dataset into an interactive decision-support system capable of delivering evidence-based workforce insights. The project demonstrates how Microsoft Excel can be used as a Business Intelligence (BI) tool by integrating automated data preparation, interactive dashboards, and executive-level storytelling.

The solution combines **Power Query**, **Excel formulas**, **PivotTables**, **PivotCharts**, and **interactive slicers** to create a dynamic reporting environment. Once a new dataset replaces the original source, users simply click **Refresh All**, and every transformation, KPI, PivotTable, and visualization updates automatically.

---

# 🎯 Project Objectives

- Clean and standardize raw HR data using Power Query.
- Build a fully automated and refreshable reporting workflow.
- Design an interactive Excel dashboard for workforce monitoring.
- Analyze key HR metrics and workforce trends.
- Generate actionable business insights and strategic HR recommendations.
- Demonstrate Excel's capability as a Business Intelligence solution.

---

# 📂 Dataset Description

The analysis is based on an employee dataset containing **311 employee records** across **39 variables**, covering the period **2006–2019**.

The dataset contains information on:

- 👤 Employee demographics (Employee ID, Gender, Date of Birth)
- 💼 Employment history (Hire Date, Termination Date, Department, Manager)
- 💰 Compensation (Salary)
- 📢 Recruitment sources
- 😊 Employee engagement and satisfaction
- ⭐ Performance evaluations
- 📅 Attendance and absence records

The raw dataset contained multiple data quality issues that were addressed before analysis to ensure accurate reporting and reliable business insights.

---

# 🔄 Data Preparation (ELT Process)

The project followed a structured **Extract – Load – Transform (ELT)** workflow.

## 1️⃣ Extract

- Imported the HR dataset from a single Excel worksheet.

## 2️⃣ Load

- Loaded the dataset into Excel.
- Processed and automated all transformations using **Power Query**.

## 3️⃣ Transform

The following data quality improvements were implemented:

- ✅ Recalculated employee age using the termination date or **31 December 2019** for active employees.
- ✅ Recalculated employee tenure using the same reference dates.
- ✅ Completed missing **ManagerID** values using **XLOOKUP**.
- ✅ Standardized text capitalization across categorical fields.
- ✅ Corrected inconsistent employment status values.
- ✅ Removed termination reasons assigned to active employees.
- ✅ Removed invalid employee records.
- ✅ Created analytical fields including:
  - Age Group
  - Termination Year
  - Tenure (Years)

After validating the transformed dataset, an interactive dashboard was developed using KPI cards, PivotTables, PivotCharts, and slicers.

---

# 📈 Executive Workforce Summary

| KPI | Value |
|------|------:|
| Total Employees | **310** |
| Active Employees | **207** |
| Terminated Employees | **103** |
| Turnover Rate | **33.2%** |
| Average Age | **39.6 Years** |
| Average Tenure | **5.4 Years** |
| Average Engagement | **4.1 / 5** |
| Average Satisfaction | **3.9 / 5** |
| Gender Ratio (M:F) | **1.30** |
| Average Salary | **$69,033.80** |

### 💡 Executive Insight

The organization employs **310 individuals**, of whom **207 remain active**, while **103 employees have separated** from the company, resulting in an overall turnover rate of **33.2%**.

Employee engagement remains relatively strong (**4.1/5**), although overall satisfaction is slightly lower (**3.9/5**), suggesting opportunities to further enhance the employee experience. With an average employee tenure of **5.4 years** and an average workforce age of **39.6 years**, the dashboard provides valuable insights into workforce stability, retention, compensation, and organizational performance.

These KPIs serve as a high-level summary for HR leaders, enabling rapid assessment of workforce health and supporting strategic decision-making.

---
## 📌 Executive Summary: Key Insights & Strategic Recommendations

The dashboard transforms raw HR data into actionable workforce intelligence by answering eight strategic business questions. The table below summarizes the key findings, business insights, and recommended actions that HR leaders can use to support evidence-based decision-making.

| Business Question | Key Findings | Business Insight | Strategic Recommendation |
|-------------------|--------------|------------------|--------------------------|
| **1. Overall Turnover Rate** | The organization recorded an overall turnover rate of **33.2%**. Software Engineering experienced the highest turnover, while the Executive Office reported no employee departures. | Employee turnover is concentrated in specific departments rather than being evenly distributed, suggesting department-specific retention challenges. | Conduct a retention assessment within Software Engineering by reviewing exit interviews, workload, compensation, career progression, and leadership practices. |
| **2. Termination Trend (2010–2018)** | Employee terminations peaked in **2016**, with elevated separation levels also observed during **2015**. | Consecutive years of increased departures may reflect organizational restructuring, operational changes, or external labor market conditions. | Review organizational events during 2015–2016 and incorporate lessons learned into future workforce planning. |
| **3. Employee Tenure** | The overall average tenure is **5.4 years**. IT employees leave earlier than Production employees. | Higher turnover among IT professionals may reflect stronger external demand for technical talent or limited career development opportunities. | Strengthen retention initiatives for technical employees through career growth, learning opportunities, and competitive compensation. |
| **4. Recruitment Effectiveness** | **Indeed** and **LinkedIn** generated the highest number of hires and the largest proportion of high-performing employees. | Recruitment sources differ not only in hiring volume but also in candidate quality. | Continue investing in high-performing recruitment channels while monitoring quality-of-hire metrics. |
| **5. Gender Pay Analysis** | Male employees earn an average salary of **$71,080.21**, compared with **$68,416.48** for female employees. | Salary differences should be interpreted cautiously because role, tenure, and seniority were not controlled. | Conduct a comprehensive pay equity assessment using comparable job roles and experience levels. |
| **6. Turnover by Age Group** | Employees aged **30–44 years** experienced the highest turnover rate. | Losing experienced mid-career professionals may increase recruitment costs and reduce organizational knowledge retention. | Develop targeted retention programs focusing on career advancement, recognition, and flexible work arrangements. |
| **7. Engagement & Satisfaction** | The Executive Office achieved the highest engagement score, while Software Engineering recorded the highest satisfaction score. | Employee engagement and satisfaction do not necessarily move together, indicating different drivers for each measure. | Benchmark high-performing departments and implement tailored initiatives to improve engagement and satisfaction across the organization. |
| **8. Performance & Retention** | Employees rated **Exceeds Expectations** remain with the organization longer (**6.2 years**) than employees rated **Fully Meets Expectations** (**5.3 years**). | High-performing employees demonstrate greater organizational loyalty and contribute to long-term organizational performance. | Retain top talent through succession planning, recognition programs, career development, and performance-based rewards. |


## 📌 V. Tools & Technologies
-	Microsoft Excel;
-	Power Query;
-	PivotTables & PivotCharts for detailed company-level insight;
-	Excel Formulas;
-	Dynamic Slicers for interactive exploration;
-	Figma and Microsoft PowerPoint (for Dashboard Designing);
-	AI-generated icons.

## VI. Conclusion
This project demonstrates how structured data preparation and interactive dashboard design can convert raw HR data into meaningful business intelligence. Beyond presenting workforce metrics, the dashboard supports strategic decision-making by identifying trends in employee turnover, recruitment effectiveness, compensation, engagement, and retention.
The solution was designed as a fully automated reporting system. Through Power Query, users can replace the source dataset and refresh the workbook to update all transformations, KPIs, PivotTables, charts, and dashboard visuals without manual intervention. This approach makes the dashboard suitable not only as a learning project but also as a scalable template for organizational HR reporting.
## Challenge Info

  o Organizer: DataVerse Africa
  
  o Theme : HR Analaytics Jully 2026 Challenge
  
  o Duration : 


## 🔗 For Paternship and Collaboration

Contact me  :

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/koko-mukuru-yves-98621a14a) 
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kokomukuruy@gmail.com)

---
<p align="center">
  <i>"Turning Raw Data into actionable insight for better decision marking."</i>

</p>

**© 2026 Koko Mukuru Yves**. All right reserved !
