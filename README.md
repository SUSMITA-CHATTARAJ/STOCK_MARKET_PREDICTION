# STOCK_MARKET_PREDICTION

This project aims at predicting stock market by using financial news, Analyst opinions and quotes in order to improve quality of output. It proposes a novel method for the prediction of the stock market closing price. Many researchers have contributed in this area of chaotic forecast in their ways. Fundamental and technical analyses are the traditional approaches so far. ML is another popular way to identify unknown and hidden patterns in data is used for share market prediction. 

For our project, we focused on two main algorithms for recommendations: Linear Regression and Random Forest.

Linear Regression: - To describe the linear association between quantitative variables, a statistical procedure called regression often is used to construct a model. Regression is used to assess the contribution of one or more “explanatory” variables (called independent variables) to one “response” (or dependent) variable. 

Any straight line in two‐dimensional space can be represented by this equation:

y = a + bx

Random Forest Regressor: - A Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging. 

PROBLEM STATEMENT:           
                 
                 The rate of investment and business opportunities in the Stock market can increase if an efficient algorithm could be devised to predict the short term price of an individual stock.In this report, we will see if there is a possibility of devising a model using Recurrent Neural Network which will predict stock price with a less percentage of error. And if the answer turns to be YES, we will also see how reliable and efficient will this model be.
                 
DATASET DETAILS:

Predicting Stock prices is a great use case of machine learning both for financial and time series analysis. Tesla has been in the eyes of the world for a long time now as governments of so many countries all over the world are supporting the vision of Tesla. The dataset will be downloaded as “Tesla.csv” from kaggle.com

•	Date – Format of date is: “yy-mm-dd”
•	Open – Price of the stock at open market
•	High – Highest price reached in the day
•	Low – Lowest price reached in the day
•	Close – Price of the stock at the close market
•	Volume – Number of shares traded
•	Name – The name of the stock ticker

WORK FLOW: -

•	First, stock time series data are divided into windows of different lengths. The windows are summarized and represented by technical indicators and news sentiment features.

•	Second, hierarchical clustering is employed to cluster the windows and categorize their market styles; the window lengths and number of market styles are carefully tuned to achieve the best clustering results.

•	Third, a distance measurement is proposed to distinguish among rotating patterns within the market styles to verify the usability of the market styles.

•	Finally, a stock price prediction framework is constructed to predict future stock price trends based on data belonging to the same market styles.

