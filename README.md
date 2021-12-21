# Credit_Risk_Analysis

## Overview of the analysis
Using Lending Club’s credit card credit dataset, we apply multiple machine learning techniques to analysis and predict credit risk.
With Python, imbalanced-learn, and Scikit-learn library the follow six models will be created.
1) Naive Random Oversampling
2) SMOTE Oversampling
3) Undersampling
4) Combination (Over and Under) Sampling
5) Balanced Random Forest Classifier
6) Easy Ensemble AdaBoost Classifier

Afterword we will assess the accuracy score, confusion matrix report, and classification report of each model and compare their strengths and weaknesses to see how well the model predicts the data. 


## Results - Balanced Accuracy, Precision, and Recall Scores
### Resampling Models
#### Oversampling - Naive Random 
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/Naive_Random_Oversampling.PNG)
Balanced Accuracy: 0.64\
Precision Score: 0.01\
Recall Score: 0.62\
F1 Score: 0.02

#### Oversampling - SMOTE 
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/SMOTE_Oversampling.PNG)
Balanced Accuracy: 0.65\
Precision Score: 0.01\
Recall Score: 0.66\
F1 Score: 0.02

#### Undersampling
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/Undersampling.PNG)
Balanced Accuracy: 0.51\
Precision Score: 0.01\
Recall Score: 0.57\
F1 Score: 0.01

#### Combination (Over and Under) Sampling
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/Combination_Over_and_Under_Sampling.PNG)
Balanced Accuracy: 0.64\
Precision Score: 0.01\
Recall Score: 0.69\
F1 Score: 0.02

### Ensemble Learning Models
#### Balanced Random Forest Classifier
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/Balanced_random_Forest_Classifier.PNG)
Balanced Accuracy: 0.66\
Precision Score: 0.72\
Recall Score: 0.32\
F1 Score: 0.44

#### Easy Ensemble AdaBoost Classifier
![alt_text](https://github.com/kwporras/Credit_Risk_Analysis/blob/4155fbd31eb204bca97436e9f33f59b5dc120f7e/Resources/Easy_Ensemble_AdaBoost_Classifier.PNG)
Balanced Accuracy: 0.93\
Precision Score: 0.08\
Recall Score: 0.91\
F1 Score: 0.14

## Summary
The Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier would be the two models to consider. The Precision and F1 score are higher in the Balanced Random Forest Classifier but the Easy Ensemble AdaBoost Classifier has a higher Balanced Accuracy and Recall Score. Considering the F1 score, the normally the Balanced Random Forest Classifier would be chosen, however the accuracy score is very poor at 0.66. This make the Easy Ensemble AdaBoost Classifier the most ideal model to use. That said, since the F1 score is so low I would not recommend any of the models to make a prediction.
