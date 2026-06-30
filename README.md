# SMART-Rain: iTransformer for Climate-Aware Multivariate Rainfall Forecasting

SMART-Rain is a deep learning framework for multivariate rainfall forecasting using long-term climate data and Transformer-based architectures. The project focuses on improving rainfall prediction accuracy through spatio-temporal feature engineering and advanced sequence learning models.

##  Overview

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

##  Key Features

* Long-term multivariate rainfall forecasting
* Climate-aware deep learning framework
* Bayesian hyperparameter optimization using Optuna
* Comparative evaluation of sequence models
* Spatial and temporal feature engineering
* Attention-based forecasting using iTransformer

##  Results

Results
Model	RMSE	MAE	R²
LSTM	0.0976	0.0692	0.7262
Transformer Encoder	0.0897	0.0657	0.7409
iTransformer	0.0885	0.0629	0.7703
Best Model

The iTransformer achieved the best performance, demonstrating strong capability in modeling long-range temporal dependencies and multivariate rainfall interactions.
![Alt text](https://github.com/Solitaryseeker/SMART-Rain-iTransformer-for-Climate-Aware-Multivariate-Rainfall-Forecasting/blob/main/pictures/Actual_vs_Predicted.png)


Results demonstrate that Transformer-based architectures outperform traditional recurrent models for long-range rainfall forecasting tasks.


## 📂 Dataset

 [Yemen Rainfall Dataset](https://www.kaggle.com/datasets/solitaryseeker/yemen-rainnfall)
* CHIRPS rainfall dataset
* Period: 1982–2025
* Subnational rainfall observations (Yemen Level-2 regions)

## 📖 Paper

[SMART-Rain: iTransformer for Climate-Aware Multivariate Rainfall Forecasting](https://github.com/Solitaryseeker/SMART-Rain-iTransformer-for-Climate-Aware-Multivariate-Rainfall-Forecasting/blob/main/Paper/eSmarTA-2026_paper_267.pdf)

This work evaluates the effectiveness of Transformer-based architectures for rainfall prediction and highlights the capability of iTransformer in modeling long-range temporal dependencies and multivariate interactions.

## 🔮 Future Work

* Explainable AI (SHAP/XAI)
* Extreme rainfall prediction
* Weighted loss functions
* Hybrid Transformer architectures
* Multi-horizon forecasting

## 👤 Author

**Rohit Sahu**  
Machine Learning & NLP Enthusiast  

📧 Email: quantumsolitaryseeker@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/rohit-sahu-7142742a7/

🐙 GitHub: https://github.com/Solitaryseeker

---


## 📜 License

This project is intended for research and academic purposes.

⭐ If you found this project helpful, consider giving it a star!
