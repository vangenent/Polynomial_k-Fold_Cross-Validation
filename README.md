# Polynomial k-Fold Cross-Validation

This Python script implements k-fold cross-validation for polynomial regression models of four different degrees. The purpose is to determine which degree of polynomial fits the data best by evaluating the mean quadratic fit (MQF) over k partitions of the data.
Features

    k-Fold Cross-Validation: The data is split into k partitions (folds), and for each fold, a different subset of the data is used as a test set, while the remaining data is used for training.
    Polynomial Regression: Polynomial models of degrees 1 to 4 are fitted to the training data.
    MQF Calculation: The mean quadratic fit (MQF) is calculated for each model to assess its accuracy.
    Model Selection: The polynomial degree that minimizes the MQF is selected as the best-fitting model.

    
