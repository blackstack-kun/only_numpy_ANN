# Heart Disease Prediction using ANN without Tensorflow/Keras

This repository contains an implementation of an Artificial Neural Network (ANN) for predicting heart disease using only NumPy. The ANN is trained on a dataset with 13 features and is designed to perform binary classification to determine the likelihood of heart disease.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)

## Introduction

It is a simplified version to illustrate the principles of neural networks, including forward propagation, backpropagation, and the impact of different activation functions.

## Dataset

The dataset used for this project contains 13 input features that are commonly used in heart disease prediction, such as age, cholesterol levels, blood pressure, etc. The target variable is binary, indicating the presence (1) or absence (0) of heart disease.

### Features:
- Age
- Sex
- Chest Pain Type (4 values)
- Resting Blood Pressure
- Serum Cholesterol in mg/dl
- Fasting Blood Sugar > 120 mg/dl
- Resting Electrocardiographic Results (values 0, 1, 2)
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- Oldpeak = ST Depression induced by exercise relative to rest
- The Slope of the Peak Exercise ST Segment
- Number of Major Vessels (0-3) colored by fluoroscopy
- Thal (3 = normal; 6 = fixed defect; 7 = reversible defect)

## Model Architecture

The ANN model consists of the following layers:
- **Input Layer:** 13 neurons corresponding to the 13 features.
- **Hidden Layer 1:** 10 neurons with ReLU activation.
- **Hidden Layer 2:** 10 neurons with ReLU activation.
- **Output Layer:** 1 neuron with sigmoid activation for binary classification (0 or 1).

### Activation Functions:
- **ReLU (Rectified Linear Unit):** Used in hidden layers.
- **Sigmoid:** Used in the output layer for binary classification.

### Forward and Backward Propagation:
The model uses forward propagation to compute predictions and backward propagation to update the weights and biases using gradient descent.

## Results
It got a Accuracy of 77%, and it can be made better using more layers or increasing the complexity, tuning the hyperparameters, Its just the intuition of how a neural network works.
