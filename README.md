# Star Bucks Project
This is an classification model which predicts whether a customer will respond to an offer or not.

## Installation
1. Python3.6
2. Pandas
3. NumPy
4. Matplotlib
6. Seaborn
7. sklearn
8. re
9. os
10. clean_data
11. exploratory_data_analysis
12. joblib
13. sys

## Motivation
The problem is to build a model that predicts whether a customer will respond to an offer. 

## Files in the repository
1. data : The dataset file.
2. Starbucks_Capstone_notebook.ipynb : Notebook file contaning the exploration and analysis of the work.
3. clean_data.py : Cleaning Data.
4. exploratory_data_analysis.py : Analysis of the data.
5. README.md : The readme file for write-up.

## Summary of the results
This problem is solved in four steps:
1. Combine the offer portfolio, customer profile, and transaction data. Each row of this combined dataset will describe an offer's attributes, customer demographic data, and whether the offer was successful.
2. I will assess the accuracy and F1-score of a naive model that assumes all offers were successful. This provides me a baseline for evaluating the performance of models that I construct. Accuracy measures how well a model correctly predicts whether an offer is successful. However, if the percentage of successful or unsuccessful offers is very low, accuracy is not a good measure of model performance. For this situation, evaluating a models' precision and recall provides better insight to its performance. I chose the F1-score metric because it is "a weighted average of the precision and recall metrics".
3. I will compare the performance of logistic regression, random forest, and gradient boosting models.
4. Refine the parameters of the model that has the highest accuracy and F1-score.

Model ranking based on training data accuracy
1. RandomForestClassifier model accuracy: 0.742
2. GradientBoostingClassifier model accuracy: 0.736
3. LogisticRegression model accuracy: 0.722
4. Naive predictor accuracy: 0.471

Model ranking based on training data F1-score
1. RandomForestClassifier model f1-score: 0.735
2. GradientBoostingClassifier model f1-score: 0.725
3. LogisticRegression model f1-score: 0.716
4. Naive predictor f1-score: 0.640

Results suggest that the random forest model has the best training data accuracy and F1-score

## Prediction is divided into the following steps
1. Reading Dataset
2. EDA
3. Data pre-processing
4. Feature Selection 
5. Modelling
6. Evaluation

## How to interact with your project?
Here you just need to install python and install the packages that are listed above and open this .ipymb file in your jupyter notebook and just run all cell or just click <b>SHIFT + ENTER</b> to run cell one by one.

## Licensing
This is just for learning.

## Authors
  Biswajit Satapathy
   Jr. Data Analyst
    Aptus Data Labs 
    
## Acknowledgement
Special thanks to Pramit Kumar Patra for giving his valuable time for teaching me statistics and machine learning.
