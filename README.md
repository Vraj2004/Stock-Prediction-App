## Stock Prediction System

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

NOTE: TRY TO ACCESS WEBSITE DIRECTLY!

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

[streamlit-main-2024-09-18-13-09-54.webm](https://github.com/user-attachments/assets/42d02404-e849-4d96-bbde-217b8bd3125c)
![image](https://github.com/user-attachments/assets/6f444be3-9e35-47a9-ae8f-587723a3b69e)
