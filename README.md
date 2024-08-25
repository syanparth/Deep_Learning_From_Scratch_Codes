# Perceptron-Based Logic Gate Implementations

This project demonstrates the implementation of basic logic gates (AND, OR, NOT, NAND, NOR, XOR, and XNOR) using a ions)
   - [AND Gate](#and-gate)
   - [OR Gate](#or-gate)
   - [NOT Gate](#not-gate)
   - [NAND Gate](#nand-gate)
   - [

## Perceptron Model

The Perceptron model is a type of linear classifier used for binary classification tasks. The Perceptron model in this project uses a unit step function as the activation function, which outputs `1` if the input is greater than or equal to zero and `0` otherwise.

# Housing Prices Prediction

This project demonstrates a simple linear regression model to predict housing prices based on the size of the house.

## Table of Contents

1. [Overview](#overview)
2. [Data Initialization](#data-initialization)
3. [Model Prediction](#model-prediction)
4. [Plotting th
import numpy as np

# Initialize the training data
x_train = np.array([1.0, 2.0, 3.0, 10.0])  # House sizes in 1000 square feet
y_train = np.array([300.0, 500.0, 700.0, 1200.0])  # Prices in 1000s of dollars

# Display the initialized data
print(f"x_train = {x_train}")
print(f"y_train = {y_train}")
