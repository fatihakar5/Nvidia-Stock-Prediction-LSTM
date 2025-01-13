# Nvidia Stock Analysis & Prediction with LSTM

![results](https://github.com/user-attachments/assets/d6290e5c-0cba-49e6-a8ba-da81d50f49f4)


## Project Description
This project uses the LSTM (Long Short-Term Memory) model to predict Nvidia stock prices. Since stock prices are time series data, LSTM networks are highly effective in learning time dependencies in such data. In this notebook, we trained an LSTM model on historical Nvidia stock price data and predicted future stock prices.

## Methodologies Used
In this project, LSTM (Long Short-Term Memory) networks are used to predict Nvidia stock prices from time series data. Several preprocessing and visualization steps were applied to enhance model performance.

## The project was carried out with the following steps:

- Data Collection: The Nvidia Stock Data was downloaded from Kaggle.
- Data Preprocessing: The data was normalized and prepared to be suitable for the LSTM model.
- Model Training: The LSTM model was trained, and predictions were made on test data.
- Prediction Evaluation: Metrics such as MSE (Mean Squared Error) were used to evaluate the model's performance.
- Visualization: The real and predicted stock prices were compared visually.

## Dataset
The dataset contains daily prices of Nvidia stock and is sourced from Kaggle. The dataset used in this project can be downloaded here.

##  Project Flow
1. Data Loading and Exploration
First, the Nvidia stock data was loaded using pandas, and basic statistical analyses were performed. In this step, missing values, chronological order, and data types were checked.

2. Data Preprocessing
In the data preprocessing step, the data was normalized. To improve the efficiency of the LSTM model, the data was scaled using MinMaxScaler to a range between 0 and 1.

3. Time Series Visualization
Visualizing the data is an important step in time series modeling. Below are the descriptions of the time series plots for Close, Open, High, and Low prices:

      3.1. Close Price Time Series Plot
      This plot shows the variation of Nvidia's closing price over time. The closing price is typically the most important value for investors and analysts.
      
      3.2. Open Price Time Series Plot
      This plot shows the variation of Nvidia's opening price over time. The opening price represents the starting level of the market and the first price of the day’s trading.
      
      3.3. High Price Time Series Plot
      This plot shows the variation of Nvidia's highest price over time. The high price is the maximum value the stock reaches during the trading day.
      
      3.4. Low Price Time Series Plot
      This plot shows the variation of Nvidia's lowest price over time. The low price represents the minimum value the stock reaches during the trading day.

4. Model Training and Prediction
After training the model, future stock prices were predicted. The predictions were compared with actual prices, and the model's accuracy was evaluated. The MSE (Mean Squared Error) was computed to measure the performance of the model.

5. Results and Visualization
The differences between the predicted and actual prices were visualized. The model's performance over time was observed through visualizations.

6. Prediction for the Next 5 Days
Based on historical data, the model predicted the stock prices of Nvidia for the next 5 days.

## Model Performance
The performance of the model was measured using the MSE (Mean Squared Error) metric. A lower MSE indicates that the model made accurate predictions.

MSE (Mean Squared Error): 0.67
