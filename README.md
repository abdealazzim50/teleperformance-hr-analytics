# 📊 HR Attrition & Retention Analytics Dashboard

An interactive, end-to-end HR Analytics Dashboard created with **Power BI**, **Power Query**, and **Excel**. This project analyzes employee turnover, workforce demographics, satisfaction metrics, and career progression patterns to provide actionable retention strategies.

---

## 🖼️ Dashboard Preview

### 1. Executive Overview
![Overview Page](screenshots/overview.png)

### 2. Behavior & Culture Insights
![Behavior Page](screenshots/behavior.png)

### 3. Career Progression & Compensation
![Progress Page](screenshots/progress.png)

---

## 🎯 Key Business Insights

* **Early-Stage Turnover Gap:** Over **72%** of role-related attrition occurs within the first **2 years** of stepping into a new role (`Role Expectation Gap`). This proves that onboarding alignment and initial training impact turnover more than long-term stagnation.
* **Demographics Impact:** High attrition velocity is concentrated among early-career employees aged 25–34, particularly within the Sales department.
* **Compensation & Satisfaction:** Mapped salary scaling across job levels (`Junior` to `Senior` & `Leader`) to evaluate fair pay distribution against job satisfaction ratings.

---

## 🛠️ Tech Stack & Methods

* **Data Cleaning & ETL:** Power Query & Excel (Data transformation, type casting, band creation).
* **Data Modeling:** Star Schema (`employee_fact`, `employee_dim`, `jop_dim`, `emp_survey`).
* **DAX Formulas:** Dynamic measures for Attrition Rates, Stagnation Metrics, and Tenure Averages.
* **UI/UX Design:** Dark Glassmorphism theme designed for high readability and zero redundant KPIs.

---

## 🚀 How to View
1. Clone or download this repository.
2. Open `pbix/HR_Attrition_Analytics.pbix` using **Power BI Desktop**.
