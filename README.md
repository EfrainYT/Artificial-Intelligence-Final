

# 📈 Ice Cream Shop Sales Forecasting (ARIMA & SARIMA Models)

This repository contains the code, datasets, and statistical analysis for a project focused on forecasting ice cream shop sales using **Time Series Models** such as **ARIMA** and **SARIMA**.  
The goal is to predict future monthly sales and understand seasonal patterns in product demand.

---

## 📌 Project Description

This project analyzes **monthly sales data from an ice cream shop (2022–2024)**.  
Using this dataset, the following tasks were completed:

- Data cleaning and transformation  
- Exploratory Data Analysis (EDA)  
- Visualization of total sales and product-level sales  
- Stationarity testing (ADF Test)  
- Identification of ARIMA/SARIMA parameters using:
  - ACF / PACF plots  
  - AIC/BIC model selection  
- Forecasting sales for the next 6 months  
- Evaluation using RMSE, MAE, and MAPE  

This work is part of a university data science and artificial intelligence project.

---

## 📊 Dataset

The dataset used is:

- **ventas_m.csv**  
- Contains monthly aggregated sales  
- Variables:  
  - `total_sales`  
  - `cone_without_topping`  
  - `simple_freddo`  
  - `simple_tulip`  
- 36 rows (January 2022 – December 2024)

---

## 🧠 Methodology

1. **Load and preprocess dataset**  
2. **Plot monthly total sales**  
3. **Plot each product separately**  
4. **Check stationarity with ADF Test**  
5. **Use ACF & PACF to identify p, d, q and P, D, Q**  
6. **Train ARIMA and SARIMA models**  
7. **Forecast upcoming months**  
8. **Evaluate model accuracy**

---

## 🧪 Models Used

- **ARIMA(p, d, q)**  
- **SARIMA(p, d, q)(P, D, Q)s**

Parameter selection was based on minimum AIC/BIC and visual inspection of ACF/PACF.

---

## 📈 Results

- SARIMA performed better based on RMSE, MAE, and MAPE  
- Sales show strong seasonality patterns  
- Forecasting predicts increasing demand in specific months  

(You can later insert graphs here.)

---

## 📚 Folder Structure

