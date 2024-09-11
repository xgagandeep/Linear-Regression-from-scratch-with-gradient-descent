
# Project: Linear Regression with Gradient Descent

**Date:** 2020  
**Language:** Python  
**Libraries:** NumPy, Pandas, Matplotlib  
**Type:** Linear Regression Implementation

## Description

This project demonstrates the implementation of linear regression using gradient descent. The goal is to fit a linear model to the training data and make predictions on test data. The code covers data normalization, hypothesis computation, error calculation, gradient computation, and visualization of the results.

## Features

- **Data Loading:** Reads training and test datasets from CSV files.
- **Data Normalization:** Normalizes feature values to standardize the range.
- **Linear Regression:** Implements hypothesis function, error function, and gradient descent for model training.
- **Visualization:** Plots data points, regression lines, and error convergence.
- **Prediction:** Makes predictions on test data and saves the results to a CSV file.
- **Interactive Visualization:** Displays interactive plots of the regression process.

## Files

- `Linear_X_Train.csv`: Training features dataset.
- `Linear_Y_Train.csv`: Training target values dataset.
- `Linear_X_Test.csv`: Test features dataset.
- `output.csv`: Output file with predictions for the test dataset.

## Installation

To run this project, you need Python and the required libraries installed. Follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/xgagandeep/Linear-Regression-from-scratch-with-gradient-descent.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd linear-regression-gradient-descent
   ```

3. **Install the required libraries:**

   ```bash
   pip install numpy pandas matplotlib
   ```

4. **Prepare Data Files:**

   Make sure to place `Linear_X_Train.csv`, `Linear_Y_Train.csv`, and `Linear_X_Test.csv` in the appropriate directories as specified in the script.

5. **Run the Script:**

   ```bash
   python script.py
   ```

## Usage

1. **Load Data:** The script loads training and test data from CSV files.
2. **Normalize Data:** The feature values are normalized to improve model performance.
3. **Train Model:** Linear regression parameters are learned using gradient descent.
4. **Visualize Results:** The script generates plots of the training data, regression line, and error convergence.
5. **Make Predictions:** Predictions are made on the test data and saved to `output.csv`.

## Functions

- `hypothesis(x, theta)`: Computes the hypothesis function for given inputs.
- `error(X, Y, theta)`: Calculates the mean squared error for the given parameters.
- `gradient(X, Y, theta)`: Computes the gradient of the error function.
- `gradientDescent(X, Y, max_iteration, learning_rate)`: Performs gradient descent to optimize the parameters.
- `r2score()`: Calculates the R^2 score to evaluate model performance.

## Contribution

Feel free to contribute to this project by submitting issues or pull requests. For any questions or feedback, please open an issue on the GitHub repository.

-
