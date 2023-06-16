# Cancer Analysis
# Breast Cancer Detection

This repository contains code for a breast cancer detection project. The goal of the project is to develop machine learning models that can classify breast cancer tumors as benign or malignant based on various features.

## Dataset

The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Dataset. It consists of measurements from digitized images of breast mass samples, including features such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

## Models

### Random Forest Classifier

The Random Forest Classifier model was trained using the following configuration:

- Number of estimators: 100
- Maximum depth: 5

This model achieved an accuracy of 0.95 on the test set.

### Support Vector Machine (SVM) Classifier

The SVM Classifier model was trained using the following configuration:

- Kernel: RBF
- Regularization parameter (C): 1.0
- Gamma: auto

This model achieved an accuracy of 0.92 on the test set.
