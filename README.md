# Feature Scaling

Map data into range [0, 1]. Why?
* Speed up learning
* Consider the features as equally important (at least initially) 

## Formula

X_new = (X-X_min) / (X_max-X_min)

## Algorithms affected by Feature Scaling:
* Neural Networks
* K-Nearest Neighbors
* K-Means Clustering
* Support Vector Machine

## Algorithms NOT affected by Feature Scaling:
* Naive Bayes
* Linear Regression (unless regularized)
* Decision Trees
* Random Forests
* Logistic Regression (unless regularized)
