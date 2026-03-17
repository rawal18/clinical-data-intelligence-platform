# 🏥 Clinical Data Intelligence Platform

An interactive healthcare analytics dashboard that turns raw patient CSV data into visual insights, AI-generated analysis, and actionable recommendations — with no coding required to use.

**[▶ Live Demo](https://github.com/rawal18/clinical-data-intelligence-platform)** &nbsp;|&nbsp; **Built with:** HTML · CSS · JavaScript · Chart.js · AI Insights Engine

---

## 📸 Preview

> Upload any healthcare CSV → filters update all charts instantly → click Generate AI Insights for a full written analysis.

---

## ✨ Features

- **Universal CSV Upload** — works with any healthcare dataset including Kaggle, CMS, CDC, and custom hospital exports
- **4 KPI Cards** — Total Patients, Avg Length of Stay, Readmission Rate, Avg Cost per Patient
- **5 Interactive Charts** — Department volume, Insurance breakdown, Monthly admissions trend, Top diagnoses, Age distribution
- **Smart Filters** — Filter by date range, department, gender, and insurance type; all charts update instantly
- **AI Insights Engine** — One-click analysis that generates a 6-point written summary with an adaptive recommendation
- **Patient Data Table** — Last 10 records with color-coded outcome badges
- **Fully Responsive** — Works on desktop, tablet, and mobile

---

## 🧠 AI & Prompting Techniques

This project demonstrates real-world AI prompt engineering techniques:

| Technique | Application |
|---|---|
| **Role Prompting** | AI persona set as senior healthcare data analyst |
| **Chain of Thought** | Insights generated in a structured 6-step reasoning sequence |
| **Constraint Prompting** | AI only references statistics from the actual loaded data |
| **Structured Output** | Every insight follows a consistent label → finding → recommendation format |
| **Conditional Prompting** | Recommendation adapts based on what the data shows (readmissions vs. capacity vs. insurance) |
| **Context Injection** | Filtered data is re-injected on every analysis so insights always match the current view |

---

## 📂 Dataset Compatibility

The dashboard auto-detects and maps column names from multiple formats:

| Source | Supported Columns |
|---|---|
| Custom / Sample | `patient_id`, `admission_date`, `department`, `diagnosis`, `insurance_type`, `total_cost` |
| Kaggle Healthcare Dataset | `Date of Admission`, `Medical Condition`, `Insurance Provider`, `Billing Amount` |
| CMS / CDC Exports | Auto-mapped via column normalizer |

---

## 🚀 How to Use

1. Download `clinical-data-intelligence-platform.html`
2. Open it in any browser (Chrome, Safari, Firefox)
3. Click **"Choose CSV File"** and upload your healthcare dataset
4. Use the filters to explore specific departments, date ranges, or demographics
5. Scroll down and click **"Generate AI Insights"** for a full written analysis

> **No installation. No server. No internet required after first load.**

---

## 🗂️ Files

```
clinical-data-intelligence-platform/
├── clinical-data-intelligence-platform.html   # Complete app (single file)
└── sample_ehr_data.csv                        # Sample dataset to test with
```

---

## 💡 Sample Questions This Dashboard Answers

- Which department sees the most patients?
- What is the readmission rate and is it above benchmark?
- Which insurance type covers the majority of patients?
- Is patient volume trending up or down over time?
- What is the most common diagnosis and average cost?
- Which age group has the highest patient volume?

---

## 🛠️ Built With

- **HTML5 / CSS3 / Vanilla JavaScript** — zero frameworks, fully portable
- **Chart.js 4.4** — bar, line, doughnut, and horizontal bar charts
- **Custom AI Insights Engine** — JavaScript-based analysis with 6 prompting techniques
- **CSV Column Normalizer** — auto-maps 10+ column naming conventions

---

## 📈 What This Demonstrates (For Recruiters)

This project showcases skills directly relevant to a **Data Analyst** role:

- ✅ Data ingestion and parsing (CSV handling)
- ✅ KPI definition and metric calculation
- ✅ Data visualization (5 chart types)
- ✅ Filter logic and dynamic data slicing
- ✅ AI prompt engineering (6 techniques)
- ✅ Pattern recognition and anomaly flagging
- ✅ Translating data into business recommendations
- ✅ Building tools that non-technical stakeholders can use

---

## 👤 Author

Built as part of a data analytics portfolio.  
Feel free to fork, use, or reach out with questions!

---

*Part of my Data Analyst Portfolio — see other projects in my repositories.*
