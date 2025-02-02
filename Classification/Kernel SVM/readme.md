### Kernel SVM Classification - Machine Learning Project

Overview

This repository contains a Kernel Support Vector Machine (SVM) Classification model implemented in Python using Scikit-Learn. The model is trained on a dataset (Social_Network_Ads.csv) to predict whether a user will purchase a product based on Age and Estimated Salary.

Project Workflow

Data Preprocessing: 
- Load the dataset using Pandas.
- Split data into training and test sets.
- Apply feature scaling using StandardScaler to normalize the values.
Model Training:
- Train a Kernel SVM Classifier using the Radial Basis Function (RBF) kernel.
- Fit the model to the training dataset.
Predictions & Evaluation:
- Make predictions on the test dataset.
- Evaluate model performance using a Confusion Matrix and Accuracy Score.
- Visualization:
Plot decision boundaries for both training and test sets using matplotlib.

### Dataset

The dataset contains:

- Age (Independent Variable)
- Estimated Salary (Independent Variable)
- Purchased (Target Variable: 1 if purchased, 0 otherwise)
