# Credit_Risk_Analysis
Module 17: Supervised Machine Learning and Credit Risk
## Project Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

## Resources
[.csv](https from github)

## Results
Six machine learning models to describe the balanced accuracy scores and the precision and recall scores 

### RandomOverSampler

![image name](https from github)

- High Risk: Precision = 0.01, Recall = 0.72
- Low Risk: Precision = 1.00, Recall = 0.56

### SMOTE algorithms

![image name](https from github)

- High Risk: Precision = 0.01, Recall = 0.62
- Low Risk: Precision = 1.00, Recall = 0.69

### ClusterCentroids algorithm

![image name](https from github)

- High Risk: Precision = 0.01, Recall = 0.69
- Low Risk: Precision = 1.00, Recall = 0.40 

### SMOTEENN algrithm

![image name](https from github)

- High Risk: Precision = 0.01, Recall = 0.72
- Low Risk: Precision = 1.00, Recall = 0.58

### BalancedRandomForestClassifier

![image name](https from github)

- High Risk: Precision = 0.04, Recall = 0.67
- Low Risk: Precision = 1.00, Recall = 0.91

### EasyEnsembleClassifier

![image name](https from github)

- High Risk: Precision = 0.07, Recall = 0.91
- Low Risk: Precision = 1.00, Recall = 0.94

## Summary
- Analysis shows all models used show a feeble precision in determining a high credit risk. 
- Ensemble Classifier shows improvment of the sensitivity in high credit risk, however, the low credit risks falsely detected compared to the high credit risk.  
- Based on my analysis summary I would not recommend any of these models. 

