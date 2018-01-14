# Ames house prices kaggle competition

This is data analysis prepared for Kaggle [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques#) competition analysing and predicting prices of residential homes in [Ames, Iowa](https://en.wikipedia.org/wiki/Ames,_Iowa).

## Framing the problem

This competition objective is to predict the sales price of each home base on the set of features values. For Id in the test set, we must predict the value of the `SalePrice` variable.

This is clearly supervised learning problem since we are dealing with labeled training data. And because we try to predict variable value based on other set of feature it is clearly a regression problem.

The proposed solution will be evaluated on Root-Mean-Squared-Error (RMSE) the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

The final submission should have the following format:

`Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.`
