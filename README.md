# 📊 HR Analytics Dashboard — Workforce Insights. People Decisions.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

> An interactive HR analytics dashboard built in Power BI to uncover employee attrition patterns, workforce demographics, and high-risk roles — enabling data-driven people decisions.

---

## 🧾 Project Overview

This dashboard analyses employee attrition across departments, job roles, salary bands, age groups, and overtime status. It helps HR teams and business leaders identify where talent loss is highest, which roles carry the most risk, and how compensation and workload contribute to attrition.

**Dataset:** IBM Watson HR Employee Attrition dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`)

---

## 📸 Dashboard Preview

![HR Dashboard](https://github.com/ayeshasana0355/HR-Dahboard/blob/main/HR%20dashboard.pdf?raw=true)

> For the best view, download the `.pbix` file and open it in Power BI Desktop.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Attrition Rate | 16.1% |
| Average Tenure | 7.01 years |
| Average Income | $6.50K |

---

## ✨ Key Features

### 🔢 KPI Cards
- Total Employees, Attrition Rate, Average Tenure, Average Income
- Instant snapshot of overall workforce health

### 📉 Attrition Analysis
- Attrition by Department — Research & Development leads with 133 cases
- Attrition by Job Role — Laboratory Technicians (62) and Sales Executives (57) highest
- Top 5 Highest-Risk Roles table with attrition rate by role
- Sales Representatives carry the highest attrition rate at 0.40

### 👥 Workforce Demographics
- Age Group Distribution donut chart (18–25, 26–35, 36–45, 46+)
- Largest group: 26–35 age band at 41.22%
- Salary Band Split: Low (50.95%), Medium (29.93%), High (19.12%)

### ⏱️ Overtime Impact
- Employees working overtime have a 30.5% attrition rate vs 10.4% for those who don't
- Clear signal that work-life balance is a key retention driver

### 🎛️ Dynamic Filters
- Department slicer
- Job Role slicer

---

## 🛠️ Technical Highlights

### DAX Measures
- Custom Attrition Rate calculation per department, role, and overtime status
- Average Tenure and Average Income measures
- Role-level attrition rate for the Top 5 High-Risk table

### Power Query (ETL)
- Data type corrections and null handling
- Salary band classification (Low / Medium / High) from raw income data
- Age group binning (18–25, 26–35, 36–45, 46 Above)

### Data Modelling
- Clean single-table model with calculated columns and measures
- Optimised for slicer cross-filtering across all visuals

---

## 🔍 Key Findings

- Research & Development has the highest absolute attrition (133 employees)
- Sales Representatives have the most alarming attrition rate (0.40 — nearly 1 in 2 leave)
- Overtime is strongly linked to attrition — 30.5% vs 10.4% for non-overtime employees
- Low salary band employees make up over 50% of the workforce, suggesting compensation is a risk factor
- The 26–35 age group dominates the workforce, making them the most critical retention target

---

## 📁 Project Structure

```
HR-Dahboard/
├── HR dashboard.pbit        # Power BI Template file
├── HR dashboard.pdf         # Dashboard PDF preview
├── WA_Fn-UseC_-HR-Employee-Attrition.csv   # Source dataset
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/ayeshasana0355/HR-Dahboard.git
   ```
2. Open `HR dashboard.pbit` in **Power BI Desktop**
3. When prompted, point to `WA_Fn-UseC_-HR-Employee-Attrition.csv` as the data source
4. Click **Refresh** to load the data
5. Use the Department and Job Role slicers to explore

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development |
| DAX | Custom measures & attrition calculations |
| Power Query (M) | Data cleaning & feature engineering |
| IBM Watson Dataset | Source HR data |

---

## 🤝 Connect

If you found this useful or want to discuss the approach, connect on [LinkedIn](https://linkedin.com/in/yourprofile) or open an issue.

---

*Built with 💙 using Power BI | Dataset: IBM Watson HR Employee Attrition*
