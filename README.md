# Women Safety Risk Analysis (2018–2022)

## Project Overview

This project analyzes women safety trends across Indian states using publicly available National Crime Records Bureau (NCRB) datasets from **2018–2022**. The objective is to prepare a reliable analytical dataset by integrating multiple government data sources, performing extensive data preprocessing, engineering meaningful features, and developing a risk score for state-wise comparison.

The project demonstrates an end-to-end data preparation pipeline, from raw government datasets to an interactive analytical dashboard.

---

## Problem Statement

Crime statistics collected over multiple years often contain inconsistent schemas, varying column names, missing information, and non-uniform state names. These issues make direct comparison difficult.

This project addresses these challenges by creating a standardized analytical dataset and developing population-normalized risk indicators for meaningful comparisons across states.

---

## Objectives

* Analyze women safety trends across Indian states (2018–2022)
* Standardize and clean multi-year government datasets
* Integrate crime and population datasets
* Calculate population-adjusted crime rates
* Develop a normalized women safety risk score
* Visualize regional trends using Power BI

---

## Data Sources

* National Crime Records Bureau (NCRB) Crime in India Reports (2018–2022)
* State-wise Population Dataset

Crime categories included:

* Rape Cases
* Kidnapping Cases

---

## Tech Stack

* Python
* Pandas
* NumPy
* Power BI
* DAX

---

# Project Workflow

## 1. Data Collection

Collected yearly NCRB datasets (2018–2022) and state population data from government sources.

---

## 2. Data Inspection

Performed initial analysis to identify:

* Dataset structure
* Column names
* Missing information
* Schema differences across years

---

## 3. Data Cleaning

Performed multiple preprocessing operations, including:

* Column standardization
* Removing unnecessary summary rows
* Removing duplicate records
* Data type corrections
* State name standardization
* Handling missing values
* Dataset validation

---

## 4. Dataset Integration

Combined multiple yearly datasets into a unified analytical dataset using Pandas.

Integrated:

* Crime data
* Population data

---

## 5. Feature Engineering

Created analytical features including:

* Rape Rate (per 100,000 population)
* Kidnapping Rate (per 100,000 population)

Developed a weighted Women Safety Risk Score using normalized crime indicators for fair comparison across states.

---

## 6. Exploratory Data Analysis (EDA)

Performed exploratory analysis to identify trends and regional patterns, including:

* Crime trend across years
* State-wise comparison
* Highest risk states
* Crime distribution
* Correlation analysis

---

## 7. Dashboard Development

Built an interactive Power BI dashboard featuring:

* KPI Cards
* Year Filter
* State Filter
* Trend Analysis
* Risk Score Comparison
* Geographic Visualizations
* Heatmap

---

# Data Challenges Solved

| Challenge                           | Solution                                  |
| ----------------------------------- | ----------------------------------------- |
| Different column names across years | Standardized schema across all datasets   |
| Inconsistent state names            | Applied state name normalization          |
| Missing population records          | Validated and handled unmatched entries   |
| Multi-year datasets                 | Combined into a single analytical dataset |
| Population differences              | Created per-capita crime rates            |
| Different feature scales            | Applied Min-Max normalization             |

---

# Final Dataset

The processed dataset contains:

* State
* Year
* Population
* Rape Cases
* Kidnapping Cases
* Rape Rate
* Kidnapping Rate
* Normalized Risk Indicators
* Women Safety Risk Score

---

# Key Outcomes

* Built a clean and standardized analytical dataset from raw government data.
* Developed population-based crime indicators for meaningful comparisons.
* Created a normalized Women Safety Risk Score to rank states.
* Delivered an interactive dashboard to support data-driven analysis.

---

# Repository Structure

```
Women_Safety_Risk_Analysis/
│
├── README.md          ← (ye document)
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_eda.ipynb
├── dashboard/
│   └── Women_Safety_Dashboard.pbix
└── images/
    ├── dashboard_overview.png
```

---

## Skills Demonstrated

* Data Collection
* Data Cleaning
* Data Validation
* Data Transformation
* Dataset Integration
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Statistical Normalization
* Risk Modeling
* Python (Pandas, NumPy)
* Power BI
* DAX
* Analytical Thinking

---

## Future Improvements

* Include additional crime categories for a more comprehensive safety index.
* Add time-series forecasting for future trend analysis.
* Develop a machine learning model to predict women safety risk using historical crime data.
* Deploy the dashboard as an interactive web application.

---

## Author

**Urvashi Shasne**

AI & ML Graduate | Data Analyst | Python | SQL | Power BI | Machine Learning
