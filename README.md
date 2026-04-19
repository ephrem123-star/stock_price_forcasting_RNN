📈 Stock Price Prediction using Deep Learning (RNN, GRU, LSTM)
🚀 Project Overview

This project is a time-series forecasting system that predicts Apple (AAPL) stock closing prices using deep learning models: RNN, GRU, and LSTM.
The best-performing model (GRU) is used for future stock price forecasting and interactive visualization through a Streamlit app.

🎯 Objectives
Analyze historical AAPL stock data
Build deep learning models for time-series prediction
Compare RNN, GRU, and LSTM performance
Predict future stock prices
Deploy an interactive Streamlit application
📊 Dataset
Source: Historical stock market dataset (AAPL only)
Features used:
Open
High
Low
Close (Target)
Volume
🧠 Models Used
Recurrent Neural Network (RNN)
Gated Recurrent Unit (GRU)
Long Short-Term Memory (LSTM)
⚙️ Workflow
Data preprocessing & cleaning
Feature scaling (MinMaxScaler)
Time-series sequence creation
Train/Test split (time-aware)
Model training (RNN, GRU, LSTM)
Evaluation (MAE, RMSE)
Future forecasting
Streamlit deployment
📈 Results
Model 	MAE 	RMSE
0 	RNN 	27.254181 	28.002142
1 	GRU 	11.531270 	12.354025
2 	LSTM 	15.320741 	16.351496


✔ GRU performed best overall.

🔮 Features
Stock price prediction (AAPL)
Multi-model comparison
Future forecasting (1–14 days)
Interactive Streamlit dashboard
Real-time visualization
🖥️ Streamlit App

Run locally:

streamlit run app.py
💾 Model Files
gru_stock_model.h5 → best trained model
scaler.pkl → MinMax scaler
df_model.csv → processed dataset
📌 Key Insight

GRU model effectively captures temporal dependencies in stock price data and provides the most stable and accurate predictions among tested models.

🚀 Future Improvements
Real-time stock API integration
Trading signal system (BUY / SELL / HOLD)
Multi-stock prediction
Cloud deployment

👨‍💻 Author

Ephrem Ftye Aspiring Data Scinetist 
