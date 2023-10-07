# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** 
vector of numbers representing data of house that has been sold at an input date

**Output:** 
prediction of price at sale of the house 

**Model Architecture:** 
Random Forest regressor with hyper parameters tuned by bayesian optimisation

## Performance

R^2 tested on unseen data of 0.85, the model was tested on 216 unseen pieces of data from the dataset.

## Limitations

This model is limited to predicting house prices of houses sold in cook county washington between 2014-2015. the further outside that time window and further from that geographic location, the less well the model will perform although the model might perform quite well for cases that are vaguely close.

## Trade-offs

Strong predictive power was achieved with a model that managed to account for 85% of the variance, however  the trade-off is that the model is not interpretable so it can't be used to infer what might cause differences in house sale price 
