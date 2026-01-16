## Project Overview

This project analyses NHS Accident & Emergency (A&E) performance data using the most recent
publicly published monthly CSV files available from the official NHS England website. These
datasets include:

- A&E attendances across Types 1, 2, and Other departments  
- Emergency admissions via A&E  
- Patients waiting 4–12 hours and 12+ hours from decision-to-admit (DTA)  
- Trust-level performance indicators  

The data is sourced directly from NHS England’s monthly A&E activity publications, ensuring
that the analysis reflects the latest available operational performance metrics.

# NHS A&E Data Analysis and Interactive Dashboard

This project analyses NHS Accident & Emergency (A&E) performance data and presents the findings through a fully interactive PyQt5 + Plotly dashboard. The work forms part of a university coursework submission and demonstrates skills in data analysis, visualisation, dashboard development, documentation, and version control.

---
## 📁 Data Source

The dataset used in this project was obtained from the most recent monthly CSV files published
by NHS England. These files contain official statistics on A&E attendances, emergency
admissions, and waiting times (including 4–12 hour and 12+ hour waits). The data is publicly
available through the NHS England website under their monthly A&E activity publications.

## Data Scourced from: 
https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/ae-attendances-and-emergency-admissions-2025-26/


##Jupyter notebook

## Key Features

### Data Cleaning & Preprocessing
- Standardised column names  
- Handled missing values  
- Combined related metrics  
- Generated summary statistics  

### Exploratory Data Analysis
- Attendances and admissions trends  
- Wait time distributions  
- Correlation heatmaps  
- Trust-level comparisons  

### Interactive Dashboard (PyQt5 + Plotly)
- Six visualisation buttons  
- “Show All Charts” mode (2×3 grid)  
- Scrollable dashboard layout  
- Animated counters on the Home Page  
- Hospital Finder tool  
- Clean NHS‑themed UI  

---

## Technologies Used

- **Python 3**
- **Pandas** – data cleaning & analysis  
- **Plotly** – interactive visualisations  
- **PyQt5** – GUI dashboard  
- **Jupyter Notebook** – reporting & documentation  
- **GitHub** – version control  

---

## Repository Structure

NHS-AE-Dashboard/
│
├── data/                # Dataset(s)
├── notebooks/           # Jupyter notebook with full report
├── dashboard/           # PyQt5 dashboard application
└── README.md             # Project overview (this file)

---
This project is for educational purposes only and is not affiliated with the NHS.

