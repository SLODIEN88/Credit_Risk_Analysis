# Credit_Risk_Analysis
Machine learning
## Overview of the analysis: 
The purpose of this analysis was to employ different techniques to train and evaluate models with unbalanced classes. I sued imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. I used the credit card data set from lending club, LoanStats_2019.csv to help determine the different algorithms

## Results: 
I used Python to determine the results. Six machine learning models were used to build an evaluate to determine which provided whether a loan defaulted or not.
### Naive Random Oversampling
The balanced accuracy score is 66%. The recall for a high risk loan is 32% and precison being 72%

![image](https://user-images.githubusercontent.com/96274446/166161601-10f0b383-5049-43c2-bbb6-1847592f327c.png)
![image](https://user-images.githubusercontent.com/96274446/166162126-45ca4203-3139-4118-8bca-54a7e0ee17e6.png)


### SMOTE Oversampling
The balanced accuracy score is 62%. The recall for a high risk loan is 62% and precison being 1%
![image](https://user-images.githubusercontent.com/96274446/166161609-888bd060-f913-4565-9937-59f7de41cb92.png)

### Undersampling
The balanced accuracy score is 64%. The recall for a high risk loan is 61% and precison being 1%
![image](https://user-images.githubusercontent.com/96274446/166161652-9b07a93c-46ac-41a0-ad71-f192c633e2d9.png)

### Combination (Over and Under) Sampling
The balanced accuracy score is 59%. The recall for a high risk loan is 61% and precison being 1%
![image](https://user-images.githubusercontent.com/96274446/166161660-30644c03-5ec5-4a1e-9a6e-930083cd99ab.png)

### Balanced Random Forest Classifier
The balanced accuracy score is 66%. The recall for a high risk loan is 32% and precison being 72%
![image](https://user-images.githubusercontent.com/96274446/166161708-637070fd-52d6-4d31-abb9-43acb5e87822.png)

### Easy Ensemble AdaBoost Classifier
The balanced accuracy score is 92%. The recall for a high risk loan is 91% and precison being 7%
![image](https://user-images.githubusercontent.com/96274446/166161729-0b40ac78-f9d4-4f20-bd75-c3904a51ff1a.png)

## Summary: 
In the first four models we undersampled, oversampled and also did a combination of both to try and determine which model is best at predicting which loans are the highest risk. In the 1st modules, the balanced accuracy scores were not as high. It is better to look for a module that is balanced and won't produce a high risk. I would recommend the Easy Ensemble AdaBoost Classifier because for high risk loans, it provided an accuracy rate of 92%, and a precison of 7%. This would be ideal for the high risk loans. But if they are looking for one that helps the low risk loans, then an entirely new model needs to be used. 

