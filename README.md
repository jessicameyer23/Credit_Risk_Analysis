# Credit_Risk_Analysis
## Overview

The purpose of this project is to evaluate our loan prediction risk analysis machine learning algorithms.  We are evaluating different algorithms to determine whether any of these models should be used to predict credit risk.

## Results



![image_name](https://github.com/jessicameyer23/Amazon_Vine_Analysis/blob/main/Images/Total%20%20count%20of%20Vine%20paid%20reviews2022-04-03%20151953.png)



# Summary









Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
