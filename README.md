
# Overview

A from-scratch parallel random forest model in Python used to predict whether a student has a learning disability. The problem is modeled as a binary classification task where the target feature is learning_disability.

The custom model is benchmarked against scikit-learn's random forest, achieving comparable performance. The custom model achieved slightly higher confidence interval than the library version.

Also contains the feature analysis pipeline used, which includes:
* Dataset cleaning which removes improper entries (null, wrong data types);
* Feature encoding using a custom Label Encoder for categorical features;

# Metrics

The following metrics are used to evaluate the model's performance: train/test accuracy, precision, recall, F1, AUC, AUPRC, 95% confidence intervals, 5-fold cross validation.

# How to run

This project requires python version 3.10 or later. Run using python main.py and the program will automatically fit both the custom and the library model on the data set and output the aforementioned metrics.
