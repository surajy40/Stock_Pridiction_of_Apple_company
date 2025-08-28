
# Apple Stock Price Prediction
This project demonstrates how to predict Apple Inc. (AAPL) stock prices using Recurrent Neural Networks (SimpleRNN and LSTM). It is implemented in Python with TensorFlow/Keras, and the workflow is documented in the Jupyter Notebook Apple_Stock_pri.ipynb.



## Project Overview

- Goal: Forecast Apple’s stock price trends using historical data.

- Dataset: AAPL.csv (includes Date, Open, High, Low, Close, Adj Close, Volume).

- Models Used:

  - SimpleRNN

  - LSTM
## Workflow

1. Data Preprocessing

  - Load dataset (AAPL.csv)

  - Handle missing values

  - Use Close Price as the target feature

  - Normalize values with MinMaxScaler

  - Convert time series into sequences for supervised learning

2. Model Development

  - Build SimpleRNN and LSTM architectures with Keras

  - Train models on 80% of the data

  - Evaluate on 20% test set

3. Evaluation & Visualization

  - Compare predictions with actual prices

  - Metrics: Mean Squared Error (MSE)

  - Visualize stock price trends
## Repository Structure

📦 Apple-Stock-Prediction

  ┣ 📜 Apple_Stock_pri.ipynb   # Main notebook

  ┣ 📜 AAPL.csv                # Dataset

  ┣ 📜 README.md               # Project documentation

  ┗ 📜 requirements.txt        # Python dependencies

## Skills

- Python
- Tensorflow
- Numpy
- Pandas
- Matplotlib
- Scikit-learn