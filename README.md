# Credit Risk Analysis

## Overview of Credit Risk Analysis

Fast Lending, a peer-to-peer lending company, wants to use machine learning to predict credit risk.  Management believes that this will provide a faster, more streamlined loan experience.  It is also thought that machine learning will lead to a more accurate identification of good candidates for loans and result in lower default rates.

Fast Lending wants me to assist the lead machine learning analyst to develop six machine learning models to predict credit risk.  We will use techniques such as sampling and boosting to make the most of our models and accomplish our task.  

### Resources

* Resources:  LoadStats2019.csv
* Software:  Python, imblearn, sci-kit learn, Visual Studio Code, 1.38.1

## Credit Risk Analysis Machine Learning Results

## Machine Learning Model #1:  Niave Random Oversampling

![m1.png](Resources/m1.png)

*  Balanced Accuracy Score:  0.6337390365455198
*  Precision and Recall Score:  0.99 and 0.68

## Machine Learning Model #2:  SMOTE Oversampling

![m2.png](Resources/m2.png)

*  Balanced Accuracy Score:  0.6285619895975602

*  Precision and Recall Score:  0.99 and 0.66

## Machine Learning Model #3:  Undersampling

![m3.png](Resources/m3.png)

*  Balanced Accuracy Score:  0.6285619895975602

*  Precision and Recall Score:  0.99 and 0.44

## Machine Learning Model #4:  Combination Over and Under Sampling

![m4.png](Resources/m4.png)

*  Balanced Accuracy Score:  0.5110319445955256

*  Precision and Recall Score:  0.99 and 0.57

## Machine Learning Model #5:  Balanced Random Forest Classifier

![m5.png](Resources/m5.png)

*  Balanced Accuracy Score:  0.7877672625306695

*  Precision and Recall Score:  0.99 and 0.91

## Machine Learning Model #6:  Easy Ensemble AdaBoost Classifier

![m6.png](Resources/m6.png)

*  Balanced Accuracy Score:  0.925427358175101

*  Precision and Recall Score:  0.99 and 0.94

## Summary of Credit Risk Analysis

The Easy Ensemby AdaBoost Classifier model performed the best of the six models.  We can make this determination based on comparing each model's balanced accuracy score, where higher scores are considered better.
