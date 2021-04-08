# Decision-Tree-Income-prediction

### Objective

Predict income for individuals that whether the salary is greater than or equal to 50K or less than 50K.

### Contents
This project is meant to explore, analyse, visualize and predict the salary of an individeual:    
     1   workclass       32561 non-null  object
     2   fnlwgt          32561 non-null  int64 
     3   education       32561 non-null  object
     4   education.num   32561 non-null  int64 
     5   marital.status  32561 non-null  object
     6   occupation      32561 non-null  object
     7   relationship    32561 non-null  object
     8   race            32561 non-null  object
     9   sex             32561 non-null  object
     10  capital.gain    32561 non-null  int64 
     11  capital.loss    32561 non-null  int64 
     12  hours.per.week  32561 non-null  int64 
     13  native.country  32561 non-null  object
     14  Age
     15  income

Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataser
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values but there are no null and unwanted values present in the dataset.
    4. Train Test Split
    5. Perform Logistic Regression  on Train data 
         - We can perform logistic Regression on the system as the values to predict are binary in nature i.e., a person can either be                  diabetic or not.
    6. Prediction of Train data
         - We got the accuracy of  - 0.78 for Train data 
    7. Prediction of Test data </ul>
         - We got the Test accuracy of - 0.75, Hence the model is neither underfiting not over fitting.


