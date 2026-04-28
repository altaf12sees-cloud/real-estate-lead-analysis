# Data-Driven Analysis of Customer Leads and Conversion Patterns in the Real Estate Sector

## 📌 Project Overview

This project presents a data-driven analysis of customer leads in the real estate sector, with the goal of understanding conversion behavior, customer preferences, and business performance.

Using real-world lead data, the analysis focuses on identifying patterns that influence conversion rates and generating actionable insights to support strategic decision-making and improve return on investment (ROI).

---

## 🎯 Objectives

* Analyze customer lead data to identify conversion patterns
* Evaluate the performance of different lead sources
* Understand the impact of property types on customer interest
* Identify key factors contributing to lead drop
* Build a predictive model for lead conversion

---

## 🗂️ Dataset Description

The dataset contains **10,000+ customer lead records** from a real estate company.

### Key Features:

* **Lead Source** (e.g., Property portals, Ads, Referrals, Walk-ins)
* **Property Type** (Residential, Commercial, Apartment, Villa, etc.)
* **Lead Status** (Converted, Dropped, Not Interested, etc.)
* **Assigned Agent**
* **Time-related variables** (lead creation and follow-up timing)

> ⚠️ Note: The dataset used in this repository is anonymized to ensure data privacy and confidentiality.

---

## ⚙️ Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* Power BI
* Microsoft Excel
* Google Colab

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handled missing values
* Removed duplicates
* Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)

* Analyzed distributions and trends
* Identified relationships between features

### 3. Statistical & Predictive Analysis

* Applied **Logistic Regression** for conversion prediction
* Addressed class imbalance using weighted classes

### 4. Data Visualization

* Developed interactive dashboards using Power BI

---

## 📊 Key Insights

* Lead source significantly impacts conversion rates
* Certain property types attract more customer engagement
* High lead drop is associated with delayed follow-up and low engagement
* Marketing channels generate varying quality vs quantity trade-offs

---

## 🤖 Model Performance

* Model Used: Logistic Regression
* Accuracy: **72.6%**
* Challenge: Imbalanced dataset (low proportion of converted leads)

The model shows moderate performance and highlights the difficulty of predicting minority class outcomes in real-world business data.

---

## 📈 Power BI Dashboard

The interactive dashboard includes:

* Lead conversion rate by source
* Property type distribution
* ROI analysis
* Lead drop reasons

📷 Screenshots are available in the `/dashboard` folder.

---

## 📁 Project Structure

```
real-estate-lead-analysis/
│
├── README.md
├── report/
│   └── project_report.pdf
├── data/
│   └── sample_dataset.csv
├── notebooks/
│   └── analysis.ipynb
├── scripts/
│   └── preprocessing.py
└── dashboard/
    └── screenshots/
```

---

## ⚠️ Limitations

* Imbalanced dataset affects prediction accuracy
* Limited behavioral and time-series features
* Analysis based primarily on structured data

---

## 🚀 Future Improvements

* Use advanced models (e.g., Gradient Boosting, XGBoost)
* Incorporate time-series and behavioral features
* Improve dataset balance
* Develop a real-time lead scoring system

---

## 📜 Declaration

This project is based on independent work. All analysis, modeling, and interpretations have been conducted by the author.

---

## 👤 Author

**Altaf Husain**

---

## ⭐ Acknowledgment

This project was developed as part of a Master's program application in Data Science.
