# ☕ Global Coffee Market Analysis (1990–2019)

An end-to-end data analytics project exploring 30 years of global coffee production, trade, imports, and consumption data using Python, Pandas, Jupyter Lab, and Tableau.

This project combines data cleaning, exploratory data analysis (EDA), feature engineering, interactive dashboard design, and executive storytelling to uncover how coffee moves through the global economy.

---

## 📊 Project Overview

The coffee industry is one of the world's most globally interconnected agricultural markets.

Using historical data from the International Coffee Organization (ICO), this project investigates:

* Which countries dominate coffee production?
* How do global trade flows compare with domestic consumption?
* Which nations depend entirely on imports?
* How has the market evolved over the last three decades?

The final deliverables include:

* A cleaned analytical dataset (`coffee_master.csv`)
* A Python EDA notebook
* An interactive Tableau dashboard
* An executive business report

---

## 🛠 Tech Stack

| Tool            | Purpose                        |
| --------------- | ------------------------------ |
| Python          | Data cleaning & transformation |
| Pandas          | Data wrangling                 |
| NumPy           | Numerical operations           |
| Jupyter Lab     | Exploratory analysis           |
| Matplotlib      | EDA visualizations             |
| Tableau Desktop | Interactive dashboard          |
| Git & GitHub    | Version control & portfolio    |

---

## 🔍 Analytical Workflow

### 1. Data Preparation

Four independent datasets were consolidated into a unified analytical model:

* Production
* Exports
* Imports
* Consumption

Key preparation steps included:

* Country name harmonization
* Crop-year standardization
* Data type corrections
* Missing value investigation
* Dataset integration

---

### 2. Data Quality Investigation

Several real-world data issues were identified during the analysis process.

Examples include:

* Sentinel values (`-2147483648`) embedded within export records
* Missing observations in historical trade data
* Inconsistent temporal formats across source files
* Structural null values requiring analytical interpretation

Rather than imputing artificial values, missing observations were preserved whenever they represented genuine uncertainty.

---

### 3. Exploratory Data Analysis

The EDA phase focused on:

* Global production concentration
* Export intensity
* Import dependency
* Country segmentation
* Long-term market evolution

Additional derived metrics were created to support deeper analysis and interpretation.

---

## 🌍 Interactive Tableau Dashboard

The dashboard was designed around a simple analytical workflow:

### Explore → Select → Investigate

Users can:

* Explore countries through an interactive world map
* View Production, Exports, Imports, and Consumption metrics
* Analyze historical market behavior by country
* Compare different national market structures

### Dashboard Components

* KPI Summary Panel
* Interactive World Map
* Coffee Market Dynamics Trend Analysis
* Contextual Tooltips

---

## 📈 Key Insights

### Brazil's Exceptional Market Position

Brazil simultaneously leads:

* Global production
* Global exports
* Domestic consumption

making it the most influential actor in the coffee value chain.

### Highly Concentrated Supply

A small group of countries accounts for the majority of global coffee production, creating significant supply-chain concentration risk.

### Distinct Country Roles

The analysis revealed three broad market profiles:

* Producers
* Producer-Consumers
* Pure Importers

demonstrating that countries participate in the coffee economy in fundamentally different ways.

---

## 📁 Repository Structure

```text
Global-Coffee-Market-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── global-coffee-market-analysis.ipynb
│
├── dashboard/
│   └── coffee_dashboard.twbx
│
├── reports/
│   └── Global_Coffee_Market_Analysis_Executive_Report.pdf
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Data Quality Assessment
* Feature Engineering
* Interactive Dashboard Development
* Data Storytelling
* Business Insight Generation

---

## 📸 Dashboard Preview

> Add a dashboard screenshot here.

![Dashboard Preview](C:\Users\wwwCo\Desktop\Coffe Market Analisis\images\dashboard_preview.png)

---

## 📄 Executive Report

A detailed executive report documenting methodology, findings, dashboard design decisions, and business implications is included in the repository.

---

## 👤 Author

**Ezequiel Gonzalez**

Aspiring Data Analyst passionate about analytics, visualization, and transforming raw data into actionable insights.

LinkedIn: [[Add Link](https://www.linkedin.com/in/ezequiel-gonzalez-data/)]

GitHub: [[Add Link](https://github.com/arielezequielwork)]
