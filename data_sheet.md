# Datasheet: House Sales in King County, USA

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

The data comes from official public records of home sales in the King County area, Washington State collected by the government. 
I was not able to find the official reason why home sales data was recorded in public records by the government.

 
## Composition
The instances that comprise the dataset represent the price that a house in King County was sold for between may 2014 and may 2015 and information about that house. There are 21613 instances of these sold houses. There is no missing data. There is no confidential data.


## Collection process

The data are public records available from the King County government website. I assume that King County  has a policy that houses sold must record their sale data. The data is subset of the King county sale data available from other years. The sampling strategy was to choose a year which interested the person who originally created the csv file. The data was collected from may 2014-may 2015.

## Preprocessing/cleaning/labelling

To pre-process the data, the date string was converted into number of days since 01.01.2001  and any other strings of numbers in the table were converted into numbers.  The raw data was included and the cleaning was performed within the analysis carried out in the jupyter notebook.

## Uses

The dataset could also be used to develop explanatory models for what effect different house data has on sales price, and used for exploratory data analysis about the characteristics of houses in the king county area and what house features are associated with other house features.  I can not foresee any harm that could be caused by this dataset  since houses are practically unidentifiable and can't be used to harm any groups or individuals. Like any dataset, this dataset should not be used to extrapolate to datasets that are drawn from a different, not-similar distribution. 


## Distribution

The dataset has been distributed on kaggle at https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data the license of the dataset is CC0: Public Domain.

## Maintenance

Nobody maintains the dataset

