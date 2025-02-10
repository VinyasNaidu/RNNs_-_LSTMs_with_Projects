# Advanced RNN and LSTM Projects for NLP and Stock Market Predictions

This repository showcases my exploration of Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTMs) networks applied to challenging real-world problems in Natural Language Processing (NLP) and Time-Series Forecasting.

## Projects Overview

### 1. Sentiment Analysis with RNN (IMDB Movie Reviews)
- **Objective:** Classify IMDB movie reviews into positive or negative sentiments using RNNs.
- **Techniques Used:** Text tokenization, padding, SimpleRNN layers, and Adam optimizer.
- **Results:** Addressed vanishing gradient issues and improved sequence processing for NLP tasks.
- **Key Takeaways:** Importance of word embeddings and advanced RNN variants like LSTMs/GRUs for better context retention in NLP.

### 2. Stock Price Prediction using LSTM
- **Objective:** Forecast stock prices using historical data from Yahoo Finance with LSTMs.
- **Approach:** Data normalization, time-series window creation, multi-layer LSTMs.
- **Performance Metric:** RMSE (Root Mean Squared Error) for accuracy assessment.
- **Key Insights:** Demonstrated LSTMs' ability to capture long-term dependencies and trends in financial time-series data.

### 3. Hyperparameter Tuning for LSTM Stock Prediction
- **Objective:** Enhance the LSTM model for stock price prediction through rigorous hyperparameter tuning.
- **Methods:** Employed Keras Tuner for both Grid Search and Random Search techniques.
- **Achievements:** Optimized model settings led to reduced loss and enhanced predictive accuracy.
- **Future Directions:** Plans to incorporate Bayesian Optimization and Attention Mechanisms.

## Getting Started

To get started with these projects:
- Clone this repo using:
  ```bash
  git clone [repository-url]
