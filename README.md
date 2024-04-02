# Modeling-multiple-stock-prices-using-a-single-model

## Predicting Multiple Stocks using LSTM

This repo is an attempt to verify the effectiveness of LSTM (Long Short-Term Memory) models in predicting the stock prices of multiple stocks simultaneously. The project was primarily developed and trained within a Kaggle Jupyter notebook.

### About the Project

The primary objective of this project is to assess the feasibility of employing LSTM neural networks for predicting stock prices across various industries. The project utilizes the Nifty-50 dataset, encompassing stock market data from 2000 to 2021.

[Kaggle Notebook Link](https://www.kaggle.com/code/dobariyanaitik/predicting-multiple-stocks-using-a-single-rnn/notebook)

The dataset used in this project is sourced from Kaggle and consists of Nifty-50 stock market data, providing comprehensive insights into the performance of various stocks over time. The project entails training an LSTM model on data from six different stocks belonging to distinct industries. Moreover, the project involves verifying the independence of stocks by assessing the correlation among them. The data is segmented into training and testing sets, and the LSTM model is trained to discern patterns and fluctuations in stock prices effectively.

![__results___30_0](https://github.com/NaitikDobariya/Modeling-multiple-stock-prices-using-a-single-model/assets/113834773/15d3ddfd-819b-4ef6-86f5-098e57029257)


#### Libraries Used

- pandas
- numpy
- seaborn
- datetime
- matplotlib
- sklearn
- tensorflow

### Results

The LSTM model demonstrates commendable performance in predicting the stock prices of multiple stocks. It effectively captures the underlying patterns and fluctuations in stock prices.

![__results___32_0](https://github.com/NaitikDobariya/Modeling-multiple-stock-prices-using-a-single-model/assets/113834773/df965082-acd6-4449-8937-bcfdb9925102)


The model exhibits promising results, but it is essential to acknowledge the inherent uncertainties and complexities associated with stock market prediction.
