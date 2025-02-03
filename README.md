# Stock-Price-Prediction-using-LSTM
Overview
Stock price prediction is a challenging task due to the highly volatile nature of financial markets. This project leverages a Long Short-Term Memory (LSTM) neural network, a type of recurrent neural network (RNN), to forecast stock prices based on historical closing prices. The implementation covers a complete pipeline, including data preprocessing, exploratory data analysis (EDA), model training, and evaluation. By analysing past stock price movements and trends, the model aims to generate predictions that can provide insights into future price behavior.

### Dataset
The dataset used for this project is Zomato.csv, which contains historical stock prices of the Zomato company. The dataset consists of essential attributes such as the Date and the Close price, where the closing price represents the stock’s final traded value for each trading day. The data is cleaned and formatted while being used in the model, ensuring that missing values are handled and dates are properly structured for time series analysis.

### Key Features
📌 Data Preprocessing
- Cleaning, formatting, and sorting stock price data
- Normalizing values to improve model performance

📊 Exploratory Data Analysis (EDA)
-  Autocorrelation Analysis (ACF & PACF)
-  Trend & Seasonality Decomposition using Statsmodels
-  Moving Averages & Daily Returns

🤖 LSTM Model Implementation
- TensorFlow/Keras-based LSTM with multiple layers
- Sequence Creation: Uses 90-day lookback for forecasting
- Saves the trained model for future predictions

🔍 Prediction & Visualization
- Generates future stock price predictions
- Compares actual vs. predicted closing prices using Matplotlib
 
### Conclusion
This project demonstrates the power of LSTM networks in time series forecasting, particularly for stock price prediction. By leveraging historical price data and deep learning, the model provides insights into potential future trends. While LSTMs are effective in capturing patterns, stock markets remain inherently unpredictable due to external factors. Future improvements can include adding more technical indicators, experimenting with hybrid models, or integrating real-time data streams.

🔹 Next Steps: Optimize hyperparameters, fine-tune the model, and explore alternative deep learning architectures! 🚀





