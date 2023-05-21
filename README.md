# deep-learning-challenge

## Analysis Overview
Inthis 
## Results

* The target variable for this model was 'IS_SUCCESSFUL', a bianary variable dictating whether the applicant was successful or not in their venture.
* The features for the model are as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* The variables that were removed during the preprocessing of the data were 'EIN' and 'NAME'

* The final model consists of 7,381 parameters with five hidden layers, all with relu activation except for the output which was sigma.  Number of neurons for each layer is as follows:
      Layer 1 = 80
      Layer 2 = 30
      Layer 3 = 20
      Layer 4 = 10
      Layer 5 = 10
 * Multiple iterations were attempted for optimzation, the highest accuracy score attained was 0.73


## Summary

The final neural network model used 5 hidden layers, used relu activation, adam as its model optimizer, and had a total of 7,381 parameters.
Experimenting by removing columns, adding additional epochs from 100, or changing the model optimizer did not yield a dramatic difference from the accuracy score reported here of 0.73.
For increasing accuracy, other models such as decision-tree algorithms like Random Forest may be experimented with to see if accuracy increases.  Ultimately, more data used in training would produce an optimal model for 

