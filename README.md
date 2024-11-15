# Computational Linear Algebra Assignment

## Overview
This project implements key computational linear algebra techniques to solve various problems, including solving linear systems using QR factorization, fitting data with least squares, and analyzing real-world datasets.

## Files
- **main.ipynb**: Jupyter notebook containing all the implementation and solutions.
- **House_Sales_Data.py**: Python file providing sample housing data for the house price prediction problem.

## Dependencies
The following Python libraries are required to run the code:
- `numpy`: For numerical computations and matrix operations.
- `matplotlib`: For plotting graphs and visualizing data.

## Assignment Components
### 1. Solving Linear Systems with QR Factorization
- Decomposes a matrix into orthonormal (`Q`) and upper triangular (`R`) matrices using the Gram-Schmidt process.
- Solves linear systems using the back substitution algorithm.
- Computes the relative error to validate the solution.

### 2. Data Fitting with Least Squares
- Applies the least squares method to fit a linear model to the annual petroleum consumption data.
- Generates a plot to visualize the actual consumption data and the fitted line.

### 3. House Price Prediction
- Uses real-world housing data to predict house prices based on the number of bedrooms and house size.
- Implements the least squares method to determine the model parameters.
- Calculates the average difference between the predicted and actual house prices.

## How to Run
1. Open the Jupyter notebook `main.ipynb` in Google Colab or your local Jupyter environment.
2. Run the notebook cell by cell, following the instructions and ensuring the `House_Sales_Data.py` file is in the same directory as the notebook.
3. Analyze the outputs and plots generated.

## Results
- **Relative Error**: The relative error for solving the linear system is close to zero, indicating accurate solutions.
- **Petroleum Consumption Fit**: The linear model accurately fits the data, and the plot shows a good match.
- **House Price Prediction**: The model provides a reasonable prediction of house prices, with the average price difference being below 30% of the average house price.

## Notes
- Ensure the random seed is fixed as provided in the notebook to maintain reproducibility.
- The code uses Python 3.7+ and has been tested on Google Colab.

## Acknowledgments
- The housing dataset and problem structure were provided as part of the assignment materials.
- QR factorization and least squares techniques are implemented based on course instructions and textbook references.

## Contact
For questions or clarifications, please contact [Your Name] at [Your Email].
