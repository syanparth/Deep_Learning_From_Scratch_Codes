# Housing Prices Prediction

This project demonstrates a simple linear regression model to predict housing prices based on the size of the house.

## Table of Contents

1. [Overview](#overview)
2. [Data Initialization](#data-initialization)
3. [Model Prediction](#model-prediction)
4. [Plotting the Data](#plotting-the-data)
5. [Making Predictions](#making-predictions)
6. [How to Run](#how-to-run)

## Overview

The project uses a linear model to predict housing prices. The input variable `x_train` represents the size of the house in 1000 square feet, and the target variable `y_train` represents the price in 1000s of dollars.

## Data Initialization

```python
import numpy as np

x_train = np.array([1.0, 2.0, 3.0, 10.0])
y_train = np.array([300.0, 500.0, 700.0, 1200.0])

print(f"x_train = {x_train}")
print(f"y_train = {y_train}")
