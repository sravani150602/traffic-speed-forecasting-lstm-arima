# 🚦 Traffic Speed Forecasting using ARIMA & LSTM

## 🧠 Project Summary

This project forecasts traffic speed using advanced time series modeling techniques, including classical statistical models (ARIMA) and deep learning (LSTM). The dataset is preprocessed, analyzed visually, and fed into models that are rigorously evaluated using real-world metrics.

## 🎯 Objectives

- Build a full time series prediction pipeline
- Compare traditional and deep learning forecasting models
- Demonstrate end-to-end workflow from data cleaning to evaluation

## 🧰 Technologies & Tools Used

| Category        | Tools/Libraries                             |
|----------------|---------------------------------------------|
| Language        | Python                                      |
| Environment     | Google Colab                                |
| Data Handling   | pandas, numpy                               |
| Visualization   | matplotlib, seaborn                         |
| Time Series     | statsmodels, pmdarima                       |
| Deep Learning   | TensorFlow (Keras LSTM)                     |
| Evaluation      | sklearn (MAE, RMSE, R²)                     |
| File Handling   | zipfile, os                                 |

## 📊 Exploratory Data Analysis

- Line plots of average traffic speed
- Heatmaps showing time vs speed
- Station-wise breakdown
- Time-of-day pattern analysis

## 📈 Modeling Approaches

### 🔁 ARIMA Model
- Auto ARIMA selection using AIC
- Stationarity check using Augmented Dickey-Fuller test
- Model diagnostics and residual analysis

### 🧠 LSTM Model
- Normalization and reshaping of time series
- Model architecture using Keras (LSTM + Dense)
- Early stopping and training visualization

## 📉 Model Evaluation

| Metric | ARIMA   | LSTM     |
|--------|---------|----------|
| MAE    | X.XX    | Y.YY     |
| RMSE   | X.XX    | Y.YY     |
| R²     | 0.XX    | 0.YY     |

(*Replace `X.XX` and `Y.YY` with your actual model results.*)

## 🖼️ Visual Outputs

Include the following images in your repo:
1. `output/arima_forecast.png` – Forecast plot from ARIMA
2. `output/lstm_forecast.png` – Forecast from LSTM
3. `output/eda_heatmap.png` – Heatmap from EDA
4. `output/loss_curve.png` – LSTM training loss graph

📁 Create a folder in your GitHub repo called `/output/` and upload the above images.

## 🏁 Conclusion

This project showcases the practical differences and effectiveness of ARIMA vs LSTM in a real-world forecasting scenario. It demonstrates full-cycle data science skills, from data wrangling and visualization to modeling and evaluation.

---

### 👨‍🎓 Author

Sravani Elavarthi
