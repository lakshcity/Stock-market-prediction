# Stock-market-prediction
📝 Project Description
This project aims to predict stock market prices using various models including Linear Regression, XGBoost, and LSTM (Long Short-Term Memory) networks.
It explores technical indicators like Moving Averages, Bollinger Bands, MACD, and RSI to enhance the prediction capabilities.

The goal is to compare traditional machine learning models with deep learning models for stock forecasting and visualize market patterns.

🚀 Features
Moving Averages (MA5, MA20)

Bollinger Bands for Volatility Analysis

MACD and Signal Line for trend changes

RSI for Overbought/Oversold analysis

Correlation Heatmap

Machine Learning Models:

Linear Regression

XGBoost Regressor

Deep Learning Model:

LSTM Neural Network

Performance Metrics:

MSE (Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

Visualization of Results

Comparative Analysis of all models

📚 Tech Stack
Python

Libraries Used:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

tensorflow (for LSTM)

📊 Results
Linear Regression performed decently but lacked understanding of sequential patterns.

XGBoost handled non-linear relationships better and showed improved performance.

LSTM captured time dependencies and gave the best performance on unseen stock price data.

Performance was evaluated based on MSE, MAE, and R² Score.

Visualizations helped identify market volatility and trend changes.

🎯 Conclusion
Using technical indicators along with ML and DL models, we improved the prediction accuracy of stock closing prices.
The LSTM model outperformed other models because it is capable of learning sequential data patterns which are common in stock market data.

🔮 Future Work
Include more features like financial news sentiment.

Hyperparameter tuning for models.

Try more advanced deep learning models like GRU, Transformer-based models.

Deploy the model into a real-time stock dashboard.
