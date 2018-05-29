# Bitcoin-Pricing
Machine Learning project on bitcoin pricing analysis and prediction. As the data file is huge it can be downloaded from the following link. 
https://drive.google.com/file/d/1X-rtGqBZ1qQTzysJ_yCr6HhTB_-8CCTo/view?usp=sharing 
The file contains every minute transaction data of bitcoins from December 2011 to January 2018.  


Time series analysis have been done using AR-MA, ARIMA and RNN models. The data for AR_MA and ARIMA models have been split on monthly basis and RNN model is built on daily data. Rnn model predicts well as the ampiunt of training data was huge. But the ARIMA model predicts very accurately even though just trained with around 70 data points. 

Also check out the blogpost for this project which was posted by Dataturks, for the work done by me. 
Link: https://dataturks.com/blog/bitcoin-price-prediction.php 
