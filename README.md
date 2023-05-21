# deep-learning-challenge

## Analysis Overview
Inthis 
## Results

* The target variable for this model was 'IS_SUCCESSFUL', a bianary variable dictating whether the applicant was successful or not in their venture.
![Screenshot 2023-05-20 at 8 22 27 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/e6934eba-3a2d-4dd6-862e-992cbb2e1ecc)



* The features for the model are as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT






* The variables that were removed during the preprocessing of the data were 'EIN' and 'NAME'
* ![Screenshot 2023-05-20 at 8 24 35 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/53573d77-16ac-458f-96d2-e2c805cf2a4c)


* The final model consists of 7,381 parameters with five hidden layers, all with relu activation except for the output which was sigma.  Number of neurons for each layer is as follows:
      Layer 1 = 80
      Layer 2 = 30
      Layer 3 = 20
      Layer 4 = 10
      Layer 5 = 10
      
 ![Screenshot 2023-05-20 at 8 25 36 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/c50cf0da-06a7-44c7-a480-803821c22604)

 * Multiple iterations were attempted for optimzation, the highest accuracy score attained was 0.73




## Summary

The final neural network model used 5 hidden layers, used relu activation, adam as its model optimizer, and had a total of 7,381 parameters.
Experimenting by removing columns, adding additional epochs from 100, or changing the model optimizer did not yield a dramatic difference from the accuracy score reported here of 0.73.
For increasing accuracy, other models such as decision-tree algorithms like Random Forest may be experimented with to see if accuracy increases.  Ultimately, more data used in training would produce an optimal model for 

