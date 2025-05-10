# AQI Prediction and Trend Analysis Using Machine Learning

## 📘 Overview

This project presents a hybrid machine learning and deep learning model to accurately predict the Air Quality Index (AQI) and analyze long-term pollution trends. Conducted as part of a B.Sc. IT academic submission at Thakur College of Science and Commerce, the study integrates a variety of ML techniques—including Logistic Regression, SVM, CNN, and XGBoost—with Holt’s Linear Exponential Smoothing for enhanced AQI forecasting. It aims to support public health and environmental planning through reliable real-time air quality predictions.

## 🧠 Key Objectives

- Predict concentrations of major pollutants: PM2.5, PM10, NO₂, SO₂, CO, and O₃.
- Classify AQI into standard categories (Good to Severe) using ML classifiers.
- Forecast future AQI values using time-series models for proactive health alerts.
- Compare performance between traditional ML models and hybrid deep learning systems.

## 🧪 Techniques and Methodologies

- **Machine Learning Models**: Logistic Regression, SVM, XGBoost
- **Deep Learning**: Convolutional Neural Networks (CNNs)
- **Hybrid Modeling**: Stacked ensemble integrating CNN, XGBoost, and Linear Regression
- **Forecasting**: Holt’s Linear Exponential Smoothing
- **Validation**: Train-test split, cross-validation, rolling window approach
- **Metrics**: Accuracy, MSE, RMSE, MAE, MAPE

## 📊 Performance

| Model              | Accuracy (%) | MAE  | RMSE |
|-------------------|--------------|------|------|
| Logistic Regression | 97.00        | -    | -    |
| SVM                | 96.00        | -    | -    |
| Hybrid Model       | 97.07        | 5.2  | 7.1  |
| Holt’s Smoothing   | -            | 5.6  | 7.4  |

## 📈 Key Features

- Comprehensive data preprocessing and normalization
- Feature correlation analysis (heatmaps)
- Real-time adaptability using ensemble learning
- AQI classification aligned with Indian National AQI standards
- Visualizations of pollutant trends and prediction convergence

## 🔬 Research Impact

This study demonstrates how ML and DL models can significantly improve air quality forecasting. The findings help develop early warning systems, support environmental policymaking, and promote public awareness of pollution levels.

## 📁 Project Structure

```
/data             # Cleaned and processed datasets
/models           # Trained ML and DL models
/notebooks        # Jupyter notebooks for EDA, training, and evaluation
/scripts          # Core implementation scripts
/reports          # Documentation and visualizations
README.md         # Project summary and usage guide
```
