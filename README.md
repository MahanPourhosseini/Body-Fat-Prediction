### Problem Statement

This project aims to predict body fat percentage in a dataset of 252 individuals using Lasso and Ridge regression models. The primary objective is to compare the performance of these two regression techniques in terms of accuracy and error metrics.

### Project Overview

#### 1. Data Loading and Preprocessing
We start by loading the dataset from 'bodyfat.csv' and splitting it into features and the target variable ('Weight'). We also create training and testing datasets for model evaluation.

#### 2. Lasso Regression
- We implement Lasso regression and perform hyperparameter tuning using a grid search with cross-validation.
- The best alpha (hyperparameter) is determined, and the Lasso model is trained with this optimal alpha.
- Model performance is evaluated on both the training and testing datasets, calculating Mean Squared Error (MSE) and R-squared (R2).

#### 3. Ridge Regression
- Similarly, we implement Ridge regression and follow the same steps as with Lasso regression.
- The best alpha is found using cross-validation, and the Ridge model is trained with this optimal alpha.
- Model performance is evaluated using MSE and R2 on the training and testing datasets.

#### 4. Model Comparison
- We compare the performance of the Lasso and Ridge regression

### Conclusion

This project provides valuable insights into using Lasso and Ridge regression techniques for body fat prediction. The findings suggest that the Ridge regression model yields slightly better accuracy compared to Lasso. For a more detailed code implementation, please refer to the Jupyter Notebook in this repository.
