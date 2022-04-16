# Credit_Risk_Analysis

## Overview of Project
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Three machine learning models were analysed by using resampling to determine which is better at predicting credit risk. THe three learning models included: Oversampling RandomOverSampler and SMOTE algorithms, and then the undersampling ClusterCentroids algorithm. Using these algorithms, the dataset was resampled, a count was taken of the target classes. From this point we train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.Three technical analysis deliverables are:

* Deliverable 1: Use Resampling Models to Predict Credit Risk
* Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

## Deliverables

### Naive Random Sampling

<img width="344" alt="image" src="https://user-images.githubusercontent.com/95591222/163688283-94ed36e9-d83f-4023-9ea5-f4f9a5150310.png">

### Somote Oversampling

<img width="338" alt="image" src="https://user-images.githubusercontent.com/95591222/163688319-81879a07-d76d-44d9-92b5-d9f05cf52b6b.png">

### Undersampling

<img width="332" alt="image" src="https://user-images.githubusercontent.com/95591222/163688376-e5097d31-9250-4684-96e6-2a9fca77ca65.png">


### Combination Sampling

<img width="349" alt="image" src="https://user-images.githubusercontent.com/95591222/163688390-e46df2ec-af25-4382-b16a-3ada4c22500a.png">

### Balanced Random Forest

<img width="352" alt="image" src="https://user-images.githubusercontent.com/95591222/163688411-11b582cb-add3-48e8-ad1b-85b3882c3a5e.png">

### Easy Emsemble Adabooster

<img width="362" alt="image" src="https://user-images.githubusercontent.com/95591222/163688425-eca2af3b-ea6b-400a-b727-bcf7e883d4da.png">


## Deliverable 4: Conclusion

* Among the resampling models, the combination (SMOTEENN) model has the highest balanced accuracy score (67%) which is only a few points higher than the other models. For these resampling models the high risk and low risk predictions were 1% and 100% respectively.

* The Balanced Random Forest Classifier has a balanced accuracy score of 78.9% while Easy Ensemble AdaBoost shows 93.2%. While both models predict low risk 100% of the time.

* The Easy Ensemble predicts 9%, the highest out of all models making it the best option among the choices to predict credit risk.



