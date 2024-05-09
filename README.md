# LetsGrowMore Virtual Internship Program
![image](https://github.com/vinay-852/LGMVIP-DataScience-2/assets/132639307/be2c4666-662f-477c-9392-fce50a174abf)


This program provides a unique opportunity for students to work on real-world problems, enhancing their understanding of the industry and enriching their learning experience.


## Task 1: Stock Price Prediction and Forecasting using Stacked LSTM

In this project, we aim to predict the future stock prices of a company using historical stock price data. We will be using a type of Recurrent Neural Network known as Long Short Term Memory (LSTM) due to its ability to remember long-term dependencies, which is crucial when dealing with time-series data like stock prices.


### About the Dataset


The dataset used in this project contains daily stock prices for a specific company over a certain period. Each row in the dataset represents a trading day and the columns represent features such as Open, High, Low, Close, and Volume.
<br><br>
Open: The price at which the stock started trading when the market opened on that day.<br>
High: The highest price at which the stock traded during the day.<br>
Low: The lowest price at which the stock traded during the day.<br>
Close: The final price at which the stock was traded when the market closed on that day.<br>
Volume: The number of shares that were traded during the day.

### Model: LSTM sequential reggesor

The model used in this project is a Sequential Regressor with stacked LSTM layers. The LSTM (Long Short-Term Memory) is a type of Recurrent Neural Network (RNN) that is capable of learning long-term dependencies, which makes it perfect for our use-case of stock price prediction.
