# employee-attrition-analysis
An end-to-end data analytics project combining data engineering and interactive business intelligence to deliver a data-driven corporate retention strategy.


# Strategic Workforce & Employee Attrition Analytics

## 📋 Project Overview & Objective
This repository contains the end-to-end data engineering pipeline, interactive visualizations, and executive business strategies compiled for the Employee Attrition Analysis Project. The primary objective is to evaluate operational, demographic, and financial risk variables to isolate exact organizational flight risk indicators and convert complex HR matrices into clean, structured insights for senior leadership decision-making.

---

## 🏗️ Repository Architecture & Deliverables
The project bridges the gap between technical data engineering and executive business logic across the following framework:

1. **Data Cleaning Pipeline (`.ipynb`):** Handles comprehensive data auditing, zero-variance column removal, logical contradiction filtering, and data quality normalization.
2. **Exploratory Data Analysis (EDA):** Identification of numerical and categorical dimensions mapping core employee attributes.
3. **Interactive Dashboard (`.twbx`):** Staged in Tableau Public to track dynamic KPIs, compensation disparities, and workforce segments.
4. **Executive Presentation Document (`.pdf`):** A C-suite-ready synthesis outlining operational risk discoveries and strategic action plans.

---

## 📊 Key Analytical Insights Unlocked

* **Total Corporate Roster:** 1,470 employees with a **Baseline Attrition Rate of 16.12%**.
* **The Overtime Catalyst:** Employees working overtime log a staggering **30.53% attrition rate** compared to just 10.44% for the baseline non-overtime cohort. Overtime stands out as the single highest critical risk factor for voluntary exit.
* **The Job Level 2 Paradox:** Mid-tier personnel experience an unfavorable ratio of heavy operational output relative to low overtime payouts, introducing severe burnout risks and vulnerability to competitive poaching.
* **Structural Compensation Disparity:** Departed staff averaged a monthly income of **$4,787** versus **$6,832** for retained staff. This net variance indicates that retention risks are heavily concentrated among undercompensated talent bands.
* **Demographic Exit Velocity:** The **Single** demographic cohort exhibits the highest group-level exit velocity at **25.53%**, making them a highly mobile risk group when exposed to prolonged overtime or salary stagnation.

---

## 🛠️ Data Engineering & Pipeline Infrastructure
To preserve data integrity before dashboard ingestion, the Jupyter Notebook backend executed strict operations:
* **Zero-Variance Column Removal:** Excluded uninformative variables that lacked empirical variation across records.
* **Logical Contradiction Filtering:** Cross-examined structural metrics (tenure, role, and department consistency) to screen out anomalous data quality variances.
* **Data Dictionary Synthesis:** Mapped explicit Dimensions and Measures to enable smooth, interactive dynamic filtering in the Tableau interface.

---

## 🚀 Leadership Action Plan & Strategic Recommendations

1. **Implement Overtime Caps & Audits:** Establish an operational limit on mandatory overtime hours. Trigger an automated management review whenever a specific team logs over a 15% surplus hour threshold.
2. **Correct Job Level 2 Compensation Tiers:** Adjust baseline salary banding or introduce performance-tied quarterly bonuses for Level 2 roles to eliminate market vulnerability and close the retention salary gap.
3. **Deploy Targeted Engagement Metrics:** Utilize Tableau Public action filters to actively monitor high-risk demographic subsets (e.g., Single status + Overtime), initiating proactive career-development checkpoints before critical turnover intervals.

---

## 🧰 Tech Stack Used
* **Data Engineering & EDA:** Python, Jupyter Notebook, Pandas, NumPy
* **Business Intelligence & Visualization:** Tableau Desktop / Tableau Public
* **Documentation & Reporting:** Markdown, presentation-grade PDF frameworks-
