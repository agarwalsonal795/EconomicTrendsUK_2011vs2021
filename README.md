# 📊 Visual Analytics Assessment: Socio-Economic and Ethnic Trends in England and Wales (2011–2021)

This repository contains the **code**, **data**, and **report** for a visual analytics project exploring changes in **ethnic diversity** and **labour market participation** across **England and Wales**, using data from the **2011** and **2021 UK Censuses**.

The project leverages **advanced data analysis** and **interactive visualization techniques** to uncover trends, disparities, and emerging patterns in **employment**, **occupation**, and **industry participation** by **ethnic group** and **region**.

---

## 📌 Project Overview

- **Title:** Visual Analytics Report on Socio-Economic and Ethnic Trends in England and Wales (2011–2021)
- **Main Objective:** Provide **actionable insights** for **policymakers**, **researchers**, and **local authorities** to understand and address evolving **socio-economic inequalities** and **workforce diversity**.
- **Key Methods:**  
  Data Harmonization | Bayesian Statistical Modeling | Dimensionality Reduction (PCA, t-SNE) | Interactive Dashboards

---

## 📂 Repository Contents

- **Data** # Cleaned and harmonized datasets (CSV format)
- **Notebooks** # Jupyter notebooks for data processing and analysis
- **Dashboards** # Tableau dashboards and visualization assets
- **Report_SONAL.pdf** # Full project report with methodology, results, and findings

## 🛠️ Data Preparation and Processing

- **Data Sources:**
  - [2011 Census (Nomis)](https://www.nomisweb.co.uk/)
  - [2021 Census (ONS)](https://www.ons.gov.uk/)

- **Cleaning & Harmonization:**
  - Standardized **ethnicity**, **industry**, and **occupation** categories to the **ONS 8-category schema**.
  - Aligned **geographic boundaries** to 2011 local authority districts using **official ONS lookups**.
  - Addressed **merged districts (2021)** using **Bayesian Dirichlet-Multinomial modeling** for temporal consistency.

- **Processing Tools:**
  - Python: `pandas`, `NumPy`, `PyMC`

---

## 📈 Visual Analytics Approach

### Interactive Dashboards (Tableau)

- **Choropleth Maps:** Spatial distribution and diversity analysis.
- **Stacked Bar Charts & Heatmaps:** Ethnic composition across industries and regions.
- **Tree Maps:** Hierarchical views of employment sectors.
- **Linked Filtering & Tooltips:** For exploratory data analysis.

### Dimensionality Reduction

- **PCA** and **t-SNE** used to reveal:
  - **Clustering patterns**
  - **High-dimensional relationships** in employment and industry participation.

### Bayesian Methods

- Applied **Bayesian modeling** to:
  - Disaggregate **merged local authority districts** (2021 data).
  - **Estimate missing values** for consistent temporal and spatial comparisons.

---

## 📊 Key Findings

- **Diversity Trends:**  
  Significant increase in **industry diversity**, especially among **"White: Other White"** and **"Asian/Asian British"** groups.

- **Unemployment Disparities (2021):**
  - Highest: **"Black/African/Caribbean/Black British"** – **8.01%**
  - Lowest: **"White: Irish"** – **2.62%**

- **Employment Rates:**
  - **"White: Other White"** had the highest employment rate (**73.76%**) in 2021.
  - Non-White groups showed growth in **professional and managerial roles**.

- **Regional Patterns:**
  - **London** and **West Midlands** show highest **ethnic diversity** and **representation**.
  - **Rural** and **northern regions** remain less diverse.

- **Cluster Analysis (PCA / t-SNE):**
  - Revealed both **stable core employment patterns** and **emerging specialization/diversity** in certain areas and ethnic groups.

---

## 🚧 Limitations

- Changes in **local authority boundaries** between 2011 and 2021 required **harmonization** and **model-based estimation**, introducing some assumptions.
- Limited to **census variables**; further analysis would require **additional datasets** (e.g., education, income, health).

---

## 🔭 Future Enhancements

- Incorporate **additional socio-economic variables** (education, health, income).
- Add **statistical significance markers** and **explanatory tooltips** in dashboards.
- Extend **Bayesian modeling** to support **hierarchical geographies** and **uncertainty-aware projections**.

---

## 🎯 Intended Users

- **Policymakers:** For targeted interventions and inclusive economic planning.
- **Researchers & Academics:** To support socio-economic and ethnic trend analysis.
- **Local Authorities:** For regional strategies and resource allocation.
- **Advocacy Groups / Community Leaders:** For evidence-based advocacy and public engagement.

---

## 🚀 Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/ethnic-socioeconomic-trends.git
cd ethnic-socioeconomic-trends
```

2. Explore:
 
 **data** for cleaned datasets

**notebooks** for Python data processing scripts

**dashboards** for Tableau visualization assets

**Report_SONAL.pdf** for the full analysis and findings

3 Open Tableau Dashboards:
Load files from the dashboards/ folder in Tableau Desktop or Tableau Public for interactive exploration.

## 📚 References
2011 Census Data: Nomis - Official Labour Market Statistics

2021 Census Data: Office for National Statistics (ONS)

Full reference list available in Report_SONAL.pdf.
