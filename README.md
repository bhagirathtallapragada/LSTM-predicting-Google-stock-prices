# Predicting Google stock prices (a project to understand application of LSTMs for time series analysis

## Objective:

1. Train an LSTM on 5 years of Google stock prices data between 2012-2016
2. Predict the upward/ downward trend of Google stock prices in the first month of 2017

## Method:

1. Timestep: Stock prices for 60 days (determined optimal experimentally)
2. Design an LSTM with 5 layers (input layer with 50 units, 3 middle layers with 50 units along with dropout regularization and 1 output layer with a single unit)
3. Complie and fit the model on the training data
4. Predict and visualize results
 
