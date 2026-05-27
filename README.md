# Amazon E-Commerce Sales Performance & Distribution Analysis

An end-to-end data science and analytics pipeline designed to ingest, clean, and analyze transactional data from Amazon sales report matrices. This repository serves as a practical, hands-on portfolio showcasing data cleaning, exploratory data analysis (EDA), and data visualization utilizing the standard Python scientific computing stack.

## 📂 Project Repository Checklist Status
- [x] Technical Setup & Code Portfolio Ingestion
- [x] System Environment Setup (Google Colab Workspace)
- [x] Clean Data Quality Engineering & Deduplication
- [x] Exploratory Data Analysis (EDA) & Summary Statistics
- [x] Structural Distribution Density Visualization Plotting

---

## 🛠️ Core Technical Stack & Libraries
* **Language Environment:** Python 3 Core Setup
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization & Plotting:** `matplotlib.pyplot`, `seaborn`

---

## 🚀 Analytical Pipeline Architecture

### 1. Data Collection & Structural Understanding
* **Ingestion Model:** Ingested the raw multi-type transactional database (`Amazon Sale Report.csv`) containing complete order logs with categorical and numerical features.
* **Metadata Profile Check:** Evaluated structural layout boundaries, shape variables, columns taxonomy, and memory allocation maps using `.shape` and `.info()` operations.
* **Initial Database Footprint:** Evaluated a raw volume space consisting of **128,975 rows** and **24 unique column attributes**.

### 2. Data Cleaning & Quality Preprocessing
* **Type Safeguards:** Resolved database parser constraints (`DtypeWarning` metrics) across long-tail columns by establishing strict memory management attributes (`low_memory=False`).
* **Handling Missing Fields:** Isolated and systematically processed continuous variables and categorical profiles to prevent skewing numerical aggregates.
* **Deduplication Matrix:** Scrubbed and eliminated duplicate sequence entries to maintain data auditing health integrity.

### 3. Exploratory Data Analysis (EDA) & Metrics Mining
* **Descriptive Statistics:** Executed numerical summary aggregates (`.describe()`) mapping count metrics, deviations, percentiles, min/max limits, and statistical mean targets for core metrics like `Qty` and `Amount`.
* **Categorical Frequency Indexing:** Evaluated business transaction performance trends by tracking data distribution volumes across core statuses including `Shipped`, `Shipped - Delivered to Buyer`, and `Cancelled`.

### 4. Data Visualization & Insights Mapping
* **Plot Type:** Implemented structural density histplot mapping curves powered by Seaborn.
* **Outlier Truncation Filtering:** Configured dynamic percentile boundaries (`df['Amount'].quantile(0.99)`) to truncate extreme transactional anomalies and produce a highly scannable grid analysis chart.
* **Layout Design:** Enhanced look with customized grid overlays, custom color schemas (`color='purple'`), clean density curves (`kde=True`), and optimized axes layout labeling.

---

## 📈 System Execution Checkpoints
All analytical pipeline sequence states have been tested, fully verified, and executed within a clean computational run loop, successfully rendering all graphical outputs and descriptive analysis summaries.
