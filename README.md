# final project : predicting house prices in King county using random forests tuned with bayesian optimisation

## NON-TECHNICAL EXPLANATION :
In this project I create a model to predict the price a house sells at from data about that house.
I use a model called a random forest regressor which can produce accurate predictions but is very hard to interpret why it makes those predictions.
To get the best performance out of the model, I tune it's hyper parameters using bayesian optimisation. 
The final model had an R^2 value of 85%, so was able to explain 85% of the variance in house prices. 

## DATA
The data I'm using is the House Sales in King County dataset 
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

## MODEL 
A random forest  works by constructing a number of decision trees then taking the average output of those decision trees as the prediction. 
I chose this model because it is known for being able to perform well at prediction tasks and because  I am not concerned with an interpretable model,
as random forests are very hard to interpret.

## HYPERPARAMETER OPTIMSATION
the hyperparameters of the random forest which I optimised are: the maximum depth of the trees , the minimum training samples required to be a leaf node on the trees, 
the maximum number of features to consider when looking for the best split on a tree,  whether bootstrap samples are used when constructing trees, and the minimum decrease in impurity sufficient to split a node in a tree.
I chose to optimise them using a bayesian optimisation library called HEBO

## RESULTS
Using bayesian optimisation to search for the best hyper parameters, the R^2 performance of the random forest regressor increased from 0.3 on the training set up to 0.85 on the final unseen test set!


## contact details
contact details to follow

