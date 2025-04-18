# ⚡ Electric Vehicle Data Analysis Project

## 📌 Overview

This project involves the exploration and analysis of a dataset containing specifications and performance metrics of electric vehicles (EVs). The goal is to extract actionable insights, detect patterns, build a user-friendly EV recommendation system, and perform statistical hypothesis testing.

---

## 📁 Dataset Features

Key columns include:

- **Car full name**: Complete model name
- **Make / Model**
- **Minimal price (gross) [PLN]**
- **Engine power [KM]**
- **Maximum torque [Nm]**
- **Drive type / Type of brakes**
- **Battery capacity [kWh]**
- **Range (WLTP) [km]**
- **Dimensions**: Wheelbase, Length, Width, Height
- **Weight metrics**: Empty weight, Gross weight, Load capacity
- **Tire size [in]**
- **Maximum speed [kph]**
- **Boot capacity (VDA) [l]**
- **Acceleration 0-100 kph [s]**
- **Max DC charging power [kW]**
- **Mean Energy consumption [kWh/100 km]**

---

## ✅ Tasks Completed

### **Task 1: Budget-Based EV Filtering**
- Filter EVs under 350,000 PLN with a range ≥ 400 km
- Grouped filtered EVs by manufacturer
- Calculated average battery capacity per manufacturer

### **Task 2: Energy Consumption Outlier Detection**
- Detected unusually high or low energy consumption EVs
- Used statistical outlier detection methods

### **Task 3: Battery Capacity vs Range**
- Visualized the relationship using a scatter plot
- Derived insights on efficiency and performance

### **Task 4: EV Recommendation Class**
- Created a user-friendly Python class
- Users input budget, range, and battery capacity
- Returns top 3 matching EVs based on dataset

### **Task 5: Hypothesis Testing (Tesla vs Audi)**
- Compared average engine power of Tesla and Audi EVs
- Conducted a **two-sample t-test**
- Interpreted statistical significance of the results

---

## 📊 Libraries Used

- `pandas` – Data wrangling
- `numpy` – Numerical operations
- `matplotlib` / `seaborn` – Visualization
- `scipy.stats` – Hypothesis testing
- `sklearn` (optional) – Advanced stats or modeling

---

## 🔍 Insights & Recommendations

- Price-to-range ratios vary significantly across brands
- Certain brands (e.g. Tesla) consistently outperform in range vs battery capacity
- Some models exhibit inefficient energy consumption – needs optimization
- Engine power differences between Tesla and Audi are statistically significant
