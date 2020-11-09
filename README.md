# Credit_Risk_Analysis

## Overview of the analysis: 
In this project, we are working with LendingClub, a peer-to-peer lending services company.  LendingClub wants to use Machine Learning to predict credit risk with the hopes that it will result in a quicker and more reliable loan experience.  Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. For this analysis we employed different techniques to train and evaluate models with unbalanced classes. This analysis uses imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.  We oversampled the data using the Random Over Sampler and SMOTE algorithms, and undersampled the data using the Cluster Centroids algorithms.  We also used a combinatorial approach of over and under sampling using the SMOTEENN algorithm.  

## Results: 
We found the following results from our different testings.

### Balanced Random Forest Classifier
- Accuracy Score (r squared) = 0.79
- Precision = 0.99
- Recall = 0.87

<img src = "https://github.com/jennfrbrown/Credit_Risk_Analysis/blob/main/ReadMe%20Images/Balance%20Random%20Forest%20Classifier.png">

### Naive Random Oversampling
- Accuracy Score:0.63
- Precision: 0.99
- Recall:0.68

<img src = "https://github.com/jennfrbrown/Credit_Risk_Analysis/blob/main/ReadMe%20Images/Naive%20Random%20Oversampling.png">

### SMOTE Oversampling
- Accuracy Score: 0.65
- Precision:  0.99
- Recall: 0.63

<img src = "https://github.com/jennfrbrown/Credit_Risk_Analysis/blob/main/ReadMe%20Images/SMOTE.png">

### Cluser Centroids Undersampling and Logistic Regression
- Accuracy Score: 0.51
- Precision: 0.99
- Recall: 0.41
<img src = "https://github.com/jennfrbrown/Credit_Risk_Analysis/blob/main/ReadMe%20Images/Cluster.png">

### SMOTEENN
- Accuracy Score: 0.51
- Precision: 0.99
- Recall: 0.60
<img src = "https://github.com/jennfrbrown/Credit_Risk_Analysis/blob/main/ReadMe%20Images/SMOTEENN.png">

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
