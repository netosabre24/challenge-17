# Credit Risk analysis

# Overview
The purpose of this data analysis is to build multiple supervised machine learning algorithms that will predict cases of fraud for credit transactions. This will aid loan companies predict high risk transactions.

# Software
* Python
* sklearn Libarary
* imblearn Libary

# Analysis and results

# Random Sampling
![RandomOversampling](https://user-images.githubusercontent.com/82550431/136346435-e2ba7d25-66a9-4124-994e-670bab6f8fde.PNG)

![RandomOversampling2](https://user-images.githubusercontent.com/82550431/136346449-ab3f768b-5ffd-4813-a428-8c5468e091ba.PNG)

The accuracy for random Oversampling is 64.6%. The precision for high risk loans is very small at 1%, and the recall value at only 57% giving an f1 score of only 1%. Low risk loans however have higher precision and recall at 100% and 55%, giving a 71% f1 score. Which is most likely due to imbalance of the data set with low risk loans.

# SMOTE

![SMOTE](https://user-images.githubusercontent.com/82550431/136347788-29e96dcf-31d6-47bf-9d00-853ca9a2e97a.PNG)

![SMOTE2](https://user-images.githubusercontent.com/82550431/136347736-908b3fa2-72fe-4ebe-9459-210e52cae706.PNG)

The accuracy for the SMOTE Model is slightly better than the previous, at 66%. The precision for both high & low risk, as well as the recall for low risk remain almost exactly the same as before (1%, 100%, 69%). The recall value for high risk loans is slightly higher at 65% and the f1 scores remain about the same value.

# Random Forest

![randomforest](https://user-images.githubusercontent.com/82550431/136349534-b5ba3e15-8785-492a-af7f-f0e09f16312a.PNG)

![randomforest2](https://user-images.githubusercontent.com/82550431/136349563-5f9a42f2-2b9f-46b9-99e7-a27bbce0b60a.PNG)

Random forest has shown some interesting results, with a accuracy of 3%. The precision, recall and f1 of low risk loans varied between 70%-90%. The f1 score low was 7%.

# Ensemble

![Ensemble](https://user-images.githubusercontent.com/82550431/136351338-cf9d4106-2cb2-4e09-a43d-12616d6cc30f.PNG)

![Ensemble2](https://user-images.githubusercontent.com/82550431/136351386-0694ba39-5546-458e-865b-1b0b6b7ef1e9.PNG)

Ensemble outperformed all the otrher alogrithms by far, with an accuracy of 93%. Although the precision for detecting high risk loans is very low at 9%.

# Summary
Overall, all the models used here were relatively weak at predicting credit risk. The ensemble model gave us the best accuracy and very high recall value, which would allow us to detect most high risk loans. Unfortunately, the precision for the ensemble model is still extremely low, which would falsely tag many low risk loans. To conclude the overview, I dont recommend using a specific model in their current state.
