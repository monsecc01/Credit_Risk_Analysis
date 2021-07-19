# Credit Risk Analysis 

## Resources

Data Source: [Loan Stats 2019 Q1](https://github.com/monsecc01/Credit_Risk_Analysis/blob/44a5453f2e05c9d584e759eba15b3a0a1a49089a/LoanStats_2019Q1.zip)

Software: Jupyter Notebook, Python, Anaconda Navigator

## Overview of the analysis: 

Explain the purpose of this analysis.

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

  ### RandomOverSampler Model
  * Balanced Accuracy Scores: Approximately 66%.
  * Precision Scores: High risk precision is only 1% with 63% sensitivity, which provides an F1 of 1%.
  * Recall Scores: Due to the high number of low risk, the sensitivity is 66%.

![image](https://user-images.githubusercontent.com/81447450/126101879-12abebbc-3d73-4c5d-9e54-47407c47a586.png)

  ### SMOTE Model

  * Balanced Accuracy Scores
  * Precision Scores
  * Recall Scores
 
 ![image](https://user-images.githubusercontent.com/81447450/126102401-922a3856-19ce-499a-9daa-2f1ed20b0cae.png)
 
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
