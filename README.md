# Credit_Risk_Analysis

## Overview of the analysis:
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## What Its being Created
This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis

## Resources
- Software: Git version 2.33.0.windows.2, Visual Studio 1.62.2, Jupiter Notebook 6.4.6, Python 3.7.10 (default, Feb 26 2021, 13:06:18) [MSC v.1916 64 bit (AMD64)]Anaconda.

## What is being done:
Create using 6 different machine learning models, over a Credt Risk Analysis of a Loan Portfolio, which can estimate better. The models are:
1. Random Oversampling
2. SMOTE Oversampling
3. Undersampling
4. Combination Sampling
5. Balanced Random Forest Classifier
6. Easy Ensemble AdaBoost Classifier

## Results:
The results of each of the six machine learning modelsare listed below. It includes per model including:
- Precision (PRE): Precision refers to the number of true positives divided by the total number of positive predictions
- Recall (REC): recall means the percentage of a certain class correctly identified.
- Balanced accuracy (BA): is a metric that one can use when evaluating how good a binary classifier is. It is especially useful when the classes are imbalanced, i.e. one of the two classes appears a lot more often than the other. 

### Random Oversampling
![Random_Oversampling]
- PRE: 0.01 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.60 High Risk,  0.68 Low Risk
- BA: 0.6413

### SMOTE Oversampling
![Smote_Oversampling]
- PRE: 0.01 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.60 High Risk,  0.68 Low Risk
- BA: 0.6374

### Undersampling
![Undersampling]
- PRE: 0.01 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.60 High Risk,  0.68 Low Risk
- BA: 0.6413

### Combination Under-Over Sampling
![Combination_sampling]
- PRE: 0.01 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.70 High Risk,  0.58 Low Risk
- BA: 0.5292

### Balanced Random Forest Classifier
![BRFC_Model]
- PRE: 0.04 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.67 High Risk,  0.91 Low Risk
- BA: 0.7877

### Easy Ensemble AdaBoost Classifier
![Easy_Ensemble]
- PRE: 0.07 High Risk (Meaning Low) 1.00 Low Risk (Meaning High)
- REC: 0.91 High Risk,  0.94 Low Risk
- BA: 0.9254

## Summary:
Aftere analyzinf teh results of each model, we can confirm that the Easy Ensemble AdaBoost Classifier Model is the one which has the better indicators for Credit Risk Analysis. Precision has the highest result for High risk with 0.07, meanwhile others do not exceed of 0.04. On the Recall it has the Percentaje for High and Low risk on levels over 90%, meanwhile the othe models round on 60%. Finally the balance Accuracy is almost 100% on 0.9254, against the other models whic do not exceed 79%.

