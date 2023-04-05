# 08 - Model Selection

## Introduction

In this section, we will know how to select the best model for our data using `Accuracy Score` and `Confusion Matrix`.

## Dataset Information

We are given a dataset of [Breast Cancer Wisconsin (Diagnostic)](<https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)>), we need to predict whether the cancer is benign or malignant.

- `radius`: mean of distances from center to points on the perimeter
- `texture`: standard deviation of gray-scale values
- `perimeter`: mean size of the core tumor
- `area`: mean smoothness of the image
- `smoothness`: mean number of concave portions of the contour
- `compactness`: mean symmetry
- `concavity`: mean fractal dimension ("coastline approximation" - 1)
- `concave points`: mean fractal dimension ("coastline approximation" - 2)
- `symmetry`: mean fractal dimension ("coastline approximation" - 3)
- `fractal dimension`: mean fractal dimension ("coastline approximation" - 4)
- `target`: 0 for Benign, 1 for Malignant

## Evaluation Metric

We will be using `Accuracy Score` and `Confusion Matrix` to evaluate the performance of our model.

## Scores

|           Model           |    Accuracy Score    | Position |
| :-----------------------: | :------------------: | :------: |
|    Logistic Regression    | $0.9473684210526315$ |   $3$    |
| K-Nearest Neighbors (KNN) | $0.9473684210526315$ |   $3$    |
| Support Vector Classifier | $0.9415204678362573$ |   $4$    |
|   Kernel SVM Classifier   | $0.9532163742690059$ |   $2$    |
|  Naive Bayes Classifier   | $0.9415204678362573$ |   $4$    |
| Decision Tree Classifier  | $0.9590643274853801$ |   $1$    |
| Random Forest Classifier  | $0.935672514619883$  |   $5$    |

## Results

We can see that `Decision Tree Classifier` is the best model for our data with an accuracy score of $0.9590643274853801$.
