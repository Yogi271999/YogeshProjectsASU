# YogeshProjectsASU

# Project - 1 Demand Prediction using Time Series Analysis

## Project Overview
This project focuses on predicting the demand for a manufacturing industry using time series analysis from January 2023 to February 2023. Our team, consisting of three members, employed various machine learning algorithms including ARIMA, SARIMA, LSTM, and FbProphet to develop predictive models.

## Description
The goal of this project was to analyze historical data to predict future demand in the manufacturing industry. We compared several models to identify which algorithm provides the most accurate forecast. The project involved data cleaning, exploratory data analysis, model building, and evaluation.

## Results

The performance of each time series model was evaluated based on the mean absolute error (MAE). Below are the results showing how each model performed in predicting the demand:

- **LSTM (Long Short-Term Memory):**
  - **MAE:** 0.1368
  - **Interpretation:** The LSTM model provided the most accurate predictions with the lowest error rate among the tested models.

- **Fb Prophet:**
  - **MAE:** 0.675
  - **Interpretation:** While more user-friendly and easier to implement, FbProphet showed moderate accuracy in this scenario.

- **ARIMA (AutoRegressive Integrated Moving Average) & SARIMA (Seasonal ARIMA):**
  - **MAE:** 0.793
  - **Interpretation:** ARIMA and SARIMA models, while traditional choices for time series forecasting, resulted in the highest error rates in this study.

Based on the mean absolute errors observed, the LSTM model outperformed the other techniques, making it the most suitable choice for future demand forecasting in this manufacturing industry context.

