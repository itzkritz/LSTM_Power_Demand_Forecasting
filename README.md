# Power Demand Forecasting (LSTM)
# Overview
This project uses Deep Learning to predict future electrical power demand. I built a Long Short-Term Memory (LSTM) neural network, which is a specialized type of AI that can "remember" past patterns in time-series data to make accurate future predictions.

Accurate forecasting helps energy companies prevent power outages and manage resources more efficiently.

# Key Features
Automated Cleaning: Handles missing data through mean imputation.

Time-Series Windowing: Converts raw data into sequences (using the last 25 hours to predict the next hour).

Deep Learning: Uses an LSTM architecture to capture complex trends that simple models miss.

Evaluation: Measures success using standard industry metrics (MAE, MSE, and RMSE).

# Tech Stack
Deep Learning: TensorFlow / Keras

Data Science: Pandas, NumPy, Scikit-Learn

Visualization: Matplotlib

# Model Results
The model successfully learned the energy consumption patterns with very low error rates on the test data:
Mean Absolute Error (MAE): 0.02174321748316288 MWh

Mean Squared Error (MSE): 0.0008979527628980577 MWh

Root Mean Squared Error (RMSE): 0.029965859955924136 MWh
