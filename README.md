# Credit_Risk_Analysis

## Overview

The following analysis examines six different machine learning algorithms to compare and contrast their effectiveness (or ineffectiveness) using the classification reports and balanced accuracy score. The application of the algorithms is in determining credit card risk rating. The six algorithms used will be:

* Native RandomOverSampler
* SMOTE oversampling
* ClusterCentroids undersampling
* SMOTEENN combination over- & undersampling
* BalancedRandomForestClassifier reduced bias sampling
* EasyEnsembleClassifier reduced bias sampling

## Resources

Language & libraries used in this analysis are: 

* Python
  * scikit-learn library
  * imbalanced-learn library
  * Pandas

From the [dataset provided](LoanStats_2019Q1.csv), a sample for training and testing was divided using the train_test_split function (using the random_state value of 1). The training data set was then used in each algorithm to produce a Logistic Regression model or classifier model which was then tested with the test subset of the data. Balance accuracy scores are then calculated and the classification report produced.

## Results

The balanced accuracy scores of each of the aforementioned algorithms are summarized in the below table.

![BalancedAccuracyScores](/Resources/BalancedAccuracyScores.png)

Then each individual algorithm's classification report is shown in the following list:

* Native RandomOverSampler

![RandomOverSampler](/Resources/RandomOversampler.png)

* SMOTE oversampling

![SMOTE](/Resources/SMOTE.png)

* ClusterCentroids undersampling

![ClusterCentroids](/Resources/ClusterCentroids.png)

* SMOTEENN combination over- & undersampling

![SMOTEENN](/Resources/SMOTEENN.png)

* BalancedRandomForestClassifier

![BRFC](/Resources/BalancedRandomForestClassifier.png)

* EasyEnsembleClassifier

![EEAB](/Resources/EasyEnsembleAdaBoost.png)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.