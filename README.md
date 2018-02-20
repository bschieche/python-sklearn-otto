# Test several classification algorithms on Otto product data

This Python3 notebook shows the use of many scikit-learn features. They are applied to the Otto classification challenge hosted by kaggle in 2015 (https://www.kaggle.com/c/otto-group-product-classification-challenge). The train and test data is also available at the given URL. 

A special focus of this notebook lies on xgboost, which plays an important role with respect to computational time and accuracy in many winning solutions of kaggle competitions. Here it also outperforms many other models.

You will find sections to the following topics:
* some visualization techniques (PCA, t-SNE), descriptive statistics with seaborn package
* comparison of classifiers
* hyperparameter tuning / grid search with **xgboost**
* **calibration** to improve predicted class probabilities
* **ensemble learning**: bagging, soft voting, stacking

For an improved view please use the following nbviewer URL:

https://nbviewer.jupyter.org/github/bschieche/python-sklearn-otto/blob/master/otto-classification-challenge.ipynb
