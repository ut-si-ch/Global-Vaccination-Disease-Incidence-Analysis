#  Global Vaccination & Disease Incidence Analysis
---
##  Project Overview

This project explores the relationship between **vaccination coverage** and **disease incidence** across countries from **1980 to 2023**.The dataset includes vaccination coverage, disease incidence, reported cases, vaccine introductions, and vaccination schedules across WHO regions.The aim is to clean, store, analyze, and visualize the data to derive meaningful **public health insights**.

---

## Objectives

* Understand how vaccination rates impact disease incidence.
* Identify gaps in coverage for critical vaccines.
* Track global progress toward WHO vaccination goals.
* Provide insights through **SQL queries, Python analysis, and Power BI dashboards**.

---

## Dataset

The project integrates multiple datasets:

* **Coverage Data** → Vaccination coverage by country, year, and antigen.
* **Incidence Data** → Disease incidence rates across regions.
* **Reported Cases** → Number of disease cases by year.
* **Vaccine Introduction** → Timeline of vaccine rollouts by country.
* **Vaccine Schedule** → Information on booster rounds, target populations, and administration age.

---

##  Project Workflow

### 1. **Data Cleaning (Python)**

* Handled missing values and outliers.
* Standardized units (% coverage, incidence per 100k population).
* Ensured date and ISO code consistency.

### 2. **SQL Database Setup (MySQL)**

* Normalized schema into **Countries**, **Vaccines**, **Diseases**, and **Fact Tables**.
* Implemented primary & foreign keys for data integrity.
* Loaded cleaned datasets into MySQL for structured storage.

### 3. **Exploratory Data Analysis (Python + SQL)**

* Correlation between vaccination rates and disease incidence.
* Drop-off rates between initial and booster doses.
* Trends in disease cases before and after vaccine introduction.
* Regional disparities in coverage and outcomes.

### 4. **Power BI Dashboards**

*  **Geographical Heatmaps** → Coverage & incidence across countries.
*  **Trend Lines/Bar Charts** → Vaccination & disease trends over years.
*  **Scatter Plots** → Correlation between coverage and incidence.
*  **KPI Indicators** → Track WHO vaccination targets.

---

##  Key Insights (Sample)

* Countries with **>90% vaccination coverage** consistently report lower disease incidence.
* Significant **drop-off between DTP1 and DTP3 doses**, highlighting booster uptake challenges.
* Some WHO regions show **delayed vaccine introductions**, leading to prolonged high incidence.

---

##  Tech Stack

* **Languages**: Python, SQL
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
* **Database**: MySQL (normalized relational schema)
* **Visualization**: Power BI (interactive dashboards)

---

## Repository Structure

```
├── datasets/                # Raw & cleaned data files
├── notebooks/               # Jupyter Notebooks for analysis
├── python_etl_scripts/      # Data cleaning & MySQL upload scripts
├── docs/                    # Documentation & references
├── powerbi/                 # PBIX files for dashboards
└── README.md                # Project documentation
```

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/vaccine-analysis.git
   cd vaccine-analysis
   ```
2. Create and activate a conda environment:

   ```bash
   conda create -n vaccine_proj python=3.9
   conda activate vaccine_proj
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter notebooks for data cleaning & analysis.
5. Load cleaned data into MySQL using provided ETL scripts.
6. Open Power BI dashboards (`.pbix` files) for visual insights.

---

##  Future Scope

* Incorporate **population density & socioeconomic data** for deeper insights.
* Extend to **predictive modeling** for outbreak forecasting.
* Deploy dashboards via **Power BI Service / Streamlit app** for accessibility.

---

## 🤝 Contributions

Contributions are welcome! Please open an issue or submit a pull request for improvements.

---
