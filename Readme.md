# 📊 Time Series Analysis - Undergraduate Project (UGP) - Railway Load Forecasting Project

Railway load and power consumption forecasting using statistical and deep learning models.


## Overview

Railway load and power consumption forecasting using statistical, ML, and deep learning models.A comprehensive time series forecasting project exploring multiple methodologies including classical statistical models, machine learning, and deep learning approaches for power consumption and demand forecasting.



This project implements and compares multiple time series forecasting approaches including ARIMA, XGBoost, LSTM, and Temporal Fusion Transformer (TFT). The dataset combines historical load data from Delhi with weather and holiday information.



## Project Structure

## Models
| Model | Type | Location |
|-------|------|----------|
| ARIMA | Statistical | `ARIMA/` |
| XGBoost | ML | `Time-Series-ARIMA-XGBOOST-RNN/` |
| LSTM | Deep Learning | `Nixtla/`, `Time-Series-ARIMA-XGBOOST-RNN/` |
| TFT | Deep Learning | `Temporal-fusion-transformer_Pytorch-Forecasting/` |


---

## 📊 Data Sources

| Dataset | Description |
|---------|-------------|
| `Delhi (NR) 2022-23.xlsx` | Delhi Northern Region power data (2022-23) |
| `Delhi (NR) 2023-24.xlsx` | Delhi Northern Region power data (2023-24) |
| `DL (NR).xlsx` | Combined Delhi load data |
| `final_data.csv` | Main Load dataset combined with weather and holiday data |
| `Holidays_Data/` | Indian holiday calendar for feature engineering |

---

## 📈 Results & Outputs

All model outputs are saved in respective folders as:
- `output.csv` / `output.xlsx` - Intermediate results
- `final_output.csv` / `final_output.xlsx` - Final predictions

Visualization plots are available in:
- Root directory: `day.png`, `week.png`, `month.png`
- `Time-Series-ARIMA-XGBOOST-RNN/`: Model-specific plots

---

## 🔮 Future Work

1. **Dynamic Regression Models:** Include correlated variables in forecasting
2. **Multivariate LSTM:** Incorporate multiple features in RNN models
3. **Ensemble Methods:** Combine multiple models for improved accuracy
4. **Real-time Forecasting:** Deploy models for live predictions
5. **Hyperparameter Optimization:** Automated tuning with Optuna

