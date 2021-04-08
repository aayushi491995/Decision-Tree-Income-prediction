# Decision-Tree-Income-prediction

### Objective

Predict income for individuals that whether the salary is greater than or equal to 50K or less than 50K.

### Contents
This project is meant to explore, analyse, visualize and predict the salary of an individual:    
     1   workclass       
     2   fnlwgt          
     3   education       
     4   education.num   
     5   marital.status  
     6   occupation      
     7   relationship   
     8   race            
     9   sex           - gender of the individual   
     10  capital.gain    
     11  capital.loss    
     12  hours.per.week  - how many hours an individual spend working weekly
     13  native.country  -  country where the individual belong to 
     14  Age - age of the individual
     15  income - Whether the income is >=50K or <50K

Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataset
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values but there are no null and unwanted values present in the dataset.
    4. Train Test Split
    5. Perform Decision Tree Classifier algorithm on Train data 
         - We performed Decision Tree Classifier on the system and the values to predict are binary in nature i.e., a person can either be have salary >=50K or <50K.
    6. Prediction of Train data
         - We got the accuracy of  - 0.78 for Train data 
    7. Prediction of Test data </ul>
         - We got the Test accuracy of - 0.75, Hence the model is neither underfiting not over fitting.


