## Course Optimization for Data Science - Robust Regression

### Project Overview
This repository contains the project for the Optimization for Data Science course. The project focuses on optimization strategies for robust regression and involves implementing and analyzing different robust regression models.

### Project Objectives

The key objectives of this project include:
- Formulating the Mean Absolute Error (MAE) regression model as a Quadratic Program.
- Deriving and implementing the loss and gradients for the Huber model.
- Implementing custom solvers for L1 or squared L2 regularization using:
  - (Accelerated) Proximal Gradient Descent
  - Proximal Coordinate Descent
  - L-BFGS (only for L2 regularization)
- Creating a custom scikit-learn estimator for the Huber regression model.
- Comparing the Huber model’s performance against Ridge and Lasso regression on real datasets.
- Providing well-structured figures and results, similar to an experiment section in a research paper.

#### Getting Started

Ensure you have the following dependencies installed:

pip install numpy scipy matplotlib cvxopt numba

#### Running the Notebook

Open the Jupyter notebook and execute the cells in order:

jupyter notebook project_danan_solal_and_mourre_gregoire.ipynb

### Project Structure
- Part 0: Why a Robust Regression Model?Introduction to robust regression and generating a dataset with outliers.
- Part 1: Mean Absolute Error (MAE) Regression
- Part 2: Huber Regression
- Part 3: Custom Solvers for L1 and L2 Regularization
- Part 4: Creating a scikit-learn Estimator
- Part 5: Experiments and Results

### Results & Analysis

The project explores the efficiency of different regression techniques in handling outliers and noise in data. Detailed analysis and performance comparisons are provided, showcasing the effectiveness of robust regression methods.

### Contributors
Solal Danan
Grégoire Mourre

This project was completed as part of the Optimization for Data Science course given by Alexandre Gramfort and Rémi Flamary.
