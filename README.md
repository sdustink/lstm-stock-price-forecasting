# LSTM Stock Price Forecasting

Forecasting stock prices of **Alphabet Inc. (GOOGL)** and **Intel Corporation (INTC)** using Long Short-Term Memory (LSTM) neural networks. The project focuses on applying deep learning techniques to historical stock price data for time-series forecasting.

## 📊 Dataset

Historical stock market data for **GOOGL** and **INTC**, containing stock price information used to train and evaluate the LSTM models.

## ⚙️ Methodology

1. Load and preprocess historical stock price data.
2. Prepare sequential time-series data using a sliding-window approach.
3. Split the data into training and testing sets while preserving the temporal order.
4. Train separate LSTM models for GOOGL and INTC stock price forecasting.
5. Generate predictions on the test data.
6. Evaluate and visualize the forecasting results.

## 📈 Results

The trained LSTM models generate forecasts for both **GOOGL** and **INTC** stock prices. Model performance and prediction results are evaluated and visualized within the respective notebooks.

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## 📂 Project Structure

```text
LSTM-Stock-Price-Forecasting/
├── google_lstm.ipynb
└── intc_lstm.ipynb
```
