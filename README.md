# Temperature Forecasting Using RNN (LSTM)

## Project Overview

This project implements a Temperature Forecasting System using a Long Short-Term Memory (LSTM) based Recurrent Neural Network (RNN). The model is trained on historical climate data to predict future temperature values. Time-series forecasting is performed using deep learning techniques to capture temporal patterns and trends in temperature data.[

](https://github.com/sakshirakate11/Temperature-Forecasting-Using-RNN-LSTM/blob/main/Temperature_Forecasting_using_RNN.ipynb)
## Aim

To develop a temperature forecasting model using LSTM networks for accurate prediction of future temperature values from historical weather data.

## Objectives

* Preprocess and normalize temperature data.
* Create time-series sequences for training.
* Build and train an LSTM-based forecasting model.
* Predict future temperature values.
* Evaluate model performance using RMSE.
* Visualize actual and predicted temperature trends.

## Dataset

The project uses the Daily Delhi Climate Dataset:

* DailyDelhiClimateTrain.csv
* DailyDelhiClimateTest.csv

The dataset contains:

* Mean Temperature
* Humidity
* Wind Speed
* Mean Pressure

## Technologies Used

* Python
* Google Colab
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

## Methodology

1. Load and preprocess the dataset.
2. Normalize temperature values using Min-Max Scaling.
3. Generate time-series sequences.
4. Split data into training and testing sets.
5. Build and train an LSTM model.
6. Predict future temperatures.
7. Evaluate predictions using RMSE.
8. Visualize forecasting results.

## Model Architecture

Dataset → Preprocessing → Normalization → Sequence Generation → LSTM Network → Prediction → RMSE Evaluation

## Results

The LSTM model successfully learned temperature patterns from historical data and generated accurate forecasts.

**RMSE Achieved:** 2.38°C

## Repository Contents

* Temperature_Forecasting_using_RNN.ipynb
* DailyDelhiClimateTrain.csv
* DailyDelhiClimateTest.csv
* README.md

## Conclusion

This project demonstrates the effectiveness of LSTM-based deep learning models for temperature forecasting. The model achieved good prediction accuracy and can be further improved by incorporating additional weather parameters and larger datasets.
