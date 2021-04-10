# Credit_Risk_Analysis

## Overview of the Analysis:

The purpose of the Credit risk is to try, compare, and evaluate different machine learning models to predict credit risk. Our machine learning models are designed to reduce the inherent unbalanced classification problem since there is very low number of bad loans compared to good loans. Our team understands the significance of low probability/high consequence and therefore approached this problem in multiple methods and then evaluated and compared results.

## Results:

### The balanced accuracy scores and the precision and recall scores of all six machine learning models. 

Our team evaluated a total of six machine learning models. The results are shown below for each model.

- Naive Random Oversampling Model
  <img src="/Resources/NaiveRandomOverSampling.png" />

  - Balanced Accuracy score (Overall): 0.65
  - Precision (High Risk):             0.01
  - Sensitivity/Recall (High Risk):    0.63

- SMOTE Oversampling Model
  <img src="/Resources/SMOTEOverSampling.png"/> 

  - Balanced Accuracy score (Overall): 0.63
  - Precision (High Risk):             0.01
  - Sensitivity/Recall (High Risk):    0.60

- Undersampling Model
  <img src="/Resources/UnderSampling.png"/> 

  - Balanced Accuracy score (Overall): 0.52
  - Precision (High Risk):             0.01
  - Sensitivity/Recall (High Risk):    0.60

- Combination Oversampling and Undersampling Model
  <img src="/Resources/CombinationSampling.png"/> 

  - Balanced Accuracy score (Overall): 0.64
  - Precision (High Risk):             0.01
  - Sensitivity/Recall (High Risk):    0.69

- Balanced Random Forest Classifier Model
  <img src="/Resources/RandomForest.png"/> 

  - Balanced Accuracy score (Overall): 0.79
  - Precision (High Risk):             0.03
  - Sensitivity/Recall (High Risk):    0.70

- Easy Ensemble AdaBoost Classifier Model
  <img src="/Resources/EnsembleAdaBoost.png" /> 

  - Balanced Accuracy score (Overall): 0.93
  - Precision (High Risk):             0.09
  - Sensitivity/Recall (High Risk):    0.92

## Summary: 

Since our client has informed us that their primary concern is to to be able to identify bad loans, our team decided to report the results on precision and sensitivity/recall for the high risk loans. In addition, our primary target in the results above is to have higher sensitivty/recall of high risk loans which means higher identification of true bad loans.

Therfore, our team recommends using the Easy Ensemble AdaBoost Classifier model for our data since it had the highest recall (of High Risk loans) of 0.92 as well as the highest Precision (of High Risk Loans) of 0.09 and highest overall balanced accuracy score of 0.93.