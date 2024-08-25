# Machine Learning Projects

This repository contains two projects: Perceptron-Based Logic Gate Implementations and Housing Prices Prediction.

## Table of Contents

1. [Perceptron-Based Logic Gate Implementations](#perceptron-based-logic-gate-implementations)
   - [Overview](#overview-1)
   - [Perceptron Model](#perceptron-model)
   - [Logic Gate Implementations](#logic-gate-implementations)
     - [AND Gate](#and-gate)
     - [OR Gate](#or-gate)
     - [NOT Gate](#not-gate)
     - [NAND Gate](#nand-gate)
     - [NOR Gate](#nor-gate)
     - [XOR Gate](#xor-gate)
     - [XNOR Gate](#xnor-gate)
   - [Testing the Model](#testing-the-model)
   - [How to Run](#how-to-run-1)

2. [Housing Prices Prediction](#housing-prices-prediction)
   - [Overview](#overview-2)
   - [Data Initialization](#data-initialization)
   - [Model Prediction](#model-prediction)
   - [Plotting the Data](#plotting-the-data)
   - [Making Predictions](#making-predictions)
   - [How to Run](#how-to-run-2)

---

## Perceptron-Based Logic Gate Implementations

### Overview

This project provides implementations of basic logic gates using a single-layer Perceptron. The Perceptron is a fundamental building block in neural networks and is capable of solving simple logical operations by appropriately setting weights and biases.

### Perceptron Model

The Perceptron model is a type of linear classifier used for binary classification tasks. The Perceptron model in this project uses a unit step function as the activation function, which outputs `1` if the input is greater than or equal to zero and `0` otherwise.

```python
import numpy as np

# Define Unit Step Function
def unitStep(v):
    if v >= 0:
        return 1
    else:
        return 0

# Design Perceptron Model
def perceptronModel(x, w, b):
    v = np.dot(w, x) + b
    y = unitStep(v)
    return y

