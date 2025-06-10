# 🏡 Predicting House Prices Using the Boston Housing Dataset

## 📌 Description  
This beginner-friendly project demonstrates how to **predict house prices** using the **Boston Housing Dataset**. All models are implemented **from scratch**, with no use of pre-built regressors like `sklearn.linear_model`. The goal was to better understand how regression models work internally.

---

## ✅ Tasks Completed

### 1. Data Preprocessing
- Normalized all numerical features
- Loaded and explored the dataset
- Handled any required preprocessing manually

### 2. Model Implementation
- Implemented **Linear Regression from scratch**
- Implemented a basic **Random Forest from scratch**
- (XGBoost was skipped for simplicity, but can be added later)

### 3. Performance Comparison
- Compared model results using **RMSE** and **R² Score**

| Model              | RMSE  | R²   |
|-------------------|-------|------|
| Linear Regression | 4.68  | 0.74 |
| Random Forest     | 8.08  | 0.23 |

### 4. Feature Importance
- Visualized feature importance for Random Forest using a bar chart

---

## 📁 Files Included

- `boston_housing_prediction.ipynb` — Main Jupyter notebook
- `README.md` — Project overview and documentation

---

## 📊 Libraries Used

- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `sklearn.datasets` *(only for loading the Boston dataset)*

---

## 🔧 How to Run

1. Open the notebook file `boston_housing_prediction.ipynb` using Jupyter Notebook or JupyterLab.
2. Run each cell step by step:
   - Preprocess data
   - Train models
   - Evaluate results
   - Visualize results

---

## 💡 Notes

- No built-in regressors like `sklearn.linear_model` or `RandomForestRegressor` were used.
- The Random Forest implementation is simplified for educational purposes.

---

## 👩‍💻 Author

**Aneesa Alam**  
Beginner in Machine Learning  
Exploring the fundamentals of regression and model building from scratch.

---

