# Class Thirteen

[Home](https://daviey52.github.io/reading-notes/)

## How to run linear regression in python

Scikit-learn is a powerful python model for machine learning. It has functions for regression, classification , clustering, dimensionality reduction and model selection.

First step when running linear regression in python is to import needed libraries

Target() method is used to add data to an already existing data frame.
Drop(). Method removes rows or column by specifying label name and corresponding axis, or by specifying directly index or column name.

Some of the critical functions when fitting a linear regression model are
IM.fit() – used to fit a linear model
Im.predict() – used to predict Y using the linear model with estimated coefficients
Im.score – returns the coefficient of determination (R^2) A measure of how well observed outcome are replicated by the model, as the proportion of total variations of outcomes explained by the model.

.coef_gives the coefficients and .intercept_gives the estimated intercept.

In practice linear regression is not done on entire data set, the data is split into training and test data sets, so that you can train a model on training data and see how well it performed on test data.

Residual plot are a good way of visualizing errors in a data set. If the analysis displays a randomly scattered pattern around zero, then the analysis was good.
