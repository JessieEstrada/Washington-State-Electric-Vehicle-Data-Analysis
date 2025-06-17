# Washington State Electric Vehicle Data Analysis 📊⚡

## Overview
This project analyzes electric vehicle (EV) population data in Washington State to understand EV adoption trends, model popularity, range efficiency, and environmental impact. Using a dataset from [Data.gov](https://data.gov), we explore which EV models dominate the market, their performance characteristics, and how geographic and manufacturer factors play a role in EV adoption.

📄 **[View Full Project Report (PDF)](./Washington-State-Electric-Vehicle-Data-Analysis.pdf)**

---

## 📁 Dataset Information

- **Source:** [Data.gov](https://data.gov)
- **Scope:** All BEVs (Battery Electric Vehicles) and PHEVs (Plug-in Hybrid Electric Vehicles) registered through the Washington State Department of Licensing
- **Fields Included:**  
  VIN, Make, Model, Model Year, Electric Range, MSRP, Electric Utility, Vehicle Location, CAFV Eligibility, etc.

---

## 🔍 Key Insights

### 1. **Most Popular EV Makes and Models**
- **Tesla** dominates the dataset with 56,116 vehicles, followed by **Nissan (12,938)** and **Chevrolet (10,775)**.
- **Model 3** is the most common EV in Washington (24,117 vehicles).
- Tesla’s **Model Y** has the **highest average electric range** at **291 miles**.

### 2. **EV Growth by County**
- **King County** has the highest number of Teslas (83 recorded), aligning with its population density and likely availability of EV charging infrastructure.

### 3. **CAFV Eligibility**
- Most top EV models qualify for CAFV (Clean Alternative Fuel Vehicle) programs.
- Not all **Model 3s** are CAFV-eligible, mostly due to missing battery range data.

### 4. **Range Statistics**
- **Max Electric Range:** Tesla Model S (337 miles)
- **Top 3 by Average Range:**
  - Tesla Model Y: 291 miles  
  - Hyundai Kona: 258 miles  
  - Chevrolet Bolt EV: 243.7 miles

### 5. **BEV vs PHEV Comparison**
- BEVs are significantly more popular than PHEVs:
  - **BEVs:** 94,117 vehicles
  - **PHEVs:** 27,860 vehicles
- Tesla and Nissan manufacture only BEVs, while Chevrolet leads in PHEV production.

---

## 📊 Statistical Summary

| Metric                 | Value     |
|------------------------|-----------|
| Mean Range             | 241.58 mi |
| Median Range           | 236.22 mi |
| Standard Deviation     | 20.29     |
| Range (Max - Min)      | 73 mi     |
| Skewness               | 1.78 (Right-skewed) |
| Max Range (Top Models) | 291 mi    |
| Min Range (Top Models) | 218 mi    |

---

## 🧠 Interpretation & Takeaways

- **EV Popularity is Growing:** 2022 saw the highest EV adoption in WA with 27,742 registrations, up from 18,494 in 2021.
- **Tesla is Leading:** Tesla tops every metric — sales, range, CAFV eligibility, and BEV dominance.
- **Range = Practicality:** Models with higher average electric range (like Tesla Y and Hyundai Kona) are more viable for long-distance travel and better align with consumer needs.
- **Environment & Cost Impact:** Transitioning to EVs benefits sustainability efforts and reduces long-term ownership costs.

---

## ⚠️ Limitations

- **Missing Data:** Some vehicles had missing battery range values, limiting full analysis. These were imputed or filtered where necessary.

---

## ✅ Conclusion

Electric vehicles are not only increasing in popularity across Washington State, but Tesla is setting the standard with unmatched range, production volume, and CAFV compliance. As EV infrastructure grows and battery tech advances, the shift toward zero-emission vehicles is accelerating — backed by data.

---

## 🛠️ Tools Used

- **Data Source:** [Data.gov EV Dataset](https://data.gov)
- **Visualization:** Tableau  
- **Data Cleaning & Analysis:** Excel, Pivot Tables, Summary Stats  
- **Languages/Technologies:** None (no coding required in this phase)
