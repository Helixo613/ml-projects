# NIFTY 50 Minute-Level Price Prediction 📈

This project leverages multiple time-series forecasting models — **Prophet**, **ARIMA**, and **LSTM** — to predict the minute-level closing price of the NIFTY 50 index. The notebook includes data preprocessing, exploratory analysis, and model building.

## Overview

The main steps covered in this notebook:
- Loading and preprocessing minute-level NIFTY 50 data
- Visualizing trends and patterns
- Time series decomposition
- Forecasting using:
  - Facebook Prophet
  - ARIMA
  - Long Short-Term Memory (LSTM)

##  Dataset

The dataset used:
- **NIFTY 50_minute_data.csv**: Minute-wise stock data

> The data is sourced from Kaggle (or can be replaced with equivalent time-series data).

##  Tech Stack

- Python (Pandas, Numpy)
- Visualization: Matplotlib, Seaborn
- Time Series: Statsmodels, Prophet
- Deep Learning: Keras/TensorFlow (for LSTM)

##  How to Run

> If you're running this notebook on **Kaggle**, the dataset is already available via the input directory.

If you're running locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nifty50-prediction.git
   cd nifty50-prediction

2.  Download the dataset from Kaggle and place NIFTY 50_minute_data.csv in a folder named data/
3.  pip install -r requirements.txt
4.  jupyter notebook nifty-50-min-prediction-prophet-armia-lstm.ipynb

