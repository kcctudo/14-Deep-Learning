# 14-Deep-Learning
# Introduction
* This project uses  LSTM RNN a neural network to predict the BTC's price.  It uses two different methods to train to predict.  
One method is using its lagged price to predict the future price.  The other is to use the fear and greed index for BTC's price prediction.  
We'll compare the two methods and assess which method is a better predictor.
# List of modules:
tensorflow, numpy, pandas, hvplot
# Model evaluation:
The model that uses lagged price has lower loss function and has a better prediction that one that uses Fear and Greed variable.
The window size of 10 works best for the model.
