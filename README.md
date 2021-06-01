# Module 17 Challenge: Credit Risk Analysis

## Purpose:
The purpose of this analysis is to evaluate different supervised machine learning models to see which one is the best in predicting credit risk from loan applications. For this analysis, I will be using Python and the Scikit-Learn library to create machine learning models and task them with assessing credit risk data.
---

## Results:

### Naive Random Oversampling:
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/random_oversampling_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.65** meaning 65% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/random_oversampling_classification_report.png)
- The precision score of this model for high risk loans was **0.01** meaning that there is a 1% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.63** meaning that this model will predict a high risk loan correctly 63% of the time.
- - The recall score of this model for low risk loans is **0.67** meaning that this model will predict a low risk loan correctly 67% of the time.

### SMOTE Oversampling:

### ClusterCentroids Undersampling:

### SMOTEENN Combination Sampling:

### Balanced Random Forest Classifier:

### Easy Ensemble AdaBoost Classifier:
