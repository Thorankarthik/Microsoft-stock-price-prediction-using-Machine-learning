# Microsoft-stock-price-prediction-using-Machine-learning

## Introduction
Stock market prediction has been a significant area of research in Machine Learning. Algorithms such as regression, classifier, and support vector machine (SVM) help predict the stock market. This repository presents a simple implementation of analyzing and forecasting stock market predictions using machine learning. The case study focuses on a popular online retail store, utilizing Random Forest, a powerful tree-based technique for predicting stock prices.

## What is the Stock Market?
The stock market is a collection of markets where stocks and other securities are bought and sold by investors. Publicly traded companies offer shares of ownership to the public, and those shares can be bought and sold on the stock market. Investors can make money by buying shares of a company at a low price and selling them at a higher price. The stock market is a key component of the global economy, providing businesses with funding for growth and expansion. It is also a popular way for individuals to invest and grow their wealth over time.

## Importance of the Stock Market
| Importance | Description |
|------------|-------------|
| Capital Formation | It provides a source of capital for companies to raise funds for growth and expansion. |
| Investment Opportunities | Investors can potentially grow their wealth over time by investing in the stock market. |
| Economic Indicators | The stock market can indicate the overall health of the economy. |
| Job Creation | Publicly traded companies often create jobs and contribute to the economy’s growth. |
| Corporate Governance | Shareholders can hold companies accountable for their actions and decision-making processes. |
| Risk Management | Investors can use the stock market to manage their investment risk by diversifying their portfolio. |
| Market Efficiency | The stock market helps allocate resources efficiently by directing investments to companies with promising prospects. |

## What is Stock Market Prediction?
Before implementing the software to anticipate stock market values, let's examine the data on which we will be working. We will use the stock price data of Microsoft Corporation (MSFT) as reported by the National Association of Securities Dealers Automated Quotations (NASDAQ). The stock price data will be supplied as a Comma Separated File (.csv) that can be opened and analyzed in Excel or a spreadsheet.

MSFT’s stocks are listed on NASDAQ, and their value is updated every working day of the stock market. Note that the market does not allow trading on Saturdays and Sundays, creating a gap between the two dates. The Opening Value, the Highest and Lowest values of the stock on the same day, and the Closing Value at the end of the day are indicated for each date. Analyzing this data is useful for stock market prediction using machine learning techniques.

The Adjusted Close Value reflects the stock’s value after dividends have been declared. Additionally, the total volume of the stocks in the market is provided. A Machine Learning/Data Scientist can analyze this data to develop algorithms that extract patterns from the historical data of Microsoft Corporation stock.

## Stock Market Prediction Using the Long Short-Term Memory Method
We will use the Long Short-Term Memory (LSTM) method to create a Machine Learning model to forecast Microsoft Corporation stock values. LSTM is a deep learning artificial recurrent neural network (RNN) architecture that can handle single data points (such as pictures) and full data sequences (such as speech or video).

