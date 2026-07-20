# 📊 Payroll Expenditure & Compensation Analysis | Qinav Company

## 📌 Project Overview

This project delivers a comprehensive exploratory data analysis (EDA) and financial audit of **Qinav Company's** workforce payroll structure. Using historical compensation records stored in an SQLite database, the analysis aims to uncover key cost drivers, evaluate benefit distributions, identify pay disparities, and provide actionable business recommendations to optimize human capital expenditure.

---

## 🎯 Key Business Questions Addressed

* What is the total financial commitment and average spend across all employee compensation tiers?
* How are benefits distributed across the organization, and what percentage of the workforce receives them?
* What are the top job titles and departments driving the highest payroll expenditures?
* How is salary distributed across the workforce, and what does it reveal about organizational pay equity?

---

## 🛠️ Tech Stack & Methods

* **Database Engine:** SQLite (`salarios.sqlite`)
* **Programming & Analytics:** Python 3.x, Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn (Histograms, Boxplots)
* **Environment:** Jupyter Notebook (`payroll_analysis.ipynb`)

---

## 🔑 Key Metrics & Analysis Highlights

| Analysis Metric | Finding / Insight Summary |
| :--- | :--- |
| **Total Headcount** | Full analysis of overall active organizational workforce |
| **Salary Range** | Evaluated lowest and highest global compensation packages |
| **Benefit Penetration** | Proportion of employees receiving non-base pay/benefits |
| **Top Spend Drivers** | Top 10 Job Titles by total aggregate cost to the business |
| **Statistical Spread** | **Median Salary:** ~\$89,000 \| **Q3 Salary:** ~\$133,000 |

---

## 💡 Strategic Business Insights

* **Cost Concentration:** Major operational areas (such as *Public Safety*) represent significant payroll budget proportions relative to total headcount, highlighting critical cost centers.
* **Pay Skewness:** Distribution charts (Boxplot & Histogram) indicate right-skewed data: **50% of employees earn up to $89k**, while upper compensation bands ($133k+) represent the top quartile ($Q_3$).
* **Optimization Potential:** Cross-analyzing compensation metrics with performance, absenteeism, and retention rates offers a clear pathway to refine salary policies without impacting talent retention.

---

## 📂 Repository Structure

```text
├── payroll_analysis.ipynb   # Main Jupyter Notebook with data pipeline & visualizations
├── salarios.sqlite          # SQLite database containing raw payroll records
└── README.md                # Project documentation
