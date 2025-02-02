### K- NN Classification - Machine Learning Project

Overview

This repository contains a K Nearest Neighbours (KNN) Classification model implemented in Python using Scikit-Learn. The model is trained on a dataset (Social_Network_Ads.csv) to predict whether a user will purchase a product based on Age and Estimated Salary.

Project Workflow

- Data Preprocessing: 
  - Load the dataset using Pandas.
  - Split data into training and test sets.
  - Apply feature scaling using StandardScaler to normalize the values.
- Model Training:
  - Train a K-NN Classifier using the KNeighborsClassifier.
  - Fit the model to the training dataset.
- Predictions & Evaluation:
  - Make predictions on the test dataset.
  - Evaluate model performance using a Confusion Matrix and Accuracy Score.
- Visualization:
  - Plot decision boundaries for both training and test sets using matplotlib.

### Dataset

The dataset contains:

- Age (Independent Variable)
- Estimated Salary (Independent Variable)
