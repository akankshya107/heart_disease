# Heart Disease
Prediction on DrivenData dataset

Predict the binary class heart_disease_present, which represents whether or not a patient has heart disease.

Performance is evaluated according to binary log loss.
Testing scores on following models:
- 10 fold Random Forest/Naive Bayes : 0.44747
- AdaBoost with 21 trees : 0.64510
- Naive Bayes without crossfold : 0.56218
- Logistic Regression with normalized data : 0.40607
- Random Forest with normalized data : 0.46153
- 10 fold Naive Bayes with normalized data : 0.52082
- Naive Bayes with normalized data : 0.56438
- 10 fold Logistic Regression with normalized data : 0.37903
- 4 fold Logistic Regression with normalized data : 0.38350 
- 5 fold Naive Bayes : 0.60231
- 10 fold neural network with normalized data : 0.57658
- Neural network with all the training data with normalized data : 0.43043
- Log reg with all the training data with normalized data : 0.38417
