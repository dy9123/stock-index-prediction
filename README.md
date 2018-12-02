# stock-index-prediction
This project is still in progress. We employed wavelet-autoencoder-LSTM as suggested by Bao, Yue and Rao.
# Motivation
In this project, we employed neural network to predict future stock index.
# Data 
We first examined our model on S&P 500 index. Later, we will move onto Hang Send Index.
We used daily S&P 500 index, including its open price, close price, trading volume, etc.
Moreover, we also used technical indicators and macro economy data.
# Model
We first employed wavelet transformation to reduce the noise of the data.
We then tested regular autoencoder and stacked autoencoder to reduce the dimension.
We then employed LSTM to predict future stock index.
In addition, we employed batch normalization, gradient clipping to further improve our model.
#Evaluation
We report the final R^2 as the measure of our model.
#Files Description
Data file: GSPC, HSI, raw data
Autoencoder: 
Stacked Autoencoder: st
output from autoencoder:
output from stacked autoencoder:

Reference
Bao, W., Yue, J., & Rao, Y. (2017). A deep learning framework for financial time series using stacked autoencoders and long-short term memory. PLoS One, 12(7), E0180944.
