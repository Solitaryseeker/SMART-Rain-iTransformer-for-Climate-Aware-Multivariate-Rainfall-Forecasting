# SMART-Rain: iTransformer for Climate-Aware Multivariate Rainfall Forecasting

SMART-Rain is a deep learning framework for multivariate rainfall forecasting using long-term climate data and Transformer-based architectures. The project focuses on improving rainfall prediction accuracy through spatio-temporal feature engineering and advanced sequence learning models.

##  Overview

SMART-Rain is a climate-aware deep learning framework for multivariate rainfall forecasting using long-term historical rainfall data. It integrates spatio-temporal feature engineering, regional embeddings, and advanced sequence learning architectures to improve rainfall prediction in data-scarce and geographically diverse regions.

This framework focuses on Yemen rainfall forecasting using CHIRPS-derived dekadal rainfall indicators from 1982 to 2025.

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
  
## Data Preprocessing
![Alt text](https://github.com/Solitaryseeker/SMART-Rain-iTransformer-for-Climate-Aware-Multivariate-Rainfall-Forecasting/blob/main/pictures/smar_.jpg)

## Results

| Model | RMSE | MAE | R² |
|-------|------|------|------|
| LSTM | 0.0976 | 0.0692 | 0.7262 |
| Transformer Encoder | 0.0897 | 0.0657 | 0.7409 |
| iTransformer | **0.0885** | **0.0629** | **0.7703** |

### Best Model
The **iTransformer** achieved the best performance, demonstrating strong capability in modeling long-range tempora
![Alt text](https://github.com/Solitaryseeker/SMART-Rain-iTransformer-for-Climate-Aware-Multivariate-Rainfall-Forecasting/blob/main/pictures/Actual_vs_Predicted_.jpg)

## 📂 Dataset

 [Yemen Rainfall Dataset](https://www.kaggle.com/datasets/solitaryseeker/yemen-rainnfall)
- **Source:** World Food Programme (WFP) + Climate Hazards Center (CHC)
- **Temporal Coverage:** 1982 – 2025
- **Spatial Coverage:** 318 Level-2 administrative regions in Yemen
- **Total Records:** 503,712
- **Features:** 19
- **Temporal Resolution:** Dekadal (10-day interval)

## Research Paper

[SMART-Rain: A Climate-Aware Deep Learning Framework for Multivariate Rainfall Forecasting in Yemen]()





📧 Email: quantumsolitaryseeker@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/rohit-sahu-7142742a7/

🐙 GitHub: https://github.com/Solitaryseeker

---


## 📜 License

This project is intended for research and academic purposes.

⭐ If you found this project helpful, consider giving it a star!
