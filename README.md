# Enhancing Stock Market Prediction Using Deep Learning

# CONTENTS
[Deep Learning models](deep-learning)
  
  1.LSTM
  
  2.LSTM Bidirectional
  
  3.LSTM 2-Path
  
  4.GRU
  
  5.GRU Bidirectional
  
  6.GRU 2-Path
  
  7.Vanilla
  
  8.Vanilla Bidirectional
  
  9.Vanilla 2-Path
  
  10.LSTM Seq2seq
  
  11.LSTM Bidirectional Seq2seq
  
  12.LSTM Seq2seq VAE
  
  13.GRU Seq2seq
  
  14.GRU Bidirectional Seq2seq
  
  15.GRU Seq2seq VAE
  
  16.Attention-is-all-you-Need
  
  17.CNN-Seq2seq
  
  18.Dilated-CNN-Seq2seq

[Stacking](stacking)

  1.Deep Feed-forward Auto-Encoder Neural Network to reduce dimension + Deep Recurrent Neural Network + ARIMA + Extreme Boosting Gradient Regressor
  
  2.Adaboost + Bagging + Extra Trees + Gradient Boosting + Random Forest + XGB

[Agents](agent)
  
  1.Turtle-trading agent
  
  2.Moving-average agent
  
  3.Signal rolling agent
  
  4.Policy-gradient agent
  
  5.Q-learning agent
  
  6.Evolution-strategy agent
  
  7.Double Q-learning agent
  
  8.Recurrent Q-learning agent
  
  9.Double Recurrent Q-learning agent
  
  10.Duel Q-learning agent
  
  11.Double Duel Q-learning agent
  
  12.Duel Recurrent Q-learning agent
  
  13.Double Duel Recurrent Q-learning agent
  
  14.Actor-critic agent
  
  15.Actor-critic Duel agent
  
  16.Actor-critic Recurrent agent
  
  17.Actor-critic Duel Recurrent agent
  
  18.Curiosity Q-learning agent
  
  19.Recurrent Curiosity Q-learning agent
  
  20.Duel Curiosity Q-learning agent
  
  21.Neuro-evolution agent
  
  22.Neuro-evolution with Novelty search agent
  
  23.ABCD strategy agent

[Data Exploration](misc)

  1.Stock market study on TESLA stock, [tesla-study.ipynb](misc/tesla-study.ipynb)
  
  2.Outliers study using K-means, SVM, and Gaussian on TESLA stock, [outliers.ipynb](misc/outliers.ipynb)
  
  3.Overbought-Oversold study on TESLA stock, [overbought-oversold.ipynb](misc/overbought-oversold.ipynb)
  
  4.Which stock you need to buy? [which-stock.ipynb](misc/which-stock.ipynb)

# RESULTS

# Stock forecasting JS

LSTM Model for stock forecasting and buying simulation inside Tensorflow JS, so everyone can try!

## How-to

1. Clone this folder and just open [index.html](stock-forecasting-js/index.html),

Or, go to [stock-forecasting-js](stock-forecasting-js)!

![alt text](stock-forecasting-js/screenshot/1.png)

2. Check hyper parameters you want to tune,

![alt text](stock-forecasting-js/screenshot/2.png)

3. You can upload any stock CSV, downloaded from Yahoo finance or any website. Any error, please open an issue.

4. Train the model and wait it's fitting!

5. After done training, it will predict where to buy and sell,

![alt text](stock-forecasting-js/screenshot/3.png)

Comparing histogram and loss graph,

![alt text](stock-forecasting-js/screenshot/4.png)

