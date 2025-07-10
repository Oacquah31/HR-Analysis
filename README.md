# 🧑‍💼 HR Dashboard – Power BI Project

Interactive Power BI report that provides deep insights into workforce composition, promotion eligibility, job levels, and operational HR metrics. The dashboard helps HR teams and decision-makers monitor employee distribution, identify promotion candidates, and analyze service years and retrenchment risks.

---

## 📘 Data Dictionary

| Column Name         | Description                                     | Data Type |
|---------------------|-------------------------------------------------|-----------|
| Employee_ID         | Unique identifier for each employee             | Integer   |
| Gender              | Gender of the employee                          | Text      |
| Job_Level           | Hierarchical job classification (Level 1–5)     | Text      |
| Years_of_Service    | Total years the employee has worked             | Integer   |
| Promotion_Status    | Indicates if due for promotion                  | Text      |
| Retrenchment_Status | Flag for next retrenchment                      | Text      |
| Distance_From_Office| Distance category (Very Close, Close, Very Far) | Text      |
| Employment_Status   | Active or Inactive worker                       | Text      |

---

## 🚀 Key Features

- 👥 Total employee headcount and gender breakdown  
- 📈 Distribution of employees by job level and service years  
- 🔔 Real-time alerts for promotion and retrenchment eligibility  
- 🧭 Geographic proximity analysis (distance from office)  
- 📊 Promotion pipeline and workforce activity tracking

---

## 📁 Dataset Overview

- **Source**: Internal HR system extract  
- **Format**: Excel/CSV  
- **Rows**: 1,470 employee records  
- **Fields**: 8 core HR attributes

---

## 🔢 Key Metrics (DAX)

- Total Employees  
- % Due for Promotion vs Not Due  
- % Active vs Inactive Workers  
- Gender Distribution (M/F)  
- Distance from Office (Categorical Distribution)  
- Employees by Job Level  
- Years of Service Breakdown  

---

## 💡 Business Insights

- Over **95% of employees** are not yet due for promotion  
- **Retraining & restructuring plans** can be informed by the 8% due for retrenchment  
- **Level 1 and Level 2 roles dominate** the workforce composition  
- Employees **living very far** from the office make up **15%**, which could influence retention strategies  
- **Targeted engagement plans** could help optimize promotion readiness and reduce attrition

---

## 📷 Dashboard Preview

![HR Dashboard](https://github.com/Oacquah31/HR-Analysis/blob/main/hr.png)

> Replace with your actual GitHub image path if hosted in `assets/`.

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query for Data Transformation  
- Excel/CSV for data input

---

## ✅ Conclusion

This HR dashboard enables strategic HR planning by surfacing key metrics related to promotions, employee tenure, job levels, and retrenchment. With intuitive visuals and drill-down capabilities, HR professionals can quickly make data-backed decisions to improve workforce efficiency and employee experience.

---


