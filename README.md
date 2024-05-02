# Illustration of Gradient Descent in 2-D Data for Polynomial Regression

## Overview
This Jupyter Notebook provides a comprehensive walkthrough of implementing gradient descent from scratch to optimize a second-degree polynomial model for a regression problem. The notebook is designed to help users understand the fundamental concepts behind gradient descent, a crucial optimization algorithm widely used in machine learning and deep learning.

## Contents
1. **Introduction**
    - Brief explanation of gradient descent and its importance in machine learning.
    - Definition of the polynomial regression problem.

2. **Goal of Gradient Descent — First Steps**
    - Introduction to the second-degree polynomial model.
    - Creation of initial model and data visualization.

3. **Improving Realism with Jitter**
    - Addition of noise to the data for a more realistic scenario.
    - Implementation and demonstration of the updated evaluation function.

4. **First Pass at Modeling — Trying a Random Model**
    - Generation of a random model with random coefficients.
    - Visualization of the initial model's fit to the data.
    - Calculation of Mean Squared Error (MSE) as the initial loss metric.

5. **Gradient Descent and Loss Reduction**
    - Explanation of the gradient descent algorithm.
    - Derivation of partial derivatives for the MSE loss function.
    - Update of model coefficients using gradient descent to minimize loss.
    - Visualization of the updated model's fit to the data.

6. **Iterative Gradient Descent over Many Epochs**
    - Refinement of the gradient calculation function for iterative gradient descent.
    - Implementation of the gradient descent function to train the model over multiple epochs.
    - Visualization of the final predicted model after gradient descent training.
    - Analysis of the final model coefficients and loss reduction over iterations.

## Instructions for Use
1. Ensure you have Jupyter Notebook installed to run the provided `.ipynb` file.
2. Clone or download this repository to your local machine.
3. Open the Jupyter Notebook `regression.ipynb` using Jupyter Notebook.
4. Run each cell sequentially to follow along with the explanations and code implementation.
5. Experiment with different parameters, such as learning rate and number of epochs, to observe their effects on model training and convergence.
6. For further exploration, consider applying the concepts learned here to other regression problems or experimenting with different polynomial degrees.

## Contributer
- Name   : Paide Ashish
- Roll No: 200101072
