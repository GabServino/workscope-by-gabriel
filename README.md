# Workforce Analytics Dashboard

## Executive Summary

This personal data analytics project shows how HR data can be turned into useful insights through an interactive Power BI dashboard. The dashboard helps users monitor workforce size, employee turnover, hiring activity, employee tenure, and workforce diversity, making it easier to understand workforce trends and support better HR decisions.

The dashboard also includes interactive page navigation and bookmark features, allowing users to move between report pages and switch between chart and table views for selected analyses.


<img width="1212" height="682" alt="Dashbboard 2" src="https://github.com/user-attachments/assets/20149804-1da9-414b-88c5-f61723acdf41" />

## Key Trends & Insights

- The organization currently has **126 active employees**, with **209 total hires** and **83 total leavers**, resulting in an overall **40% turnover rate**.
- Employee turnover peaked at **27% in 2016** before improving in later years, with the lowest turnover recorded at **5% in 2022**.
- Hiring activity reached its highest level in **2016** but has slowed in recent years while employee departures remained relatively consistent, indicating slower workforce growth.
- Most employees have between **3 and 10 years of tenure**, reflecting an experienced workforce, while only **4 employees** have remained with the organization for more than **11 years**.
- Female employees represent 60% of the workforce, while male employees account for 40%.

## Recommendations

Based on the dashboard findings:

- Strengthen long-term employee retention through career development opportunities and employee recognition programs.
- Improve early-career retention by enhancing onboarding processes and collecting feedback from new employees.
- Monitor hiring activity alongside employee departures to better anticipate future staffing requirements.
- Continue monitoring workforce diversity to maintain balanced representation across the organization.

---

## Dataset Used

The dataset contains HR employee records including hiring and termination dates, employment status, departments, salaries, recruitment sources, performance ratings, employee satisfaction, engagement survey scores, absences, and demographic information.

