# 📊 Human Resources Dashboard — Tableau

A comprehensive HR analytics dashboard built in Tableau, providing both high-level summary insights and detailed employee records for data-driven workforce management.

---

## 🖼️ Dashboard Preview

### Overview
![HR Dashboard Overview](docs/HR%20Dashboard%20overview.png)

### Employee Records
![HR Dashboard Details](docs/HR%20Dashboard%20details.png)

---

## 📋 Project Description

This dashboard was built from the perspective of an HR manager who needs a single, unified platform to analyze workforce data. It covers hiring trends, employee demographics, salary analysis, and a filterable employee records table.

---

## 🗂️ Dashboard Views

### 1. Summary View

The summary view is split into three sections:

#### 🔹 Overview
- Total **hired**, **active**, and **terminated** employee counts
- Year-over-year trend lines for hires and terminations
- Employee breakdown by **department** and **job title**
- HQ vs. Branch comparison (New York = HQ)
- Geographic distribution by **city** and **state** on a map

#### 🔹 Demographics
- Gender ratio (Male / Female) displayed via donut charts
- Employee distribution across **age groups** and **education levels**
- Bubble chart showing headcount per age group
- Education level headcount breakdown
- **Education vs. Performance** correlation matrix (H-School → PhD × Excellent → Needs Improvement)

#### 🔹 Income Analysis
- Salary comparison by **education level** split by gender — highlights pay gaps and patterns
- **Age vs. Salary** scatter plot segmented by department role

---

### 2. Employee Records View

A fully interactive employee list with the following columns:

| Column | Description |
|---|---|
| ID | Unique employee identifier |
| Demographics | Name, age, education level |
| Role | Job title and department |
| Geographics | City and state |
| Salary | Annual compensation |
| Status | Hired / Terminated + start date |
| Length of Employment | Visual bar showing tenure in years |

> All columns support **click-to-filter** for in-depth exploration.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau Desktop / Public** | Dashboard design and visualization |
| **Microsoft Excel / CSV** | Source data preparation |

---

## 📁 Repository Structure

```
hr-dashboard-tableau/
│
├── HR_Dashboard.twx                      # Tableau workbook
│   └── Human Resource Dashboard pr...   # Packaged data source
│
├── datasets/
│   └── dataset.csv                       # Source HR dataset
│
├── docs/
│   ├── HR Dashboard details.png          # Employee records screenshot
│   ├── HR Dashboard overview.png         # Summary view screenshot
│   └── HR_Dashboard_Requirements.pdf     # Full project requirements
│
├── LICENSE
└── README.md
```

---

## 🚀 Getting Started

1. Download or clone this repository
2. Open `HR_Dashboard.twx` in **Tableau Desktop** or **Tableau Public**
3. The dataset is available in the `datasets/` folder as `dataset.csv`
4. Use the navigation icons on the left sidebar to switch between **Overview** and **Details** views

---

## 📌 Key Insights Enabled

- Identify **hiring trends** and **attrition rates** over time
- Spot **gender pay gaps** across education levels
- Understand **workforce demographics** at a glance
- Drill into individual **employee records** with flexible filtering
- Compare **HQ vs. branch** workforce composition geographically

---

## 📄 Requirements

See [`docs/HR_Dashboard_Requirements.pdf`](docs/HR_Dashboard_Requirements.pdf) for the full project user story and functional requirements.

---

## 👤 Author

**Duddukuri Avinash**
3rd Year B.Tech Student — RVR & JC College of Engineering

- 🎓 Passionate about data analytics and visualization
- 📊 Built this project as part of my Tableau portfolio

---

## 📜 License

This project is for portfolio and educational purposes.
