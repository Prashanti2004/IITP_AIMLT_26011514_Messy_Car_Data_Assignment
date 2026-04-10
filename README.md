# Used Car Data Cleaning & Baseline MAE

## 📌 Project Summary
Systematically explore a messy used-car dataset, fix data quality issues, and establish a **baseline MAE** before applying any ML model.

---

## 🎯 Objectives
- Explore raw data and identify issues
- Clean and standardize columns
- Handle missing values and duplicates
- Build a mean-based baseline
- Evaluate with MAE

---

## 🗂️ Dataset
`used_cars.csv` — contains car attributes and `selling_price` as target.

---

## 🔍 Data Issues Found
- Nulls in `selling_price`, `mileage`, others
- Wrong dtypes (e.g., `"18.2 kmpl"` as string)
- Inconsistent `brand` values (case/spacing)
- Duplicate rows
- Mixed units / noisy text

---

## 🧹 Cleaning Steps
1. Drop rows with null `selling_price`
2. `brand` → strip + lowercase
3. Extract numeric from `mileage`
4. Impute missing values (median/mode)
5. Remove duplicates

---

## 📉 Baseline Model
- Prediction: mean of `selling_price`
- Metric: Mean Absolute Error (MAE)

---

## 🧪 How to Run
1. Open `used_car_analysis.ipynb`
2. Run all cells in order

---

## 📁 Project Structure
