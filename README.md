# Credit_Risk_Analysis

## Analysis Overview 
Tasked with running our credit card data through a few different sencarios, we oversampled the data (RandomOverSampler & SMOTE used) and undersampled the data (ClusterCentroids used). We then moved to a combination of both (over and under sampling) with the use of SMOTEENN alogrithm. For the final piece of the our work we wanted to predict risk using BalancedRandomForestClassifer and EasyEnsembleClassifer machine learning models used to reduce bias.  

## Results of Analysis

### Reveiw of the Balanced Accuracy, Precision, and Recall Scores for each manchine learning model used. 
- RandomOverSampler

![](images/ramdomoversampler_accuracy.PNG)

![](images/ramdomoversampler_precision_accuracy.PNG)

- SMOTE

![](images/smote_accuracy.PNG)

![](images/smote_precision_accuracy.PNG)

- ClusterCentroids

![](images/ClusterCentroids_accuracy.PNG)

![](images/ClusterCentroids_precision_accuracy.PNG)

- SMOTEENN

![](images/SMOTEEN_accuracy.PNG)

![](images/SMOTEEN_precision_accuracy.PNG)

- BalancedRandomForestClassifer

![](images/BalancedRandomForestClassifer_accuracy.PNG)

![](images/BalancedRandomForestClassifer_precision_accuracy.PNG)

- EasyEnsembleClassifer

![](images/EasyEnsemlbeClassifer_accuracy.PNG)

![](images/EasyEnsembleclassifer_precision_accuracy.PNG)
