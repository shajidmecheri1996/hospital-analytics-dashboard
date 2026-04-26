# hospital-analytics-dashboard
End-to-end hospital analytics project using Python and Power BI
# 🏥 Hospital Analytics Dashboard

## 📌 Project Overview

This project presents an end-to-end data analytics solution for hospital operations using Python and Power BI. The objective is to analyze patient flow, revenue generation, doctor performance, and treatment patterns to support better decision-making.

---

## 🎯 Business Objectives

* Analyze patient inflow across time (hourly & daily)
* Identify high-performing doctors and departments
* Understand revenue distribution across treatments
* Detect operational patterns for improved hospital efficiency

---

## 📂 Dataset Description

The dataset is composed of multiple tables:

* **Patients** – demographic and registration details
* **Doctors** – specialization and experience
* **Appointments** – visit details and timings
* **Billing** – revenue and payment information
* **Treatments** – treatment type and cost

These datasets were cleaned, transformed, and merged into a final analytical dataset.

---

## ⚙️ Tools & Technologies

* Python (Pandas, NumPy)
* Power BI
* Data Cleaning & Transformation
* Data Visualization

---

## 🔄 Project Workflow

### 1. Data Processing (Python)

* Data cleaning and handling missing values
* Data type conversions (dates, numeric fields)
* Merging multiple datasets
* Feature engineering (hour, day, revenue metrics)

### 2. Data Aggregation

Generated summary datasets for efficient analysis:

* Doctor-wise performance
* Department-wise revenue
* Time-based patient trends
* Treatment distribution

### 3. Dashboard Development

Built an interactive dashboard in Power BI to visualize key insights.

---

## 📊 Dashboard Features

* **Patient Flow Analysis** – Peak hours and busiest days
* **Department Analysis** – Revenue by specialization
* **Doctor Performance** – Top 5 doctors by revenue
* **Treatment Analysis** – Volume vs revenue comparison
* **Interactive Filters** – Date, department, doctor

---

## 📸 Dashboard Preview

![Dashboard](outputs/screenshots/dashboard.png)

---

## 🧠 Key Insights

* Peak patient visits occur during afternoon hours
* Cardiology and specialized departments generate the highest revenue
* Revenue is concentrated among top-performing doctors
* High-frequency treatments differ from high-revenue treatments

---

## 📁 Project Structure

```
Hospital-Analytics-Project/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── powerbi/
│   └── hospital_dashboard.pbix
│
├── outputs/
│   └── screenshots/
│       └── dashboard.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 🔹 Python

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the notebook:

```bash
jupyter notebook notebooks/data_cleaning.ipynb
```

---

### 🔹 Power BI

* Open the dashboard file:

```
powerbi/hospital_dashboard.pbix
```

---

## 📌 Future Improvements

* Add predictive analytics (patient forecasting)
* Integrate real-time data updates
* Deploy dashboard to cloud platform

---

## 👤 Author

**Shajid**
Aspiring Data Analyst

---

## ⭐ If you found this project useful

Give it a star on GitHub!

