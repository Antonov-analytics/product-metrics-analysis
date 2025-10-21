# Product Metrics & Anomaly Analysis

### 🧩 Overview
This project focuses on analyzing user activity and retention metrics for a **mobile news feed application**.  
Users can browse posts, like them, and interact with the content that matches their interests.  

Two key analytical studies were conducted:  
1. **Retention Rate Analysis** — to measure user retention and evaluate the impact of a marketing campaign.  
2. **Anomaly Detection** — to investigate a sudden drop in user activity observed on August 24, 2025.

---

### 1. Retention Rate Analysis (`Retention Rate.ipynb`)
This notebook examines how user engagement changed before and after the **marketing campaign** held on **August 15, 2025**.  
The analysis includes:
- calculation of **DAU** and **Retention Rate (RR)**;
- cohort analysis and **heatmap visualization**;
- comparison between **ads** and **organic** traffic;
- identification of key retention patterns.

**Key Findings:**
- Average day-1 retention ≈ **33%**;  
- Ads cohort retention = **3.97%**;  
- Organic cohort retention = **29.9%**, with more stable long-term behavior.  

*File:* [`Retention Rate.ipynb`](./Retention%20Rate.ipynb)

---

### 2. Anomaly Detection (`Search anomalies.ipynb`)
This notebook investigates a **sudden drop in DAU** detected on **August 24, 2025**.  
By comparing user activity across countries and cities, the analysis reveals that the issue was **localized to Russia**,  
specifically to **Moscow** and **Saint Petersburg**, suggesting a **technical failure or incomplete data upload**.

**Key Findings:**
- The anomaly was **not behavioral**, but **regional**.  
- Activity in Moscow and St. Petersburg was missing on the affected date.  
- No gender- or OS-based anomalies detected.

*File:* [`Search anomalies.ipynb`](./Search%20anomalies.ipynb)

---

### ⚙️ Tools & Technologies
![Python](https://img.shields.io/badge/Python-20A5A8?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-20A5A8?style=flat&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-20A5A8?style=flat&logo=clickhouse&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-20A5A8?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-20A5A8?style=flat&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-20A5A8?style=flat&logo=plotly&logoColor=white)
![Redash](https://img.shields.io/badge/Redash-20A5A8?style=flat&logo=redash&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-20A5A8?style=flat&logo=jupyter&logoColor=white)

---

### Summary
- Marketing campaigns may lead to short-term traffic spikes but weak retention.  
- Organic users show higher and more stable engagement.  
- The DAU anomaly on August 24, 2025 was caused by **localized data loss or access issues** in major Russian cities.

---

### Usage
All project materials are available for review only.  
No database connection is required to explore the analysis.

1. Open the Jupyter notebooks (`Retention Rate.ipynb` and `Search anomalies.ipynb`) to review the SQL logic, visualizations, and conclusions.  
2. PDF versions of the notebooks are also available for quick viewing (`Retention Rate.pdf`, `Search anomalies.pdf`).  
3. No code execution is needed — the notebooks are fully self-contained and illustrate the analytical workflow.

---

### 📂 Repository structure

- Retention Rate.ipynb        # Retention analysis and cohort heatmaps
- Retention Rate.pdf          # PDF version of the retention analysis
- Search anomalies.ipynb      # Anomaly detection by geography
- Search anomalies.pdf        # PDF version of the anomaly analysis
- README.md                   # Project description

*Author:* **Aleksandr Antonov**
