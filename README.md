# deep-learning-challenge

## Analysis Overview
In this analysis, a neural network model was compiled, trained, and evaluated based off of data from charitable ventures.  The purpose of this analysis is to construct a model that may predict the likelihood that a venture will be successful, thus, such a model would benefeit the backer of such ventures in order to foresee if the investment into the venture is worthwhile.  Pertinent data were binned or encoded in order to compile, train, and eventually evaluate the efficacy of the model.

## Results

* The target variable for this model was 'IS_SUCCESSFUL', a bianary variable dictating whether the applicant was successful or not in their venture.
![Screenshot 2023-05-20 at 8 22 27 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/8f99c69b-f68c-4764-bca7-65f34bba0fa9)




* The features for the model are as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT





* The variables that were removed during the preprocessing of the data were 'EIN' and 'NAME'
![Screenshot 2023-05-20 at 8 24 35 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/def079ef-bbce-40ed-a939-b2c2520f50b0)



* The final model consists of 7,381 parameters with five hidden layers, all with relu activation except for the output which was sigma.  Number of neurons for each layer is as follows:
      Layer 1 = 80
      Layer 2 = 30
      Layer 3 = 20
      Layer 4 = 10
      Layer 5 = 10
      
 ![Screenshot 2023-05-20 at 8 25 36 PM](https://github.com/armannphd/deep-learning-challenge/assets/115322974/c50cf0da-06a7-44c7-a480-803821c22604)

 * Multiple iterations were attempted for optimzation, the highest accuracy score attained was 0.73




## Summary

The final neural network model used 5 hidden layers, used relu activation, adam as its model optimizer, and had a total of 7,381 parameters (named 'AlphabetSoupCharity_Optimization_attempt1.ipynb').

Experimenting by removing columns, adding additional epochs from 100, or changing the model optimizer did not yield a dramatic difference from the accuracy score reported here of 0.73.

* First attempt, 'AlphabetSoupCharity.ipynb', had 921 params, an 2 hidden layers
* Second attempt, 'AlphabetSoupCharity_attempt_1.ipynb', had 7381 params, and 5 hidden layers
* Third attempt, 'AlphabetSoupCharity_attempt_2.ipynb' changed its model optimizer from adam to adadelta
* Fourth attempt, 'AlphabetSoupCharity_attempt_3.ipynb' increased the number of neurons for a total of 18501 parameters
* Fifth attempt, 'AlphabetSoupCharity_attempt_4.ipynb' is based on 'AlphabetSoupCharity_attempt_3.ipynb' but deleted select columns
      
For increasing accuracy, other models such as decision-tree algorithms like Random Forest may be experimented with to see if accuracy increases.  Ultimately, more data used in training would produce an optimal model for 

