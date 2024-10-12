##Stock Prediction System

# Overview
Stock Prediction System is a machine learning tool designed to forecast stock prices using previous data from yahoo-finance. It uses Long Short-Term Memory (LSTM) networks to predict stock market trends while users can log in, save their favorite stocks, and interact with the predictions via a Streamlit inferface.

# Features
Stock prediction using an LSTM model
User authentication and stock favoriting
Streamlit-based interactive interface
SQLite3 for data storage

# Tech Stack
Python: Core logic and data processing
Keras/Scikit-learn: Machine learning framework
SQLite3: Database for user data and favorites
Streamlit: For the web interface

# Installation
Clone the repository:

bash
Copy code
git clone https://github.com/RishiP2004/Stock-Prediction-System.git
cd Stock-Prediction-System

Install dependencies:

Streamlit
(Other dependencies depending on if Model rebuild is preferred - see
Stock_ML_Predictor.ipynb)

# Run the Application
Run the application locally:

bash
Copy code
streamlit run main.py

# Usage
Logging in:
Users can log in or register
Stock favoriting:
Users can favorite stocks to remember the stock they wanted to track.
Future prediction:
The LSTM model predicts future stock trends based on historical data (60%).


