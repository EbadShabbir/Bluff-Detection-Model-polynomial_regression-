# Polynomial and Linear Regression for Position Salaries

This project uses both Linear and Polynomial Regression techniques to predict employee salaries based on their job position levels. The dataset contains position levels and their corresponding salaries, allowing us to model and compare different degrees of polynomial regression.

## Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Results](#model-results)
- [Visualizations](#visualizations)
- [License](#license)

## Overview
The purpose of this project is to:
- Train and visualize a **Linear Regression** model.
- Train and visualize **Polynomial Regression** models with degrees 2, 3, and 4.
- Compare the predictions made by each model for a position level of 6.5.

This allows us to understand the difference in performance between linear and polynomial regression when fitting non-linear data.

## Dependencies
The project uses the following Python libraries:
- `pandas`
- `scikit-learn`
- `matplotlib`
- pip install pandas scikit-learn matplotlib
- pip install -r requirements.txt

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/EbadShabbir/polynomial-regression-position-salaries.git
2. Installing Libraries:
   '''bash
   - pip install pandas scikit-learn matplotlib
   - pip install -r requirements.txt
# LINEAR REGRESSION RESULT
lin_pred = lin_regs.predict([[6.5]])  
print(f"Linear Regression Prediction for 6.5: {lin_pred}")

# POLYNOMIAL REGRESSION RESULT (degree 2)
poly_pred_2 = lin_reg_2.predict(poly_regs_2.fit_transform([[6.5]]))  
print(f"Polynomial Regression (Degree 2) Prediction for 6.5: {poly_pred_2}")

# POLYNOMIAL REGRESSION RESULT (degree 3)
poly_pred_3 = lin_reg_3.predict(poly_regs_3.fit_transform([[6.5]]))  
print(f"Polynomial Regression (Degree 3) Prediction for 6.5: {poly_pred_3}")

# POLYNOMIAL REGRESSION RESULT (degree 4)
poly_pred_4 = lin_reg_4.predict(poly_regs_4.fit_transform([[6.5]]))  
print(f"Polynomial Regression (Degree 4) Prediction for 6.5: {poly_pred_4}")

### Notes:
1. Make sure you include images of the regression plots (`linear_regression.png`, `polynomial_regression_2.png`, etc.) in the `images` directory.
2. Customize the actual predicted salary values in the `Model Results` section after running the script.
3. Ensure that the dataset path and other links (e.g., GitHub repository URL) are updated to reflect your environment.

This `README.md` should provide clear instructions and detailed explanations for users to understand and run your project.
