Energy Demand Forecasting using ARIMA, SARIMA, Prophet & DeepAR

This project builds a comprehensive energy demand forecasting system using multiple time-series models. The goal is to predict electricity load accurately using historical consumption data, weather patterns, and seasonal trends. By comparing classical statistical models with advanced deep learning approaches, this project demonstrates how forecasting accuracy can improve significantly in real-world utility applications.

🚀 Project Objectives

Predict hourly electricity demand using historical data

Compare classical time-series models with deep learning approaches

Analyze seasonality, trends, and probabilistic forecasts

Support decision-making for load planning and energy distribution

📊 Models Used

ARIMA – Baseline model for trend forecasting

SARIMA – Captures strong daily/weekly seasonality

Prophet – Automatically models seasonality + holidays

DeepAR (GluonTS) – Probabilistic forecasting with prediction intervals

🧠 Key Insights

ARIMA captures long-term trends but fails to model daily/weekly seasonal patterns

SARIMA and Prophet produce significantly improved forecasts

DeepAR offers best performance by generating accurate predictions with uncertainty bands

Accurate forecasting helps utility companies optimize energy generation and reduce operational cost

🛠️ Technologies Used

Python, Pandas, NumPy

Statsmodels (ARIMA/SARIMA)

Prophet

GluonTS (DeepAR)

Matplotlib, Seaborn

Jupyter Notebook

📈 Results

Includes visualizations comparing:

Actual vs Predicted load

Trend and seasonal component analysis

Probabilistic forecasts (DeepAR)

Model performance comparison
