# Air Temperature Forecasting

## Project Overview
This project focuses on forecasting monthly mean air temperature using time-series analysis and machine learning techniques. It explores historical temperature patterns, identifies trends and seasonality, and compares different forecasting models.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- ARIMA
- SARIMA
- LSTM
- Scikit-learn

## Project Workflow
1. Data collection and loading
2. Data preprocessing
3. Exploratory Data Analysis (EDA)
4. Trend and seasonality analysis
5. Train-test splitting
6. Model development using ARIMA, SARIMA, and LSTM
7. Model evaluation using MAE and RMSE
8. Future temperature forecasting for 12 months

## Model Performance

| Model | MAE | RMSE |
|---|---:|---:|
| ARIMA | 0.6271 | 0.7571 |
| SARIMA | **0.5076** | **0.6372** |
| LSTM | 0.6020 | 0.7330 |

SARIMA achieved the lowest MAE and RMSE among the evaluated models.

## Forecast Details
- Historical data period: 1982–2020
- Forecast period: July 2020–June 2021
- Forecast horizon: 12 months

## Project File
- `Air_TempTS.ipynb` – Complete project implementation, analysis, model comparison, and forecasting.

## How to Use
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required Python libraries.
3. Run the notebook cells in sequence.
4. Review the model evaluation results and forecast visualizations.
