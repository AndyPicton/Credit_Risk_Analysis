# Credit_Risk_Analysis
## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally I evaluated the performance of these models and made a  recommendation on whether they should be used to predict credit risk.

## Results
### Native Random Oversampling
Balanced Accuracy Score: 0.6556
![image](https://user-images.githubusercontent.com/99369565/176977747-c3acd0e1-4957-4358-ad40-801535c50373.png)

### SMOTE Oversampling
Balanced Accuracy Score: 0.6642
![image](https://user-images.githubusercontent.com/99369565/176977808-c70473ad-a90a-477c-8ea8-59a1142804a3.png)

### Undersampling
Balanced Accuracy Score: 0.6642
![image](https://user-images.githubusercontent.com/99369565/176977849-230f71ac-f37e-45cc-83ad-1d8de75804b4.png)

### SMOTEENN
Balanced Accuracy Score: 0.5293
![image](https://user-images.githubusercontent.com/99369565/176977912-442e50c0-b5eb-43cf-a5ba-2a4b7b69070d.png)

### Balanced Random Forest Classifier
Balanced Accuracy Score: 0.7877
![image](https://user-images.githubusercontent.com/99369565/176977935-83e15bd4-7995-46b8-a64f-e935271e0d10.png)

### Easy Ensemble AdaBoost Classifier
Balanced Accuracy Score: 0.9254
![image](https://user-images.githubusercontent.com/99369565/176977949-b718df87-b1ed-4c3c-88b3-c57a6d6ba093.png)

## Summary
The Easy Ensemble AdaBoost Classifier returns the highest balanaced accuracy score so I can confidently recommend to use that model.
