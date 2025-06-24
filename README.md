# India GDP and Macroeconomic Indicators: Exploratory Modeling and Scenario Analysis (2004–2024)

## 📌 Project Overview

This project explores the relationship between India's quarterly GDP growth and 17 macroeconomic indicators such as CPI (Inflation), M3 (Money Supply), Exchange Rate, Repo Rate, GFCF (Investment), and others over the period 2004 Q2 to 2024 Q4. The aim was not only to model GDP but also to understand the impact and contribution of various economic factors.

## ⚙️ Key Steps

- Exploratory Data Analysis (EDA)
- Feature Engineering: Lags, Rolling Means, Percentage Changes, Interaction Terms
- Modeling with Linear Regression
- Scenario Simulation: +10% CPI Shock Impact
- Model Evaluation (R² = 0.774, RMSE = 1.78M, MAE = 1.23M)

## 📊 Results Summary

- **Best Model:** Linear Regression
- **R² Score:** 0.774
- **RMSE:** 1.78 million (6.5% of mean GDP)
- **MAE:** 1.23 million
- **Shock Simulation:** +10% CPI increase led to GDP rise of ~249,484 units

## 🛠️ Tools Used

- Python (Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib)
- Jupyter Notebook

## 🚧 Future Improvements

- Incorporate sectoral GDP data
- Explore Bayesian/VAR models
- Real-time forecast deployment

