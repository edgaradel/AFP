# AFP Advanced Finance Project

How do market sentiment and investor behaviour relate to the price and contribute to the volatility of Bitcoin and other cryptocurrencies?



Standard & Poors Financial Services LLC 
July 2023-December 2023

This paper examines the long-term price trend and volatility driven by key dynamics of cryptocurrency price volatility. It profiles different cryptocurrencies, such as Bitcoin, Ethereum, Ripple, Cardano, and USD Coin, since 2016. The primary goal is to identify these key dynamics and determine if market sentiment plays a role in establishing a possible pricing directionality pattern. We will then analyze market sentiment to identify a possible correlation between these drivers and observe the association with cryptocurrency price volatility. Using empirical techniques and regression analysis, this study aims to contribute to understanding the relationships between sentiment and cryptocurrency price fluctuations, with a specific emphasis on Bitcoin.


The study aims to identify sentiment features and factors influencing Bitcoin's price variations and volatility using machine learning and numerical methods to uncover statistically significant findings. An improved understanding of financial sentiment within news and social media can be crucial for a better understanding of market structures.

Work using some research of the White Paper:

News-Based Sparse Machine Learning Models for Adaptive Asset Pricing
Liao Zhu, Haoxuan Wu, and Martin T. Wells
Department of Statistics and Data Science, 
Cornell University, Ithaca, New York, USA

and the Article

News vs. Sentiment: Predicting Stock Returns from News Stories
June 2017 Financial Analysts Journal 73(3):1-17
Heston, S. L., & Sinha, N. R.

In this paper, they concluded that positive and negative words in financial literature differ from words in other disciplines. Since then, many uses in different works have expanded the dictionary for better predictive results.


Machine learning Strategy used:

Develop a Long Short-Term Memory (LSTM) model using time series data. The LSTM model is defined with two LSTM layers (each with 50 units) and dropout layers (with a dropout rate of 20%) to prevent overfitting. The output layer is a dense layer with one unit. The model is compiled using the Adam optimizer and mean squared error loss function.

Coding Steps:

1. Imports and Dependencies
2. Set Parameters
3. Split Data: Splits data into training and testing sets based on a cutoff date.
4. Normalize Data: Scales features range between 0 and 1.
5. Create Sequences: Converts data into sequences for LSTM model input.
6. Model Definition and Training: Defines a Sequential LSTM model with dropout layers.
Model Training: Trains the LSTM model on the training sequences.
Model Evaluation: Predicts and evaluates the model performance on the test sequences using MSE.






