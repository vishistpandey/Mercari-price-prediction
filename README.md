## Mercari price Suggestion Challenge
### Challenge Overview
In this competition, you will predict the sale price of a listing based on information a user provides for this listing.

### Challenge Description:
Product pricing gets even harder at scale, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs.

Mercari, Japan’s biggest community-powered shopping app, knows this problem deeply. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari's marketplace.

In this competition, Mercari’s challenging you to build an algorithm that automatically suggests the right product prices.

## Real world/Business Objectives and constraints
### Objectives:

- Predict the price of an item given its condition, decsription and other related features.
- Minimize the difference between predicted and actual price (RMSLE)
## Machine Learning Problem
### Data
### Data Overview
Get the data from : https://www.kaggle.com/c/mercari-price-suggestion-challenge/data

### Data files :

- train.tsv
- test.tsv
(All these are tab-seperated files)

## Mapping the real world problem to a Machine Learning Problem
### Type of Machine Learning Problem
- For a given item, we need to suggest the price of that item given its different features like category, name, brand name, item description etc. The given problem is a Regression problem 
## Type of problem: Regression
- Error metric: RMSLE (Root Mean Square Logarithmic Error)
### Machine Learning Objective and Constraints
- Minimize RMSLE.
- Try to provide some interpretability.
### For more better understanding of this project:
- refer this blog which explains the entire case study in great depth: https://medium.com/analytics-vidhya/mercari-price-suggestion-challenge-a-machine-learning-regression-case-study-9d776d5293a0

credit: https://medium.com/analytics-vidhya/mercari-price-suggestion-challenge-a-machine-learning-regression-case-study-9d776d5293a0
