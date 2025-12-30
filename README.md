# Cryptocurrency Price Forecasting using ML Models
## 📘 Introduction

### What is Cryptocurrency?
A cryptocurrency is a digital or virtual currency that is secured by cryptography, making it nearly impossible to counterfeit or double-spend. Unlike traditional fiat currencies, most cryptocurrencies are decentralized networks based on blockchain technology.

### How and Why Prices Fluctuate
Cryptocurrency markets are known for their extreme volatility. Prices can fluctuate because of:
1. Supply and Demand
2. Market Sentiment
3. Government Crackdowns or the Adoption of New Laws

### Why Use Machine Learning for Prediction?
Predicting these fluctuations is challenging because they are non-linear and highly complex. Traditional statistical models often fail to capture the subtle patterns in historical price data. Machine Learning (ML) models are used because they can identify patterns with multiple data and can process vast amounts of data and provide real-time or near-real-time projections that help in decision-making.

## 🤖 Machine Learning Models Used
- Linear Regression
- Extreme Gradient Boosting (XGBoost)
- K-Nearest Neighbors (KNN)
- Random Forest
- Support Vector Regression (SVR)


## 💰 Cryptocurrencies Analyzed
This study evaluates four major cryptocurrencies:

- Bitcoin (BTC)
- Ethereum (ETH)
- Monero (XMR)
- Wrapped Bitcoin (WBTC)

## 📊 Dataset Details

Each cryptocurrency is provided as an individual CSV file, resulting in a total of **23 files**, each corresponding to a distinct cryptocurrency. The dataset includes daily market information such as opening price, highest price, lowest price, closing price, trading volume, and market capitalization.

| Attribute      | Description                                                     |
| -------------- | --------------------------------------------------------------- |
| Cryptocurrency | Bitcoin, Ethereum, Ripple, etc. (23 different cryptocurrencies) |
| Date           | Date of observation                                             |
| Open           | Opening price on the given day                                  |
| High           | Highest price recorded on the given day                         |
| Low            | Lowest price recorded on the given day                          |
| Close          | Closing price on the given day                                  |
| Volume         | Total trading volume on the given day                           |
| Market Cap     | Market capitalization in USD                                    |
| Time Period    | April 2013 – July 2021                                          |

## 🔄 Pipeline

The methodology comprises data preprocessing, the implementation of five machine learning models, and the evaluation of each model. It is evaluated based on how each model performs for each type of cryptocurrency chosen.

<img width="2006" height="522" alt="image" src="https://github.com/user-attachments/assets/35951df6-335f-4428-9b57-18ea87c9a5a0" />

## 📈 Results

The models were meticulously evaluated using Mean Squared Error (MSE), R-squared ($R^2$), and Mean Absolute Percentage Error (MAPE).
- **Best Performance for Bitcoin:** Linear Regression achieved superior performance with an $R^2$ score of 0.982324
- **Best Performance for Wrapped Bitcoin:** Linear Regression also excelled here with an $R^2$ score of 0.978025
- **Best Performance for Monero:** XGBoost delivered the best results with the lowest MSE of 325.33

## 📚 Citation
If you use this work or refer to it in your research, please cite the following paper:

```
@INPROCEEDINGS{10941381,
  author    = {Priya, S. Baghavathi and Srinivasan Anusha, Janani and S, Priyanga and Chatiyode, Veda},
  booktitle = {2024 International Conference on Integration of Emerging Technologies for the Digital World (ICIETDW)},
  title     = {Crypto Prophets: Machine Learning Oracles for Price Forecasting},
  year      = {2024},
  pages     = {1--8},
  keywords  = {Cryptocurrency, Machine Learning, Predictive Analytics, Price Prediction, Market Volatility},
  doi       = {10.1109/ICIETDW61607.2024.10941381}
}
```
