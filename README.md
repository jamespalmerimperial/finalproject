# final project

In this project I create a model to predict the price a house sells at from data about that house.
The model I used is the random forest regressor. Random forests can predict with high accuracy
but they are not interpretable.
In order to get the best predictive performance out of the random forest regressor I tuned the 
hyper parameters of the random forest regressor using bayesian optimisation.
After tuning the hyper parameters and training and validating the model with cross-validation,
the final model was tested on unseen house data and found to be able to predict  the house sale price with an R^2 of 0.85
, meaning that 85% of the variation in house prices can be explained by the model. 
