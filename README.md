# COMP4311 - Big Data - Assignment 2

This repository contains code and documentation for Assignment 2 of the COMP 4311-Big Data course, focusing on Decision Trees and Neural Networks for classification tasks using the Iris dataset.

## Overview

In this assignment, I'll implement a Decision Tree Classifier to classify the Iris dataset into binary classes and visualize the decision tree, then also define entropy and information gain and compare calculated values with visualization results.

Additionally, I'll build a simple neural network for Iris dataset classification, observing changes in model loss and accuracy with each training epoch. Then, I can discuss the impact of varying parameters like hidden neurons, epochs, and batch size on model performance.
## Questions

### Q1. Decision Tree Classifier

#### Part a. Implement a Decision Tree Classifier

- Implement a Decision Tree Classifier to classify the Iris dataset from the sklearn library.
- Modify the dataset to create a binary classification set (e.g., Setosa (0), Non-Setosa (1)).
- Visualize the decision tree and use the criterion of information gain to build the tree.
- Your Python code notebook should be appropriately commented for all the steps, including data loading, preprocessing, model training, evaluation, and any additional experiments.

#### Part b. Define entropy and information gain

- Define entropy and information gain in the context of decision tree algorithms.
- Focus on calculating the information gain for the attribute(s) used at the first level of the tree.
- Compare the calculated values with those obtained from visualizing the tree through the code.
- Show all your steps of calculations clearly.

### Q2. Simple Neural Network

#### Part a. Implement a simple neural network

- Implement a simple neural network to classify the Iris dataset.
- Specifications:
  - One input layer, one hidden layer, and one output layer.
  - Hidden layer with a specified number of neurons (e.g., 10 neurons) and a ReLU activation function.
  - Output layer with neurons corresponding to the classes in the Iris dataset and a softmax activation function.
- Visualize how the model loss and accuracy change with each training epoch.
- Your Python code notebook should be commented appropriately for all the steps, including data loading, preprocessing, model training, evaluation, and any additional experiments.

#### Part b. Discuss the challenges and potential impacts

- Discuss the challenges and potential impacts of choosing different numbers of hidden neurons, number of epochs, and batch size values on the training process and final model performance.
- Base your answers on the graphs generated from the code.

## Repository Structure

- `decision_tree_classifier.ipynb`: Jupyter notebook for Decision Tree Classifier.
- `neural_network_classifier.ipynb`: Jupyter notebook for Simple Neural Network.
- `data_processing.py`: Python script for data preprocessing functions.
- `utils.py`: Python script for utility functions.
- `README.md`: This README file.
- `requirements.txt`: Required Python packages.

## Getting Started

1. Clone this repository.
2. Install required Python packages listed in `requirements.txt`.
3. Run Jupyter notebooks (`decision_tree_classifier.ipynb` and `neural_network_classifier.ipynb`) to execute code and observe results.


