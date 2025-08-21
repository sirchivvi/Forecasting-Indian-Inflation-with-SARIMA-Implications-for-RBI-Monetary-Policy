# Forecasting Indian Inflation with SARIMA: Implications for RBI Monetary Policy

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/github/your-username/indian-inflation-forecast/blob/main/notebook.ipynb)

A comprehensive time series analysis project that forecasts India's Consumer Price Index (CPI) inflation using Seasonal ARIMA (SARIMA) modeling and provides policy implications for the Reserve Bank of India's monetary policy decisions.

## 📊 Project Overview

This project analyzes historical Indian inflation data (1960-2024) to build a robust forecasting model that can:
- Predict future inflation trends using SARIMA methodology
- Provide data-driven insights for RBI monetary policy
- Evaluate forecast accuracy against RBI's inflation targeting framework (4% ± 2%)
- Generate actionable policy recommendations

- Dataset Link: https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=IN

## 🏗️ Project Structure
indian-inflation-forecast/
├── data/
│ └── API_FP.CPI.TOTL.ZG_DS2_en_csv_v2_122376.csv # World Bank inflation data
├── notebooks/
│ └── indian_inflation_forecast.ipynb # Main analysis notebook
├── results/
│ ├── india_inflation_forecast_results.csv # Forecast results
│ └── model_summary.txt # Model performance summary
├── src/
│ ├── data_loader.py # Data preprocessing utilities
│ ├── model_trainer.py # Model training functions
│ └── visualization.py # Plotting utilities
├── requirements.txt # Python dependencies
└── README.md



## 🚀 Key Features

- **Data Analysis**: Comprehensive EDA of Indian inflation trends since 1960
- **Model Selection**: Automated ARIMA parameter optimization using grid search
- **Forecasting**: 5-year inflation forecasts with confidence intervals
- **Policy Analysis**: RBI target-based policy recommendations
- **Visualization**: Professional-grade plots and diagnostics
- **Validation**: Robust model evaluation metrics (MAE, MAPE, RMSE)

## 📈 Results

### Model Performance
- **MAE**: [Your MAE value]
- **MAPE**: [Your MAPE value] 
- **RMSE**: [Your RMSE value]
- **Best Model**: ARIMA([p,d,q])

### Key Findings
- Average forecasted inflation (2025-2029): [X]%
- [Y]% of forecasted years within RBI's target band (2-6%)
- Recommended policy stance: [Hawkish/Dovish/Neutral]


numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.5.0
seaborn>=0.11.0
statsmodels>=0.13.0
scikit-learn>=1.0.0

🎯 Methodology

    Data Preparation: World Bank inflation data processing and cleaning

    Exploratory Analysis: Trend analysis, stationarity testing, decomposition

    Model Building: ARIMA parameter selection via grid search

    Validation: Time-series cross-validation and performance metrics

    Forecasting: 5-year ahead predictions with confidence intervals

    Policy Analysis: RBI target framework evaluation

📊 Sample Visualizations

The project generates several key visualizations:

    Historical inflation trends with RBI target bands

    Model diagnostics and residual analysis

    Forecast vs actual comparisons

    5-year forecast trajectories with confidence intervals

    Policy implication summaries

🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

    Fork the project

    Create your feature branch (git checkout -b feature/AmazingFeature)

    Commit your changes (git commit -m 'Add some AmazingFeature')

    Push to the branch (git push origin feature/AmazingFeature)

    Open a Pull Request

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgments

    Data Source: World Bank World Development Indicators

    Methodology: Box-Jenkins ARIMA modeling framework

    Policy Framework: Reserve Bank of India inflation targeting

    Inspiration: Economic forecasting for policy decision-making
