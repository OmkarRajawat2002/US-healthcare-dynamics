# 🏥 U.S. Healthcare Dynamics: An In-Depth Analysis (2019–2020)

A comprehensive Power BI dashboard project analyzing key metrics across the U.S. healthcare system — covering hospital performance, patient outcomes, payer-provider dynamics, and expense trends.

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Executive Summary** | High-level KPIs: total expenses ($13M), insurance revenue ($7.5M), patient revenue ($1.5M), and total patients (5,117) |
| **Hospital Insights** | Performance metrics across 11 hospitals — AR, ARGE ratio, IPTP ratio, bad debts, and CPT unit distribution |
| **Patient Analysis** | Demographics, blood groups, lifestyle factors (tobacco, diet, alcohol, exercise), and geographic distribution |
| **Payer-Provider Analysis** | 931 distinct providers across 4 regions, specialty breakdown, FTE count, and monthly activity trends |
| **Monthly Expenses Overview** | Gross vs. adjusted expense trends with an interactive adjustment factor slider |

---

## 🗂️ Repository Structure

```
us-healthcare-dynamics/
│
├── dashboards/
│   └── US_Healthcare_Dynamics.pbix       # Main Power BI dashboard file
│
├── docs/
│   ├── US_Healthcare_Report.pdf          # Full project report (PDF export)
│   └── screenshots/                      # Dashboard page screenshots
│
├── data/
│   └── README.md                         # Data sources & schema documentation
│
├── src/
│   └── DAX_Measures.md                   # All DAX measures used in the report
│
├── .gitignore
├── CHANGELOG.md
└── README.md
```

---

## 🔑 Key Metrics at a Glance

- **Total Expenses:** $13.0M
- **Total Payments:** $9.0M
- **Insurance Revenue:** $7.5M
- **Patient Revenue:** $1.5M
- **Total Patients:** 5,117 (across 49 states, 531 cities)
- **Average Patient Age:** 44
- **Distinct Providers:** 931 | **FTE Employees:** 712
- **Total Hospitals:** 11 | **Account Receivable:** $4.0M

---

## 🏗️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualization |
| **DAX** | Custom measures and KPI calculations |
| **Power Query (M)** | Data transformation and cleansing |
| **Microsoft Bing Maps** | Geographic patient distribution |

---

## 📁 How to Open the Dashboard

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/us-healthcare-dynamics.git
   ```
3. Open `dashboards/US_Healthcare_Dynamics.pbix` in Power BI Desktop
4. Explore each dashboard page using the left-side navigation tabs

---

## 📌 Dashboard Highlights

### Executive Summary
- Monthly expense trends peaking at **$4.5M in Jan 2020**, declining steadily through year-end
- **Medicare (122K)** and **Commercial (108K)** insurers dominate CPT unit volume
- Monthly revenue KPIs tracking against a $201.2K goal benchmark

### Hospital Insights
- **Angelstone Community Hospital** leads with 102K CPT units and $1.7M AR
- Average IPTP Ratio: **83%** | Average ARGE Ratio: **31%**
- Genesis Hospital Center outlier: 90% IPTP / 19% ARGE

### Patient Analysis
- **O+ (1,944)** and **A+ (1,740)** are the most common blood groups
- **88%** of patients are non-tobacco users; **75%** follow a healthy diet
- Female patients (3,006) outnumber male patients (2,111)

### Payer-Provider Analysis
- **South region** has the highest physician count (693), followed by West (662)
- **Internal Medicine** is the largest specialty: 224 providers, 75,510 CPT units
- Provider activity and CPT volumes declined sharply after Jan 2020 (COVID-19 impact)

### Monthly Expenses
- Gross expenses peaked at **$9.53M** (pre-2020) with significant drop through mid-year
- Adjusted expense model available with a configurable **adjustment factor slider**

---

## 📄 License

This project is for educational and portfolio purposes.  
Data used is anonymized/simulated for analysis demonstration.

