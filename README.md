# Dollar Forecasting using LSTM and GRU

This project focuses on predicting the future price movement of the dollar using Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) neural networks. The goal is to build models capable of forecasting whether the dollar price will increase or decrease in the next 6 hours based on historical data.

## Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Binary Classification](#binary-classification)
- [Simulation and Capital Management](#simulation-and-capital-management)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Introduction

The fluctuation of the dollar price in the market is influenced by various factors such as economic indicators, geopolitical events, and market sentiment. Predicting these price movements accurately can be beneficial for traders and investors in making informed decisions. In this project, we leverage deep learning techniques, particularly LSTM and GRU, to forecast the direction of the dollar price movement.

## Data Preprocessing

The dataset used in this project contains historical data of the dollar price at hourly intervals. Before feeding the data into the models, preprocessing steps such as handling missing values, normalizing features, and splitting the data into training and testing sets are performed.

## Feature Engineering

Several additional features are engineered from the original dataset to enhance the model's predictive capability. These features include time-related features, rolling statistics, and lagged values.

## Model Architecture

Two types of recurrent neural network (RNN) architectures, LSTM and GRU, are utilized in this project for dollar price forecasting. Both architectures are capable of capturing sequential dependencies in the data, making them suitable for time series prediction tasks.

## Training and Evaluation

The models are trained using the training data and evaluated on the testing data. The evaluation metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) are used to assess the models' performance.

## Binary Classification

In addition to predicting the dollar price, a binary classification model is developed to predict whether the dollar price will increase or decrease within the next 6 hours. This model enables us to make trading decisions based on the predicted price movements.

## Simulation and Capital Management

A simulation of trading operations is conducted based on the predictions of the binary classification model. Capital management strategies are implemented to simulate buying and selling actions, considering the predicted price movements.

## Results

The performance of the models is analyzed based on various evaluation metrics. The effectiveness of the models in predicting dollar price movements and the profitability of the simulated trading operations are discussed.

## Conclusion

In conclusion, LSTM and GRU neural networks show promise in forecasting the dollar price movement. The binary classification model provides valuable insights for making trading decisions, and the simulation demonstrates the potential for profitable trading strategies.

## Future Work

Future work could focus on further improving the model architectures, exploring additional features, and optimizing trading strategies for better profitability. Additionally, incorporating external factors such as news sentiment analysis could enhance the models' predictive capability.
