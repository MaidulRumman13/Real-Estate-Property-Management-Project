# 🏠 Real Estate Property Management Dashboard

[Screenshot](Dashboard 1.png) <!-- Replace with your actual screenshot -->

An interactive Power BI dashboard providing actionable insights for a real estate portfolio and property management, built from a single raw dataset.

---

## 📌 Problem Statement

Real estate firms often operate with fragmented data scattered across multiple spreadsheets and sources. This makes it difficult to assess property performance, condition, and renovation needs effectively.

Without a unified analytical system, decision-making becomes reactive instead of proactive.

**Goal:**  
To create a single, interactive dashboard that consolidates key property metrics and provides strategic insights at a glance.

---

## 🛠️ Solution Overview

The solution is a Power BI dashboard structured using a **Star Schema Model**, built from one dataset (sourced from Kaggle).

### 1️⃣ Data Model
- **Fact Table (`Fact_Table`)**: Contains core metrics (price, sqft_living, etc.) and foreign keys.  
- **Dimension Tables**:
  - `Dim_Location`: Property location (California, Florida, etc.)  
  - `Dim_Condition`: Property condition ratings (Very Good, Bad, etc.)  
  - `Dim_Renovation`: Renovation status (Yes/No)  
  - `Dim_Bedrooms`: Number of bedrooms  
  - `Dim_Floors`: Number of floors  
  - `Dim_Waterfront`: Waterfront availability  

### 2️⃣ Key DAX Measures
- `Total Properties`  
- `Renovated %` / `Not Renovated %`  
- `Condition %` (Good, Bad, Very Good)  
- `Property Age`  

### 3️⃣ Interactive Dashboard Pages
- **Overview:** Summary of KPIs, condition breakdown, bedroom/floor distributions  
- **Locations:** Map of property concentration by state, with condition and floor breakdown tables  

---

## 📊 Key Insights

- The majority of properties are located in **California and Connecticut**  
- Over **85%** are in *Good or Very Good* condition  
- Around **50%** have been renovated  
- Regions with high concentrations of poor-condition properties can be prioritized for maintenance  

---

## 📈 Live Dashboard

👉 [**View Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiYTI2YzZkNWEtMTYxNC00M2RmLThmOWItMDg0YTdlNzY5YTY0IiwidCI6IjIwYjliYTY2LWExMWQtNDkzOC1iNzk0LWYyZTg1YjEzODgxOCIsImMiOjEwfQ%3D%3D)

---

## 💡 Technologies Used
- Microsoft Power BI  
- DAX (Data Analysis Expressions)  
- Star Schema Data Modeling  
- Excel / Kaggle Dataset  

---

## 🔗 Source Data
[Kaggle - King County House Sales Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

---

## ✍️ Author
**Md. Maidul Islam**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/md-maidul-islam-6a92391b9/)  
📊 [View Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTI2YzZkNWEtMTYxNC00M2RmLThmOWItMDg0YTdlNzY5YTY0IiwidCI6IjIwYjliYTY2LWExMWQtNDkzOC1iNzk0LWYyZTg1YjEzODgxOCIsImMiOjEwfQ%3D%3D)

---

## 🏷️ Tags
`Power BI` `Data Analytics` `Real Estate` `Property Management` `Business Intelligence` `Data Visualization` `Star Schema` `Data Modeling`
