# Credit_Risk_Analysis
UCB Challenge: Use skills in data preparation, statistical reasoning, and machine learning snd apply this in evaluating credit card risk while using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
 
# Overview of the Analysis 
With the dataset given to us from Lending Club, a peer-to-peer lending services company, we were given the task to evaluate credit card risk. We utilized six different algorithms in our methodology for sampling the data. We oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We also used the BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

Finally, we need to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


# Results
For each model or algorithm, its corresponding Balanced Accuracy Score, Confusion Matrix and Classification Report is presented, along with a brief summary of what is contained in the three reports. The values in the summary are expressed in percentages, having 2 significant figures when possible and no decimals.

## Naive Random Oversampling Algorithm
![Naive_Random_Oversampling_Algorithm](resources/NROA.png)
* The balanced accuracy score for this algorithm is 64%.
* The precision score for the high-risk category is 1%, recall score is 66% and an F1 score of 2%  
* The precision score is at 100%, recall score is at 62% and an F1 score of 76% for the low-risk category.

## SMOTE Oversampling Algorithm
![SMOTE_Oversampling_Algorithm](resources/SMOTE.png)
* The balanced accuracy score is 65%.
* The precision score for the high risk category is 1%, recall score is 61% and an F1 score of 2%.
* The precision score is at 100%, recall score is at 69% and an F1 score of 81% for the low-risk category.


## Cluster Centroids Algorithm
![Cluster_Centroids_Algorithm](resources/CCA.png)
* The balance accuracy score is 54%.
* The precision score for the high risk category is 1%, recall score is 69% and an F1 score of 1%.
* The precision score is at 100%, recall score is at 40% and an F1 score of 57% for the low-risk category.

## SMOTEENN Algorithm
![SMOTEENN_Algorithm](resources/SMOTEENN.png)
* The balance accuracy score is 66%.
* The precision score for the high risk category is 1%, recall score is 75% and an F1 score of 2%.
* The precision score is at 100%, recall score is at 56% and an F1 score of 72% for the low-risk category.

## BalancedRandomForestClassifier
![BalancedRandomForestClassifie](resources/BRFC.png)
* The balanced accuracy score is 79%
* The precision score for the high risk category is 3%, recall score is 70% and an F1 score of 6%.
* The precision score is at 100%, recall score is at 87% and an F1 score of 93% for the low-risk category.

## EasyEnsembleClassifier
![EasyEnsembleClassifier](resources/EEC.png)
* The balanced accuracy score is 93%
* The precision score for the high risk category is 9%, recall score is 92% and an F1 score of 16%.
* The precision score is at 100%, recall score is at 94% and an F1 score of 97% for the low-risk category.



# Summary
