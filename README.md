## 🚲 Bike Rental Demand Prediction – Regression Project (Seoul Dataset)

### 📌 Objective
This project aims to build a machine learning regression model that accurately predicts the hourly demand for shared rental bikes in Seoul based on environmental and seasonal factors. Accurate predictions can help optimize fleet distribution, reduce operational costs, and improve customer experience for bike-sharing platforms like Yulu.

### 📊 Dataset Overview
- **Source:** UCI Machine Learning Repository – Seoul Bike Sharing Dataset
- **Size:** 8760 rows × 14 columns
- **Target Variable:** Rented Bike Count (hourly)
- **Features include:**
  - Temperature (°C), Humidity (%), Wind speed (m/s)
  - Solar Radiation (MJ/m²), Rainfall (mm), Snowfall (cm)
  - Hour, Season, Holiday, Functioning Day

### 🔍 Key Steps Performed
- Performed Exploratory Data Analysis (EDA) to identify trends and outliers
- Cleaned and preprocessed data: handled missing values, encoded categorical variables
- Built multiple regression models: Linear Regression, Decision Tree, and Random Forest
- Optimized Random Forest using GridSearchCV (5-fold CV)
- Evaluated models using metrics: R² Score, MSE, RMSE, and MAE
- Used model explainability tools (feature importance, SHAP/Permutation importance)
- Saved and loaded the final model using Joblib for deployment readiness

### 🧠 Final Model & Performance
- **Chosen Model:** Random Forest Regressor (after hyperparameter tuning)
- **Best R² Score:** ~0.596
- **RMSE:** ~394
- **MAE:** ~263
- **Key Features:** Temperature, Solar Radiation, Humidity


### 🚀 Business Impact
The project provides operational insight for real-world applications:
- Dynamic bike placement planning during peak vs. off-peak hours
- Weather-aware fleet allocation strategy
- Enhanced user satisfaction through demand responsiveness

---

> 🛠 Built using: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn


