# Adecco-Analysis

---

## Overview

Adecco India is experiencing an increase in employee turnover, especially among junior sales staff. This attrition escalates expenses related to recruitment and onboarding while also diminishing overall productivity.

This initiative analyzes HR data to identify the primary drivers behind employee exits. Its central aim is to uncover patterns linked to departmental challenges, demographic factors, and levels of job satisfaction. The project seeks to deliver actionable insights that enhance employee engagement, reduce attrition, and refine retention strategies.

---

## Dataset

This analysis is based on a synthetic HR analytics dataset sourced from the [Kaggle HR Analytics Case Study](https://www.kaggle.com/datasets/bhanupratapbiswas/hr-analytics-case-study). The dataset emulates real-world employee attrition patterns within a mid-sized organization. It comprises **1,470 employee records** and includes **35 attributes** spanning demographic, job-related, and satisfaction-related factors.

- **Origin**: A publicly accessible Kaggle dataset created to simulate employee data for attrition modeling purposes.  
- **Temporal Scope**: Cross-sectional—capturing a single point-in-time snapshot of employee status.  
- **Key Features**:
  - **Target Variable**: `Attrition` (binary: “Yes” or “No”), indicating whether an employee has left the organization.  
  - **Demographic Information**: `Age`, `Gender`, `MaritalStatus`, and `DistanceFromHome`.  
  - **Job Characteristics**: `Department`, `JobRole`, `JobLevel`, `YearsAtCompany`, and `BusinessTravel`.  
  - **Compensation Data**: `MonthlyIncome`, `HourlyRate`, `DailyRate`, and `PercentSalaryHike`.  
  - **Satisfaction Indicators**: `JobSatisfaction`, `EnvironmentSatisfaction`, `WorkLifeBalance`, and `RelationshipSatisfaction` (each rated on a 1–4 scale).  
  - **Employment History**: `TotalWorkingYears`, `NumCompaniesWorked`, and `YearsSinceLastPromotion`.  
- **Additional Notes**:
  - Variables such as `EmployeeCount` (always 1) and `StandardHours` (always 80) are constant and were omitted from analysis.  
  - The field `Over18` contains only the value “Y” and thus offers no analytical value.  
  - All data is anonymized, synthetically generated, and intended for educational and analytical experimentation.


---
 
## Analytics Outcome

I conducted an analysis of Adecco India’s HR dataset using Microsoft Excel to uncover key drivers behind employee turnover. The approach followed a structured sequence—from initial data setup to insightful visual summaries.

#### **Data Cleaning & Data Pre-processing**
* **Initial Review:** The raw HR dataset was imported into Excel to examine its layout, field labels, and variable formats.
* **Consistency & Deduplication:** Duplicate records were eliminated, and categorical fields—such as department labels and attrition indicators—were standardized for uniformity.
* **Missing Data Handling:** Gaps or irregular entries were detected using filters and logical validation, then corrected to maintain accuracy in subsequent computations.

#### **Exploratory Data Analysis (EDA) Using Fundamental Excel Tools**
* **Key Findings:** Core Excel functions helped address critical business questions:
    * **Overall Attrition Rate:** Formulas like `COUNTIF` and `COUNTA` were leveraged to compute the company-wide turnover percentage.
    * **Department-Level Patterns:** **PivotTables** enabled side-by-side comparison of attrition across departments—including Sales, Engineering, and Marketing—highlighting Sales as a high-risk unit.
    * **Demographic Profiling:** Functions such as **AVERAGE**, **FILTER**, and **PivotTables** revealed characteristics of employees who left, including mean age, salary levels, and gender distribution.
    * **Performance & Tenure Metrics:** Average tenure, overtime frequency, and satisfaction ratings per role were derived using **PivotTables** and `AVERAGEIF`.
    * **Driver Identification:** The `CORREL` function quantified relationships between attrition and variables like job satisfaction, monthly pay, and commute distance.
    * **Visual Trend Exploration:** **Scatter plots** with **trendlines** illustrated associations—such as between Age and Job Satisfaction or Work-Life Balance and Performance Ratings.
    * **Granular Segmentation:** **PivotTables** further dissected attrition by marital status, training participation, and stock option eligibility to expose nuanced behavioral trends.

---
 
## Dashboard
The analysis culminated in a comprehensive, interactive Excel Dashboard that synthesizes key findings into a single, user-friendly interface. This dashboard features a high-level summary metrics card displaying the overall attrition rate, complemented by dynamic visualizations—including bar, pie, and line charts—that depict department-wise turnover, demographic distributions, and trends in employee satisfaction. To support deeper exploration, it integrates responsive slicers that allow stakeholders to filter data by Department, Job Role, and Age Group in real time. Embedded insight callouts clearly highlight the most significant drivers of attrition and offer practical, data-backed recommendations for leadership. Designed as a centralized monitoring tool, the dashboard empowers decision-makers to understand root causes of turnover, track emerging patterns, and assess the impact of future retention strategies.

**⚠️ IMPORTANT: To use this dashboard, open the file `Solution.xlsx` and navigate to the “Dashboard” sheet. All interactive elements function only within this tab.**

- This dashboard delivers a comprehensive view of employee attrition trends at Adecco India, powered by HR analytics.
- Key metrics include overall attrition rate (16.12%), total departures (237), active headcount (1,233), and average tenure of leavers (5.13 years).
- Visuals break down turnover by department, gender, age/education, overtime status, and job role satisfaction.
- Interactive slicers allow filtering by Attrition status, Department, Age, Gender, and Education for real-time insights.
- Designed for leadership and HR teams to identify high-risk segments and prioritize retention strategies.
- Actionable callouts highlight critical drivers—such as low job satisfaction in Sales or high turnover among younger employees.
- Enables data-driven decisions to reduce costs, improve engagement, and sustain workforce stability.

---


---

![Adecco](Adecco.PNG)

---

## Author & Contact
- Name: `Kshitij Saini`
/ [LinkedIn](https://www.linkedin.com/in/kshitij-saini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)


 
