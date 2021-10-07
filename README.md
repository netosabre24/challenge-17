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

![SMOTE2](https://user-images.githubusercontent.com/82550431/136347736-908b3fa2-72fe-4ebe-9459-210e52cae706.PNG)
