# MSc Data Analysis
## Predictive Analysis in the Coffee Market: Using Deep Learning to predict coffee prices.

This is the final version for my  MSc Capstone Project in Data Analysis - CCT College - Dublin, Ireland
Submitted on 13th Dec 2024


### Introduction
This notebook aims to analyse historical coffee price indices and develop a predictive model for future price trends in the green coffee market. The focus is on using data from the ICO (International Coffee Organization), particularly the composite prices indec (I-CIP), that combines prices of Colombian Milds, Other Milds, Brazilian Naturals, and Robustas.

### Dataset:
The dataset used in this analysis consists of historical coffee price data, with daily observations for business days. Prices are expressed in cents of USD per lb. and stated on a differential basis to the New York and London futures exchanges (https://icocoffee.org/wp-content/uploads/2023/01/icc-105-17-r1e-rules-indicator-prices.pdf)

The data utilized in this project is sourced from the International Coffee Organization's (ICO) Public Market Information (https://ico.org/resources/public-market-information/), which provides the I-CIP values free of charge.

For the early stages of the experimentation, 1 year worth of data was available to collect, from 01Feb23 to 29Feb24, which is present on a separate notebook (2020274_capstone_EDA_Models 2.ipynb). In this notebook, recent data from March to September 2024 were added to expand insights and feed more datapoints to modelling stage.

### Objectives:
- Clean and preprocess the dataset for missing values and inconsistencies.
- Explore the time-series behavior of coffee prices through visualizations.
- Implement various forecasting models to predict future price trends, including traditional statistical models (e.g., ARIMA/Sarima) and deep learning algorithms (e.g., LSTM neural networks).
- Compare model performance using key metrics (e.g., MSE, MAE).


## Forecasting:
Generate forecasts for future I-CIP values using the best-performing model(s) and visualize the results 
- 1 day
- 5 days = 1 week
