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
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/smote_oversampling_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.65** meaning 65% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/smote_oversampling_classification_report.png)
- The precision score of this model for high risk loans was **0.01** meaning that there is a 1% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.64** meaning that this model will predict a high risk loan correctly 64% of the time.
- - The recall score of this model for low risk loans is **0.66** meaning that this model will predict a low risk loan correctly 66% of the time.

### ClusterCentroids Undersampling:
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/clustercentroids_undersampling_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.53** meaning 53% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/clustercentroids_undersampling_classification_report.png)
- The precision score of this model for high risk loans was **0.01** meaning that there is a 1% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.61** meaning that this model will predict a high risk loan correctly 61% of the time.
- - The recall score of this model for low risk loans is **0.45** meaning that this model will predict a low risk loan correctly 45% of the time.

### SMOTEENN Combination Sampling:
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/smoteenn_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.64** meaning 64% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/smoteenn_classification_report.png)
- The precision score of this model for high risk loans was **0.01** meaning that there is a 1% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.70** meaning that this model will predict a high risk loan correctly 70% of the time.
- - The recall score of this model for low risk loans is **0.57** meaning that this model will predict a low risk loan correctly 57% of the time.

### Balanced Random Forest Classifier:
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/balanced_random_forest_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.81** meaning 81% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/balanced_random_forest_classification_report.png)
- The precision score of this model for high risk loans was **0.03** meaning that there is a 3% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.72** meaning that this model will predict a high risk loan correctly 72% of the time.
- - The recall score of this model for low risk loans is **0.89** meaning that this model will predict a low risk loan correctly 89% of the time.

### Easy Ensemble AdaBoost Classifier:
#### Balanced Accuracy Score:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/easy_ensemble_adaboost_balanced_accuracy_score.png)
- The balanced accuracy score of this model was about **0.93** meaning 93% of the predicted credit risk outputs were predicted correctly.

#### Precision and Recall:
![Credit_Risk](https://github.com/mbroad1/Module-17-Credit-Risk-Analysis/blob/main/easy_ensemble_adaboost_classification_report.png)
- The precision score of this model for high risk loans was **0.07** meaning that there is a 7% probability that this predicted high risk loan is actually a high risk loan.
- The precision score of this model for low risk loans was **1.00** meaning that there is a 100% probability that this predicted low risk loan is actually a low risk loan.
- The recall score of this model for high risk loans is **0.91** meaning that this model will predict a high risk loan correctly 91% of the time.
- - The recall score of this model for low risk loans is **0.94** meaning that this model will predict a low risk loan correctly 94% of the time.
---
## Summary:
- Out of all the machine learning models, the model with the best balanced accuracy score, precision scores, and recall scores was the Easy Ensemble AdaBoost Classifier with an accuracy score of around **0.93**, a precision of **0.07** for high risk loans, a precision of **1.00** for low risk loans, a recall of **0.91** for high risk loans, and a recall of **0.94** for low risk loans.
- The worst performing machine learning model was the ClusterCentroids Undersampling model with an accuracy score of **0.53**, a precision of **0.01** for high risk loans, a precision of **1.00** for low risk loans, a recall of **0.61** for high risk loans, and a recall of **0.45** for low risk loans.
- Therefore, the best model to assess credit risk is the Easy Ensemble Adaboost Classifier because it has the highest of any score of all the models meaning it is very accurate in predicting both low risk and high risk loans, and thus will be extremely useful in assessing credit risk.
