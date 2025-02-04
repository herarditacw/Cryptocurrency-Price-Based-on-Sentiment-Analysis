# Cryptocurrency Price Based on Tweet Sentiment Analysis

## Overview
This project analyzes tweet sentiment related to Bitcoin (BTC) and Ethereum (ETH) to predict cryptocurrency price fluctuations and trends. Using tweets from January 1 to December 31, 2020, we calculate daily sentiment scores (positive, neutral, negative) with the RoBERTa model and create daily engagement scores based on likes and retweets.

## Conclusion
Daily tweet volumes and sentiment sums are correlated with daily price data, revealing correlations between 0.49 and 0.8. The top-correlated features train two models: Extreme Gradient Boosting Regression and Classification Trees. Results show 59% accuracy for BTC trend prediction (precision 73%) and 54% for ETH (precision 61%). RMSE scores for price change predictions are 484.7 for BTC and 16.7 for ETH. Our findings suggest that tweet sentiment can be a valuable indicator for daily cryptocurrency trading.
