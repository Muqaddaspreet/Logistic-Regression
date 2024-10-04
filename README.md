# Logistoc Regression

## Project Overview

This repository contains the implementation two machine learning algorithms: **Perceptron** and **Logistic Regression**, along with their variants.

## Project Structure

- **notebooks/**: This folder contains the Jupyter notebooks for the project, which include all source code with documentation.
- **data/**: Contains the dataset used for training and testing the logistic regression model. The dataset is split into five CSV files, which need to be combined for the training process.
- **README.md**: This file, providing an overview of the project.

##  Details

###  Perceptron
This requires answering the following:
1. Whether the given dataset can be learned by a Perceptron, and the weight update process.
2. The number of boolean functions that can be learned by a Perceptron.
3. A modified version of the Perceptron algorithm and its convergence properties.

### Logistic Regression
This exercise involves implementing a **Logistic Regression** algorithm, followed by evaluating it on a dataset using **Gradient Descent**. Specific tasks include:
1. Implementing logistic regression and learning the parameters using Gradient Descent.
2. Plotting error and loss metrics during the training process.
3. Adding a regularization term to the logistic regression loss function and comparing results for different regularization strengths.
4. Applying **5-fold cross-validation** to optimize the regularization parameter.

### Output Plots
The following plots are generated during the implementation:
- Training error vs. number of epochs
- Test error vs. number of epochs
- Training loss vs. number of epochs
- Test loss vs. number of epochs

## Getting Started

### Prerequisites
- **Python 3.6+**
- **Jupyter Notebook**
- **Libraries**:
  - `numpy`
  - `matplotlib`

You can install the required Python packages using:
```bash
pip install numpy matplotlib
```
