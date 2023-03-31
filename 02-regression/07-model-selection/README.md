# 07 - Model Selection

## Introduction

In this section, we will know how to select the best model for our data. Model Performance will be evaluated using $R^2-Score$.

## Dataset Information

We are given a dataset of [A combined cycle power plant (CCPP)](https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant), we need to predict the net hourly `Electrical Energy Output (EP)` of the plant using the given features.

- `Average Ambient Temperature (AT)`: Temperature in the range 1.81°C and 37.11°C
- `Exhaust Vacuum (V)`: Vacuum in the range 25.36-81.56 cm Hg
- `Ambient Pressure (AP)`: Pressure in the range 992.89-1033.30 milibar
- `Relative Humidity (RH)`: Humidity in the range 25.56% to 100.16%
- `Net hourly electrical energy output (EP)`: net hourly electrical energy output in MW

## Evaluation Metric

We will be using $R^2-Score$ to evaluate the performance of our model.

## Scores

|           Model            |     $R^2-Score$      | Position |
| :------------------------: | :------------------: | :------: |
| Multiple Linear Regression | $0.9325315554761303$ |   $4$    |
|   Polynomial Regression    | $0.9458193056880614$ |   $3$    |
|   Support Vector Machine   | $0.9480784049986258$ |   $2$    |
|  Decision Tree Regression  | $0.922905874177941$  |   $5$    |
|  Random Forest Regression  | $0.9615908334363876$ |   $1$    |

## Results

We can see that Random Forest Regression gives the best $R^2-Score$ of $0.9615908334363876$. So, for this dataset, Random Forest Regression performs the best.
