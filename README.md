# AFP Advanced Finance Project
How do Market Sentiment and Investor Behaviour relate to the price of Bitcoin and other Crypto / 

Standard & Poors Financial Services LLC 
July 2023-December 2023

The study aims to identify sentiment features and factors influencing Bitcoin's price variations using machine learning and numerical methods to identify statistically significant findings.

Machine learning Strategy used:
Develop a Long Short-Term Memory (LSTM) model using time series data. The LSTM model is defined with two LSTM layers (each with 50 units) and dropout layers (with a dropout rate of 20%) to prevent overfitting. The output layer is a dense layer with one unit. The model is compiled using the Adam optimizer and mean squared error loss function.

Coding Steps:

1. Imports and Dependencies
2. Set Parameters
3. Split Data: Splits data into training and testing sets based on a cutoff date.
4. Normalize Data: Scales features to a range between 0 and 1.
5. Create Sequences: Converts data into sequences for LSTM model input.
6. Model Definition and Training: Defines a Sequential LSTM model with dropout layers.
Model Training: Trains the LSTM model on the training sequences.
Model Evaluation: Predicts and evaluates the model performance on the test sequences using MSE.






