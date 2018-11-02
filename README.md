# Project 2 - Ames Housing Data and Kaggle Challenge

The purpose of this project was to create a regression model based on the Ames Housing Dataset in order to predict the selling price of a house.

There was also a [Kaggle Competition](https://www.kaggle.com/c/dsi-us-5-project-2-regression-challenge) where everyone taking the Data Science Immersive course at General Assembly could submit their predicted prices and compare scores.

Since this was the fourth week of the class, I was only familiar with linear regression models, as well as Ridge and Lasso regularization techniques. The biggest challenge with this project was determining which features to use, since the dataset had over 8 columns. I learned about how to create dummy variables, and interaction terms, as well as how to use cross validation to prevent overfitting.

In retrospect, the approach I took lacked finesse, and contained way to many features. I over-used dummy variables and polynomial terms, which ended up causing my feature count to explode. Looking back, I should have spent more time looking at the data before jumping into feature engineering.
