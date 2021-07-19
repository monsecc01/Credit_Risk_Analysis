# Credit Risk Analysis 

## Resources

Data Source: [Loan Stats 2019 Q1](https://github.com/monsecc01/Credit_Risk_Analysis/blob/44a5453f2e05c9d584e759eba15b3a0a1a49089a/LoanStats_2019Q1.zip)

Software: Jupyter Notebook, Python, Anaconda Navigator

## Overview of the analysis: 

The purpose of the Credit Risk analysis is to analyze a credit card credit dataset from LendingClub, a peer-to-peer lending services company, and use 6 different algorythms to predict credit risk. We will evaluate the results from the 6 machine learning algorythm models and decide which, if any, best predicts credit risk.

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

  ### RandomOverSampler Model
  * Balanced Accuracy Scores: Approximately 66%.
  * Precision Scores: High risk precision is only 1% with 63% sensitivity, which provides an F1 of 1%.
  * Recall Scores: Due to the high number of low risk, the sensitivity is 66%.

  <img width="758" alt="randomoversampling" src="https://user-images.githubusercontent.com/81447450/126103092-d1c70656-fca2-4dbd-8d56-f5b57b63e480.png">

  ### SMOTE Model

  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores
 
  <img width="754" alt="SMOTE" src="https://user-images.githubusercontent.com/81447450/126103122-90631e0b-7c81-481a-9c02-dc618adce8f6.png">
 
  ### ClusterCentroids

  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores
 
  <img width="755" alt="cluster centroids" src="https://user-images.githubusercontent.com/81447450/126102768-a2080ad8-3468-497d-93da-723b9719f623.png">
 
  ### SMOTEENN
  
  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores
  
  <img width="752" alt="SMOTEENN" src="https://user-images.githubusercontent.com/81447450/126102780-d97b2140-3df2-4ddc-9b9f-7fa66e96a175.png">
  
  ### BalancedRandomForestClassifier

  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores

  <img width="761" alt="rfc" src="https://user-images.githubusercontent.com/81447450/126102901-7b983499-a6c8-4f72-bdaa-3994cffe7625.png">

  ### EasyEnsembleClassifier

  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores
  
  <img width="751" alt="EEC" src="https://user-images.githubusercontent.com/81447450/126102928-3ab7396c-2435-4a08-8ba1-d5caf3253a15.png">

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
