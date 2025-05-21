# Proyecto-Machine-Learning
HICP Forecasting in the European Union (2018–2025)
This project focuses on forecasting the Harmonised Index of Consumer Prices (HICP) for seven EU countries using time series models and machine learning techniques. HICP is a key metric used by the European Central Bank and policymakers to track inflation trends across the EU. Accurate forecasting of this index is essential for decision-making in finance, supply chain planning, and macroeconomic strategy.

Project Goals
Build and compare predictive models (ARIMA, SARIMAX, XGBoost) for monthly HICP data

Analyze inflation trends in Belgium, Germany, Spain, France, Italy, Netherlands, and Poland

Validate the performance of models using both internal and external test data (2025)

Data
Source: Eurostat API

Category: CP00 (Total Consumption)

Period: Jan 2018 – Dec 2025

Data includes variables such as country, time, index value, and COICOP categories

Tech Stack
Python: Pandas, NumPy, Scikit-learn, Statsmodels, XGBoost

Visualization: Matplotlib, Seaborn

Notebooks: Jupyter

Modeling: ARIMA, SARIMAX (AutoARIMA), XGBoost with calendar and lag features

Modeling Approach
Time Series Decomposition: Additive and multiplicative seasonal decomposition

Data Transformations: Log transform, trend extraction, lag features

Validation Metrics: RMSE and MAE on both 2024 test data and 2025 real data

Key Findings
SARIMAX models performed best overall, especially in countries with seasonal patterns

XGBoost showed strong performance in non-linear scenarios, particularly in France

ARIMA remained effective for countries with more regular inflation trends

Country-specific models proved more accurate than general/global approaches

Future Work
Integrate macroeconomic indicators as exogenous variables

Extend predictions to more EU countries and COICOP categories

Deploy interactive dashboards using Streamlit for real-time inflation monitoring



