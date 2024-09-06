# Kernelized Regression with Missing Features

This project focuses on predicting electricity prices in Switzerland based on historical data from various countries over the past few years, where many features are missing.

My approach involves categorical encoding using the `OrdinalEncoder` class and data imputation with `IterativeImputer` to handle categorical data and missing features. Once the data set is complete, K-Fold cross-validation is applied to determine the optimal kernel from among the linear, squared exponential (RBF), polynomial, Matern, and RationalQuadratic kernels. The `GaussianProcessRegressor` framework is used for training and making predictions. For more detailed explanations and implementations, please refer to `main.ipynb`.
