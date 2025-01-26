# Regression Model Interactive Application

An interactive application for performing **Simple Linear Regression** and **Multiple Linear Regression**, complete with data preprocessing, visualization, and result analysis. This project demonstrates the power of Python, Jupyter Notebooks, and key data science libraries.

---

## Features

- **Data Upload**: Seamlessly upload your dataset and preview it.
- **Preprocessing**: Options to handle missing values, remove duplicates, and prepare the data.
- **Model Options**:
  - **Simple Linear Regression**:
    - Choose a single predictor and target variable.
    - Visualize results with a scatter plot, regression line, equation, and R-squared value.
    - Example GIF:
      ![Simple Linear Regression Example](path/to/simple_regression.gif)
  - **Multiple Linear Regression**:
    - Select multiple predictors and a target variable.
    - Display a Variance Inflation Factor (VIF) table to check multicollinearity.
    - Show OLS Regression Results and residual plots.
    - Example GIF:
      ![Multiple Linear Regression Example](path/to/multiple_regression.gif)
- **Reset Functionality**: Reset the application to test other models.

---

## Demo

### Simple Linear Regression
![Simple Linear Regression Example](path/to/simple_regression.gif)

### Multiple Linear Regression
![Multiple Linear Regression Example](path/to/multiple_regression.gif)

---

## Code Overview

### Main Components:
- **`app.py` or Jupyter Notebook**:
  - Interactive widgets for user-friendly data processing and model configuration.
  - Visualization and statistical analysis for linear regression.
- **Dataset**: Example CSV datasets with:
  - Predictor variables (numerical).
  - Target variable (numerical).

