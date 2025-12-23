# 💊 Prescribers Redux: Prescriber Patterns and Trends

A Python data analysis project exploring prescribing behavior using the CMS Prescriber dataset, analyzing patterns in prescription counts, specialty categories, and provider performance.

---

## 📌 Project Overview

**Prescribers Redux** analyzes a publicly available prescriber dataset to investigate patterns in prescription behavior across different provider specialties. The goal is to identify trends that may inform healthcare analytics, pharmacy utilization, or policy-oriented reporting.

This analysis includes identifying top prescribers, examining specialty differences in prescription volume, and visualizing overall distribution behavior.

---

## 🎯 Project Objectives

- Identify the **top prescribers** by volume.
- Compare prescription counts between **specialty categories**.
- Use Python and data visualization to reveal prescriptive trends.
- Provide insight into how prescribing behavior varies across provider types.

---

## 🧰 Tools & Technologies

- Python  
  - pandas (data wrangling)  
  - matplotlib / seaborn (data visualization)  
- Jupyter Notebook for step-by-step analysis  
- GitHub for version control and project documentation

---

## 📊 Analysis Workflow

### 1. Data Ingestion & Cleaning  
- Load the CMS Prescriber dataset
- Inspect and clean missing or malformed entries
- Ensure consistent formats for provider specialty and prescription data

### 2. Feature Engineering  
- Extract meaningful fields such as:
  - Total prescriptions
  - Specialty categories
  - Ranking of providers

### 3. Comparative Analysis  
- Identify the **top 10 prescribers** by total prescriptions
- Compare average prescriptions by specialty

### 4. Visualization  
- Bar charts and comparative graphs to illustrate:
  - Top prescriber performance
  - Prescription distribution across specialties

---

## 📂 Repository Contents

- `PrescribersRedux.ipynb` — Jupyter Notebook containing the analysis workflow
- Dataset location or reference details (if local/directory included)
- Output visuals showing key results

---

## 📈 Key Insights & Findings

- Certain providers demonstrate **significantly higher prescription volumes**.
- Prescription behavior varies widely across specialty categories.
- Visualizations highlight where the highest concentrations of prescriptions occur, useful for healthcare analytics or policy review.

> *Note:* Additional metrics (e.g., average prescriptions per provider, trends by drug category) could deepen insights.

---

## 📍 How to Run This Project

1. Clone this repository.
2. Install Python and required libraries (`pandas`, `matplotlib`, etc.).
3. Open `PrescribersRedux.ipynb` in Jupyter Notebook.
4. Run each cell sequentially to reproduce the analysis and graphs.

---

## 🚀 Potential Next Steps

- Break down prescribing patterns by drug categories.
- Introduce statistical summaries (mean, median, variance) by specialty.
- Build interactive dashboards using Plotly or Power BI.
- Link prescriber behavior to geographic regions or patient outcomes.

---

## 👨🏾‍💻 Author

**Walter Lovett**  
Data Analytics practitioner with experience in real-world analytics workflows and reporting.
