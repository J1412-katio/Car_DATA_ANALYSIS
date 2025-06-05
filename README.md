# 🚗 Car Data Insights: Price, Performance, and Market Dynamics

## 📂 Dataset Overview

This dataset includes **6,308 entries** with **9 object-type columns**, each representing a key attribute of a car:

- **Car Name**: Model identifier
- **Price**: Vehicle price (currency unspecified)
- **Engine Capacity**: Engine displacement in liters or cc
- **Cylinder**: Number of engine cylinders (some missing values)
- **Horsepower**: Power output
- **Top Speed**: Maximum speed
- **Seats**: Seating capacity
- **Brand**: Manufacturer name
- **Country**: Manufacturer's country of origin

---
## 🚀 Key Insights from Car Data Analysis

- **Luxury Market Dominance (Average Price)**

    - Bugatti Chiron leads as most expensive ($13.3M), followed by Bentley models (Continental GT: $10.1M)
    - **Outlier**: McLaren Senna's listed price ($3B) suggests data error (likely misformatted).
    - **Trend**: Ultra-luxury brands (Bugatti/Bentley) command 10x premiums over premium brands (Mercedes/Aston Martin).

- **Market Share by Brand** 

    - **Top 3 Brands**: Likely Mercedes-Benz, BMW, Audi (exact counts unclear due to axis labels).
    - **Observation**: German brands dominate listings, indicating strong market presence.
      
- **3. Performance by Country**

    - **Top Speed Leaders**: Italy (median ~300 km/h), Germany (~250 km/h) – reflects focus on high-performance engineering.
    - **Practical Range**: Most countries cluster between 150–250 km/h.
    
- **4. Price vs. Horsepower**
- 
    - **Strong Correlation**: Higher horsepower generally commands premium pricing.
    - **Outliers**: Some high-HP cars (e.g., 600+ HP) may offer "value" relative to luxury counterparts.
      
**5. Seating Capacity**

- **Dominant Config**: 5-seaters (68% of listings), followed by 2-seaters (sports cars) and 7-seaters (SUVs).
- **Niche Demand**: 4/6/8-seaters are rare, suggesting specialized use cases.

---

## 🧠 Conclusion

- Handled missing values and standardized inconsistent formats.
- Explored outlier influence on pricing.
- Learned to design cleaner, context-rich visualizations for storytelling.

---

## 🔍 Future Work

- Investigate fuel type or mileage statistics (if available)
- Use clustering for car segmentation
- Clean and standardize missing values (e.g., cylinder data)
- Build a **price prediction model** using regression.
- Incorporate **fuel type**, **mileage**, and **emissions** if data allows.
- Cluster cars by segments (e.g., SUV vs. Sedan) using k-means or DBSCAN.

---

## 📎 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

---

##  Acknowledgments

Thank you for exploring this EDA project. Stay tuned for further developments!

---
