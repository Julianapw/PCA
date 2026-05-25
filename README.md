# Wine Dataset Principal Component Analysis (PCA)

## Technologies Used

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="45" height="45"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="45" height="45"/>
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="45" height="45"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="70" height="45"/>
  <img src="https://images.plot.ly/logo/new-branding/plotly-logomark.png" width="45" height="45"/>
</p>

---

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