[View Dataset](https://docs.google.com/spreadsheets/d/1Is8f1Hv_vQ742ZwzZGmssHF9N9Z3cmn_/edit?usp=sharing&ouid=112192994012667145760&rtpof=true&sd=true)

---

## Project Overview
This project uses HR employee data to build an interactive Power BI dashboard that helps users analyze workforce trends and key HR metrics. The data was cleaned and transformed using Power Query, and DAX measures were created to calculate workforce KPIs used throughout the report.The dashboard allows users to explore workforce size, employee turnover, hiring activity, employee tenure, and workforce diversity through interactive visualizations.

Insights and recommendations are provided on the following key areas:

- **Workforce Overview:** Analysis of active employees, total hires, total leavers, and overall employee turnover.
- **Employee Turnover & Hiring Trends:** Review of yearly hiring activity, employee departures, turnover rates, and workforce growth over time.
- **Employee Tenure:** Analysis of employee tenure distribution to better understand workforce experience and long-term retention.
- **Workforce Diversity:** Review of gender distribution to monitor workforce representation and support diversity initiatives.

---

## Business Problem

HR teams need an easy way to monitor workforce trends, hiring activity, employee turnover, retention, and workforce growth. When this information is spread across different reports, it becomes difficult to get a complete view of the workforce, identify retention issues, track staffing changes, and support informed workforce planning and hiring decisions.

## Business Questions

The dashboard was designed to answer the following workforce analytics questions:

- How many active employees does the organization currently have?
- What is the overall employee turnover rate?
- Which years experienced the highest employee turnover?
- Is hiring activity keeping pace with employee departures?
- What does the employee tenure distribution look like?
- How balanced is the workforce by gender?

---

## Data Structure & Initial Checks

The Power BI data model consists of:

| Table | Description |
|--------|-------------|
| **HRData** | Main employee table containing hiring dates, termination dates, employment status, department, salary, recruitment source, performance score, satisfaction, engagement, absences, and demographic information. |
| **dCalendar** | Calendar table used for monthly and yearly workforce analysis. |
| **_Measures** | DAX measures used for KPI calculations throughout the dashboard. |

<div align="center">
  
  <img width="630" height="592" alt="image" src="https://github.com/user-attachments/assets/ef46a739-766e-4a5f-9976-1e24e2843e92" />
  
</div>

---

## Data Preparation

Before building the dashboard, the dataset was prepared to improve reporting accuracy. Data preparation included:

- Reviewing the dataset for duplicate records
- Checking for missing values
- Validating hiring and termination dates
- Standardizing data where necessary
- Creating calculated measures using DAX for workforce KPIs

---

## Tools & Skills Used

| Tools | Skills |
|--------|--------|
| Excel | Data Exploration |
| Power Query | Data Cleaning & Transformation |
| Power BI | Dashboard Development |
| Power BI | Data Visualization |
| Power BI | DAX Calculations |
| Power BI | HR Analytics |

---

###  Business Insights

- Current workforce consists of **126 active employees**.
- The organization has recorded **209 hires** and **83 employee departures**.
- Overall employee turnover stands at **40%**.
- These KPIs provide HR stakeholders with a high-level understanding of workforce size, hiring activity, and employee retention.

---

## Employee Turnover & Hiring Trends

<div align="center">
  
<img width="757" height="407" alt="Demo" src="https://github.com/user-attachments/assets/86778016-5765-4b32-bd5f-1de1db8917dc" />
  
</div>

The report includes interactive navigation that allows users to explore workforce metrics over time, including:

- Hiring Activity
- Employee Departures
- Active Employees
- Turnover Rate

###  Business Insights

- Employee turnover reached its highest level in **2016 (27%)**.
- Hiring activity also peaked during **2016**.
- Hiring has gradually slowed while employee departures remained relatively stable.
- Workforce growth has slowed in recent years, highlighting the need for proactive workforce planning.

---

## Department Analysis

I compared workforce metrics across departments to help identify differences in hiring activity, employee turnover, and workforce size. By viewing these metrics in one place, HR stakeholders can better understand workforce trends across departments and identify areas that may need additional attention.

Key metrics include:

* Department headcount
* Total hires by department
* Total leavers by department
* Employee turnover rate by department
* Workforce distribution across departments

---

## Employee Tenure

This page analyzes employee tenure to better understand workforce experience and long-term employee retention. Users can switch between chart and table views using bookmark navigation.

<img width="217" height="262" alt="Chart" src="https://github.com/user-attachments/assets/01f91cf1-2f37-4806-97f8-ddeb25498672" />

<img width="217" height="262" alt="Chart" src="https://github.com/user-attachments/assets/2637da6b-9972-4ec2-8994-dbd298c10c9c" />

| Tenure Group | Employees |
|--------------|----------:|
| 0–2 Years | 39 |
| 3–5 Years | 140 |
| 6–10 Years | 125 |
| 11+ Years | 7 |

### Business Insights

- Most employees fall within the **3–5 year** tenure group.
- A significant number also have **6–10 years** of service, indicating an experienced workforce.
- Only a small portion of employees have remained for more than **11 years**, suggesting opportunities to strengthen long-term retention.

---

## Technical Highlights
- Cleaned and transformed HR data using Power Query
- Built a calendar table to support time-based analysis
- Created DAX measures for workforce KPIs and calculations
- Developed a Power BI data model to support dashboard reporting
- Designed interactive report pages with page navigation and bookmark functionality
- Built interactive visualizations for workforce trends, employee turnover, hiring activity, tenure, and workforce diversity

---

## Other Projects

Interested in more of my work?

**Financial Performance Analytics Dashboard**

🔗 [View Project Here](https://github.com/GabServino/profitlens-by-gabriel/blob/main/README.md)

---

## Author

### Gabriel F. Servino

Aspiring Data Analyst

- GitHub: https://github.com/GabServino

- LinkedIn: https://linkedin.com/in/gabriel-servino
