# Airbnb-stock-prediction
🏘️ Airbnb Stock Price Prediction
A machine learning project focused on predicting Airbnb (ABNB) stock prices using regression models, technical indicators, and historical market data.

📌 Project Overview
This project builds a complete workflow for stock price forecasting, including data preprocessing, exploratory analysis, feature engineering, model training, and evaluation. The goal is to understand market behavior and generate accurate price predictions.

🧰 Tech Stack
Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Environment: Jupyter Notebook / Google Colab
🔄 Workflow Summary
1. Data Collection
Historical Airbnb stock data imported from Yahoo Finance containing:

Date, Open, High, Low, Close, Adj Close, Volume
2. Exploratory Data Analysis (EDA)
Price trends over time
Volatility and daily returns
Volume patterns
Correlation analysis
3. Feature Engineering
Moving Averages (MA7, MA14, MA30)
Lag features
Volatility metrics (rolling std)
Date-based features (day, month, quarter)
Normalization for ML compatibility
4. Modeling
Models used:

Linear Regression (baseline)
Random Forest Regressor (best performance)
5. Evaluation
Metrics:

RMSE
MAE
R² score
Result: Random Forest achieved the highest accuracy and stable predictions.

6. Prediction
Generated short-term forecasts
Analyzed feature importance influencing stock price behavior
📁 Project Structure
AirBnB Stock Price Prediction/

│── notebooks/
│── src/
│── README.md
│── requirements.txt
📈 Key Findings
Airbnb stock shows seasonal patterns and volatility cycles
Engineered features significantly boost prediction accuracy
Random Forest outperforms linear models due to non-linear behavior
🚀 Future Improvements
Add LSTM/GRU deep learning models
Deploy model using Flask or Streamlit
Integrate real-time stock market API
