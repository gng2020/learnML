# Data Cleaning:
Here are my thoughts on the Kaggle Titanic dataset. 

# 1. Missing Data:

Firstly, I need to clean up the data: This involves filling in the missing data (or deleting them depending on the size of the data).

# 2. Redundant / Irrelevant Features:

Secondly, I need to perform cross-correlations among the features. I suspect things like Class and Ticket Fare contain the same info on the wealth of the individuals. Feature like where they embark could be irrelevant, or tied to their wealth or status. Similarly, their title (say like "Master" vs "Mr") might also be linked to their status. An appropriate analysis of these features to clean up and slim them down to a social class feature or something would be good.


# 3. Figure out which models to use:
From the top of my head, I would think SVM would be good to group the status classes. Upon doing so, then we could use the reduced data set to run through decision tree or random forest. 




### Misc: 
I found a good discussion of all of the above from an article by [Niklas Donges](https://towardsdatascience.com/predicting-the-survival-of-titanic-passengers-30870ccc7e8). I will follow many of his discussion but will try to implement them myself.
