# Regularization-Techniques

This file conatins the prediction of 3 different features. I used Ridge Regression, Lasso Regression, Linear Regression and some other Regression algorithms. 

The dataset is so small, it contains only 45 rows. The problem is overfitting. 

So to overcome overfitting, I chose to use Regularization techniques, for generalization.

## Lasso Regression
Lasso regression is a regularization technique that applies a penalty to prevent overfitting and enhance the accuracy of statistical models.
w-hat = argminw MSE(W ) + ||w||1


## Ridge Regression
Ridge regression—also known as L2 regularization—is one of several types of regularization for linear regression models. Regularization is a statistical method to reduce errors caused by overfitting on training data.
w-hat = argminw MSE(W ) + ||w||2

Hyperparameter tuning is performed on regularization algorithms to find best parameters. 

Finally, the models are built simple and saved. 

Note: The dataset is not given due to some reasons.
