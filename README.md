# Wine Dataset Principal Component Analysis (PCA)

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=flat-square&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=flat-square&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-orange?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4c72b0?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-f7931e?style=flat-square&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Visualization-3f4f75?style=flat-square&logo=plotly)

## Overview
This repository contains an exploratory data analysis and dimensionality reduction study using Principal Component Analysis (PCA) on the Wine dataset available from Scikit-learn.

The project investigates the relationships between the chemical properties of different wine classes and evaluates how PCA can reduce dataset dimensionality while preserving most of the original information.

The analysis includes statistical exploration, visual comparison of the original features, and dimensionality reduction in 1D, 2D, and 3D spaces to better understand class separation and data representation.

---

## Objectives and Requirements

### Dataset Exploration
- Import and inspect the Wine dataset
- Analyze the number of samples, features, and target classes
- Display the first rows of the dataset

### Feature Relationship Analysis
- Use Seaborn Pairplot to visualize relationships between features
- Compare class separation using the original variables
- Identify which feature combinations provide better discrimination between wine classes

### Dimensionality Reduction with PCA
- Apply PCA to reduce the dataset into:
  - 2 principal components
  - 1 principal component
  - 3 principal components
- Generate 2D and 3D visualizations of the transformed data

### Explained Variance Analysis
- Calculate the explained variance ratio for each principal component
- Build an Elbow Plot to visualize cumulative explained variance
- Determine the optimal number of components for efficient data representation

### Principal Component Interpretation
- Display the PCA component coefficient matrix
- Identify the most influential features in PC1 and PC2
- Construct the mathematical equation for the first principal component (PC1)

---

## Main Features

### Exploratory Data Analysis
Statistical and visual analysis of wine chemical properties using descriptive metrics and visualization techniques.

### Class Visualization
Comparison of class separation in both the original feature space and the PCA-transformed spaces.

### Dimensionality Reduction
Complete PCA implementation to transform high-dimensional data into compact and interpretable representations.

### Interactive 3D Visualization
Interactive 3D scatter plots built with Plotly for enhanced visualization of principal components.

### PCA Interpretation
Analysis of PCA coefficients to understand which variables contribute most to class separation.

### Variance Evaluation
Construction of cumulative explained variance graphs to evaluate the efficiency of dimensionality reduction.
Construction of cumulative explained variance graphs to evaluate the efficiency of dimensionality reduction.
