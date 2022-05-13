# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

1. [Prepare the data for training and testing](#prepare-the-data-for-training-and-testing)
2. [Build and train custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
3. [Evaluate the performance of each model](#evaluate-the-performance-of-each-model)

- - -
### Evaluate the performance of each model

> Which model has a lower loss?  
> The closing price predictor model had a lower loss than the FNG pridictor model.
> * FNG  
> 
> ![FNG loss](https://user-images.githubusercontent.com/93834612/168389141-54372f02-7c7d-48b6-8b94-a2a6140f8719.png)

> * Closing Price Predictor  
> 
> ![closingpriceloss](https://user-images.githubusercontent.com/93834612/168389185-351030a4-d0f1-45c7-8d45-375a0a1f3685.png)

-----
Which model tracks the actual values better over time?  
> The closing price predictor model tracks the actual values better over time.
> * Closing Price Predictor  
>![Closingpriceplot](https://user-images.githubusercontent.com/93834612/168389336-9d6a65fb-9f55-4206-a510-a604d796fa59.png)

> * FNG 
>![FNG plot](https://user-images.githubusercontent.com/93834612/168389368-31f2c5c6-8de8-4aab-80cc-9e4b8fd97b1e.png)
