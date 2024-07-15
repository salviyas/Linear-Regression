# Linear-Regression

## Introduction

The goal of this project is to predict housing prices in Boston based on various features of the houses. The dataset used in this project is the Boston Housing dataset, which contains 506 observations on housing prices along with 13 features.

## Dataset

The Boston Housing dataset contains the following columns:
- `CRIM`: Per capita crime rate by town.
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq. ft.
- `INDUS`: Proportion of non-retail business acres per town.
- `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- `NOX`: Nitric oxides concentration (parts per 10 million).
- `RM`: Average number of rooms per dwelling.
- `AGE`: Proportion of owner-occupied units built prior to 1940.
- `DIS`: Weighted distances to five Boston employment centers.
- `RAD`: Index of accessibility to radial highways.
- `TAX`: Full-value property tax rate per $10,000.
- `PTRATIO`: Pupil-teacher ratio by town.
- `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
- `LSTAT`: Percentage of lower status of the population.
- `MEDV`: Median value of owner-occupied homes in $1000s (target variable).

#The script performs the following steps:

Loads and preprocesses the data.
Visualizes the data and the distribution of residuals.
Trains a linear regression model.
Evaluates the model using Mean Squared Error (MSE) and R-squared (R^2) metrics.
Plots the actual vs. predicted values and the fitting line.
