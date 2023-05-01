# RNN_stock_prediction
Using Recurrent Neural Network to predict Next day's Stock Price of Tesla
<h3>Predicting next day's Stock Price of Tesla</h3>
Introduction
The aim of this code is to predict the stock price of Tesla for the next day 
using the past nine days' stock prices. The code uses five-year stock data for Tesla 
from Yahoo Finance(https://finance.yahoo.com/quote/TSLA?p=TSLA&.tsrc=fin-srch). 
The models used for prediction are Simple RNN, LSTM, and GRU.

<h3>Libraries Used</h3>

<ol>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib.pyplot</li>
    <li>tensorflow</li>
    <li>sklearn</li>
</ol>



<h3>Data Preparation</h3>
The data is collected from Yahoo Finance and stored in a pandas dataframe. The dataframe is then cleaned and prepared for analysis. The data is split into sequences of nine days and converted into numpy arrays. The resulting array is then reshaped to fit the models' input size.

<h3>Models</h3>
<ol>
    <li>Simple RNN with one layer</li>
    <li>LSTM with one layer</li>
    <li>LSTM with multiple layers</li>
    <li>GRU with one layer</li>
    <li>GRU with multiple layers</li>
</ol>


For each model, the structure, number of parameters, and summary are printed. The models are then trained and tested, and the performance metrics are captured in a dataframe.

<h3>Prediction</h3>
To predict the next day's stock price, the past nine days' stock prices are inputted into the model. The predicted stock price is then obtained by passing this input into the model.

<h3>Conclusion</h3>
The performance metrics of the models are compared to determine the best model for predicting the next day's stock price of Tesla. The model with the lowest RMSE is considered the best model. This code can be used as a basis for predicting the next day's stock price for other companies as well.
