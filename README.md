# k-fold Cross Validation

K-fold cross-validation is a technique used to assess and optimize the performance of machine learning models. The dataset is divided into K subsets, or "folds." The model is trained on K-1 folds and tested on the remaining one. This process is repeated K times, and the average performance is used to gauge the model's generalization ability.

## 1. Data Preparation

- Split the dataset into 80% for training and 20% for testing.
- Normalize/Regularize data if necessary.
- Encode categorical variables using appropriate encoding method if necessary.

## 2. Logistic Regression Model

Train a Logistic Regression model on the dataset using saga solver from the scikit-learn package and using no regularization penalty.

## 3. Cross Validation

Cross Validate the classifier with 5-folds and print the mean accuracy, precision, and recall for the class 1 (good) for the classifier. You may or may not use the scikit-learn implementations for computing these metrics. However, I have not used any ML package for the cross-validation logic.
