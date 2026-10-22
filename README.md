Weather Forecasting Using LSTM
Project Overview

This project predicts daily mean temperature using historical climate data and an LSTM (Long Short-Term Memory) neural network.

Objective

The main objective is to use previous weather observations to predict the next day's mean temperature.

Dataset

The project uses the Daily Delhi Climate dataset from Kaggle.

The dataset includes:

Date
Mean temperature
Humidity
Wind speed
Mean pressure
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
TensorFlow / Keras
Google Colab
Methodology
Load and inspect the climate dataset.
Clean the data and handle missing values.
Normalize the weather features.
Create sequences using the previous 30 days.
Train an LSTM model.
Evaluate predictions using MAE and RMSE.
Compare the LSTM model with a baseline.
Plot actual and predicted temperatures.
Generate a next-day temperature forecast.
Model Evaluation

The model is evaluated using:

MAE: Mean Absolute Error
RMSE: Root Mean Squared Error

Actual evaluation values should be added after running the notebook.

Results

The notebook produces evaluation metrics, an actual-versus-predicted temperature graph, a training-history graph, and a next-day forecast.

How to Run
Open the notebook in Google Colab.
Upload the required climate CSV file.
Run the notebook cells in order.
Review the metrics and visualizations.
Dataset Source

Kaggle - Daily Climate Time Series Data

Disclaimer

The forecast is a model prediction based on historical data and is not a guarantee of future weather conditions.# weather-forecasting-lstm
