# LSTM_Power_Demand_Forecasting

This repository contains a machine learning project that uses Long Short-Term Memory (LSTM) networks to predict hourly electrical load. Accurate forecasting is essential for power grid stability and optimizing energy generation.


📊 Dataset Overview

The project utilizes the energy_dataset.csv, which includes:

Time-series data: Hourly electricity consumption and generation across 29 different categories.

Features: Generation types (Biomass, Fossil, Nuclear, Wind, Solar), price data, and day-ahead forecasts.

Target Variable: total load actual.


🛠️ Key Steps

Data Cleaning: Handled missing values in the dataset using mean imputation.

Normalization: Scaled data using MinMaxScaler (0 to 1 range) to assist LSTM convergence.

Feature Engineering: Created a sliding window with a look-back of 25 hours to predict the next hour's load.

Architecture: Built a Sequential model with a 50-unit LSTM layer followed by a Dense output layer.
