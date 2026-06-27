# Univariate Linear Regression

This repository contains three versions of the Supervised Learning - Univariate Linear Regression Project:

- **`supervised_learning_univariate_linear_regression.ipynb`** — the original version of the project.
- **`review.ipynb`** — the review version, containing additional information and broken-down visualizations to aid understanding.
- **`interactive.ipynb`** — an interactive version where the user can input a value for X and adjust the slope and intercept in real time to see how predictions change.

## Notebook Workflow

In the notebook, line fitting is achieved through the following steps:

- Generating synthetic data (`X`, `Y`) with a linear relationship (`Y = 2X + 1`) plus some added noise.
- Defining a function, `plot_linear_regression`, that takes two parameters: `slope` and `intercept`.
- Inside the function, computing the predicted `Y` values using the linear equation:
  - `predicted_Y = slope * X + intercept`
- Calculating the mean squared error (loss) between the predicted and actual `Y` values.
- Plotting the data points alongside the fitted regression line, with the resulting loss value displayed on the chart.