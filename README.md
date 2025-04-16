# 🚕 Uber NYC Trip Analysis 

This project explores data merging, joining, concatenation, advanced indexing, and geo-based filtering using **Uber ride data in NYC** from **April and May 2014**.

---

## 📁 Datasets  
- **April 2014:**  
  [Download CSV](https://raw.githubusercontent.com/fivethirtyeight/uber-tlc-foil-response/master/uber-trip-data/uber-raw-data-apr14.csv)  
- **May 2014:**  
  [Download CSV](https://raw.githubusercontent.com/fivethirtyeight/uber-tlc-foil-response/master/uber-trip-data/uber-raw-data-may14.csv)

### Fields in Both Datasets:
- `Date/Time`: Timestamp of the trip
- `Lat`: Latitude of pickup
- `Lon`: Longitude of pickup
- `Base`: Uber base code

---

##  Dataset Size
- April 2014: ~ 564,000 records  
- May 2014: ~ 652,000 records  
- **Total Combined:** ~ **1.2 million+ trips**  
This large-scale dataset provides rich opportunities for realistic data analysis and performance-aware operations.

---

## 🎯 Skills Practiced
- Concatenating multiple monthly datasets using `pd.concat`
- Merging additional metadata using `pd.merge`
- Time-based feature engineering (hour, weekday, date slicing)
- Geo-spatial filtering (e.g., isolating trips within Manhattan)
- Rolling averages, moving windows, and trend analysis
- Pivot tables and grouped aggregation
- Handling missing data during joins (left, right, outer)

---

## 🧰 Tools Used
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** for visualization
- **Seaborn** for statistical plotting

---


## 💡 Outcome
This project demonstrates the ability to analyze and visualize **large-scale, real-world time series and location data** using professional data science workflows. It highlights core skills in **data merging**, **time-based filtering**, and **performance-aware processing** on large datasets — a crucial ability for roles in **data analysis** and **data science**.
