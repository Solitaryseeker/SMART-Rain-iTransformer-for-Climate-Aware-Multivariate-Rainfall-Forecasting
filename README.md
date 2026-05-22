# SMART-Rain: iTransformer for Climate-Aware Multivariate Rainfall Forecasting

SMART-Rain is a deep learning framework for multivariate rainfall forecasting using long-term climate data and Transformer-based architectures. The project focuses on improving rainfall prediction accuracy through spatio-temporal feature engineering and advanced sequence learning models.

## 📌 Overview

Rainfall forecasting is essential for climate monitoring, agriculture, water resource management, and disaster mitigation. This project uses CHIRPS rainfall data (1982–2025) and compares multiple deep learning architectures including:

* LSTM
* Transformer Encoder
* iTransformer

The framework integrates:

* Lag-based temporal features
* Rolling rainfall aggregations
* Seasonal cyclical encoding
* Spatial embeddings (PCODE)
* Log transformation for skewed rainfall distributions

## 🚀 Key Features

* Long-term multivariate rainfall forecasting
* Climate-aware deep learning framework
* Bayesian hyperparameter optimization using Optuna
* Comparative evaluation of sequence models
* Spatial and temporal feature engineering
* Attention-based forecasting using iTransformer

## 📊 Results

The iTransformer achieved the best forecasting performance:

* R² Score: 0.7619
* RMSE: 0.0901
* MAE: 0.0635

Results demonstrate that Transformer-based architectures outperform traditional recurrent models for long-range rainfall forecasting tasks.

## 🛠️ Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Scikit-learn
* Optuna
* Matplotlib

## 📂 Dataset

* CHIRPS rainfall dataset
* Period: 1982–2025
* Subnational rainfall observations (Yemen Level-2 regions)

## 📖 Paper

**SMART-Rain: iTransformer for Climate-Aware Multivariate Rainfall Forecasting**

This work evaluates the effectiveness of Transformer-based architectures for rainfall prediction and highlights the capability of iTransformer in modeling long-range temporal dependencies and multivariate interactions.

## 🔮 Future Work

* Explainable AI (SHAP/XAI)
* Extreme rainfall prediction
* Weighted loss functions
* Hybrid Transformer architectures
* Multi-horizon forecasting

## 👨‍💻 Author

Your Name

## 📜 License

This project is intended for research and academic purposes.
