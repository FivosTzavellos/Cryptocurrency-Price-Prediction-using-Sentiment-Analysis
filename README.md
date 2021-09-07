# Thesis_ECE_UTH
Cryptocurrency Price Prediction using Sentiment Analysis

In the last few years there has been an increased interest in cryptocurrencies and the blockchain technology. It is getting harder and harder to imagine a future without the
worldwide adoption of cryptocurrencies. The extreme volatility that is observed in the prices of almost all the cryptocurrencies highlights the importance of predicting
the future movement of the price inside a specific window in time. It could prove a very profitable investment to be able to forecast the price in a precise manner. 
This thesis takes steps towards this direction by extracting tweets concerning Bitcoin, by processing them and removing the ones that are considered automated messages 
from botted accounts through the use of a filter constructed for this purpose, by performing Sentiment Analysis with Vader while simultaneously including some cryptocurrency 
specific terminology in the calculations, by visualising the Pearson, Kendall and Spearman correlation between the results of the aforementioned sentiment analysis and the price
of Bitcoin and by extracting real time data, feeding them to the XGBoost algorithm and using them alongside other features to predict the price in the next minute.
The results displayed through graphs and measured according to certain error metrics seem quite promising, with a Root Mean Squared Error score of 27 USD for the full dataset 
and 24.5 USD for the dataset without bots.
