# Perceptron-Based Logic Gate Implementations

This project demonstrates the implementation of basic logic gates (AND, OR, NOT, NAND, NOR, XOR, and XNOR) using a Perceptron model.

## Table of 

1. [Overview](#overview)
2. [Perceptron Model](#perceptron-model)ate Implementations](#logic-gate-implementations)
   - [AND Gate](#and-gate)
   - [OR Gate](#or-gate)
   - [NOT Gate](#not-gate)
   - [NAND Gate](#nand-gate)
   - [NOR Gate](#nor-gate)
   - [XOR Gate](#xor-gate)
   - [XNOR Gate](#xnor-gate)
4. [Testing the Model](#testing-the-model)
5. [How to Run](#how-to-run)

## Overview

This project provides implementations of basic logic gates using a single-layer Perceptron. The Perceptron is a fundamental building block in neural networks and is capable of solving simple logical operations by appropriately setting weights and biases.

## Perceptron Model

The Perceptron model is a type of linear classifier used for binary classification tasks. The Perceptron model in this project uses a unit step function as the activation function, which outputs `1` if the input is greater than or equal to zero and `0` otherwise.

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

# Initialize the training data
x_train = np.array([1.0, 2.0, 3.0, 10.0])  # House sizes in 1000 square feet
y_train = np.array([300.0, 500.0, 700.0, 1200.0])  # Prices in 1000s of dollars

# Display the initialized data
print(f"x_train = {x_train}")
print(f"y_train = {y_train}")
