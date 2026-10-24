# SC5002 Lab Assignment – Part 2

This repository contains the Google Colab notebook for Part 2 of the SC5002 lab assignment.

The notebook uses the California Housing dataset from `sklearn.datasets`, with `MedHouseVal` as the target variable and the remaining features used as inputs. The features are scaled using `StandardScaler` before training.

Models used:
- Linear Regression
- Ridge Regression with α = 0.1, 10 and 1000

Model performance is compared using 5-fold cross-validation and the R² score.

The notebook also includes a bar chart comparing the performance of the different models.
