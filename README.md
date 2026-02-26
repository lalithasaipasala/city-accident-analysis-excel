# Data Analytics Portfolio

> A collection of interactive dashboards and machine learning projects built with Excel, Power BI, and Python.

---

## Table of Contents

- [City-Wise Accident Analysis](#-city-wise-accident-analysis)
- [Ecommerce Sales Dashboard](#-ecommerce-sales-dashboard)
- [Chicago Crime Analysis](#-chicago-crime-analysis)
- [Electric Vehicle Dashboard](#-electric-vehicle-dashboard)
- [Customer Churn Prediction](#-customer-churn-prediction)

---

## 🚨 City-Wise Accident Analysis

**Tool:** Microsoft Excel &nbsp;|&nbsp; **Period:** 1948–2022 &nbsp;|&nbsp; **Records:** 88,000+

An Excel dashboard exploring accident data across multiple cities over 74 years, built with pivot tables and charts.

**Features**
- Filter by city, year, and incident type
- Analyze accident frequency and severity
- Visualize trends and high-risk zones

**Files**
- `accidents_by_city.csv` — Source dataset
- `accident_dashboard.png` — Dashboard preview

---

## 📊 Ecommerce Sales Dashboard

**Tool:** Microsoft Excel &nbsp;|&nbsp; **Focus:** Revenue, Orders, Profit KPIs

An interactive Excel dashboard visualizing ecommerce sales performance across regions, categories, and time periods.

**Features**
- Total Revenue, Orders, and Profit KPIs
- Product category performance breakdown
- Region-wise sales distribution
- Monthly sales trend with line chart
- Dynamic slicers for Month and Product Type

**Files**
- `Ecommerce Dashboard.xlsx` — Excel dashboard
- `Ecommerce Dashboard.jpg` — Dashboard screenshot

![Ecommerce Dashboard](https://raw.githubusercontent.com/lalithasaipasala/city-accident-analysis-excel/main/Ecommerce%20Dashboard.jpg)

---

## 🔍 Chicago Crime Analysis

**Tool:** Microsoft Excel / Power BI

An interactive dashboard for exploring Chicago crime data — identifying trends, hotspots, and incident patterns over time.

![Chicago Crime Analysis](https://raw.githubusercontent.com/lalithasaipasala/city-accident-analysis-excel/main/Chicago%20Crime%20%20Analysis.jpg)

---

## ⚡ Electric Vehicle Dashboard

**Tool:** Microsoft Excel &nbsp;|&nbsp; **Records:** 114,595 vehicles

An interactive Excel dashboard analyzing EV registrations and trends across the U.S., covering vehicle types, clean fuel eligibility, and manufacturer breakdowns.

**Key Stats**

| Metric | Value |
|--------|-------|
| Total Vehicles | 114,595 |
| Battery EVs (BEV) | 87,767 (76.59%) |
| Plug-in Hybrids (PHEV) | 26,828 (23.41%) |

**Visuals**
- Map chart: EV distribution by U.S. state
- Line graph: Registration trends by model year (1997–2023)
- Bar charts: Top manufacturers and electric range leaders
- Pie chart: CAFV eligibility breakdown
- Slicers: Filter by fuel type, EV type, and model

**Key Insights**
- Tesla leads with 52,672 registered vehicles
- EV adoption grew exponentially from 2017, peaking in 2021
- Tesla, Jaguar, and Chevrolet offer the highest electric range

**Files**
- `Electric Vehicle Dashboard.xlsx` — Excel dashboard
- `Electric Vehicle Dashboard.jpg` — Dashboard screenshot

![Electric Vehicle Dashboard](https://raw.githubusercontent.com/lalithasaipasala/city-accident-analysis-excel/main/Electric%20Vehicle%20Dashboard.jpg)

---

## 🤖 Customer Churn Prediction

**Tool:** Python (Scikit-learn, PySpark) &nbsp;|&nbsp; **Records:** 100,000

A binary classification project predicting customer churn in telecom using Random Forest, comparing traditional and distributed ML approaches.

**Dataset**
- 100,000 synthetic telecom customer records
- 100 features: demographics, usage, billing, contract details

**Preprocessing**
- Median/mode imputation for missing values
- One-Hot Encoding (Scikit-learn) / StringIndexer & OneHotEncoder (PySpark)

**Models**

| Model | Accuracy |
|-------|----------|
| Scikit-learn Random Forest | 58.81% |
| PySpark MLlib Random Forest | Scalable (distributed) |

```python
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = RandomForestClassifier(n_estimators=100)
model.fit(X_train, y_train)
print("Accuracy:", accuracy_score(y_test, model.predict(X_test)))
```

**Files**
- [`Customer Churn Prediction (1) (1).ipynb`](./Customer%20Churn%20Prediction%20(1)%20(1).ipynb) — Jupyter notebook
- [`Customer Churn Prediction in Telecom.pdf`](./Customer%20Churn%20Prediction%20in%20Telecom.pdf) — Project report

---

## 🛠 Tools & Skills

| Category | Tools |
|----------|-------|
| Spreadsheets | Microsoft Excel, Pivot Tables, Charts, Slicers |
| Business Intelligence | Power BI |
| Programming | Python, PySpark |
| ML Libraries | Scikit-learn, MLlib |
| Techniques | Dashboard Design, KPI Reporting, Classification, Data Cleaning |
