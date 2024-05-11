## Overview
The "results.csv" file consists of performance metrics for various regression models used to predict outcomes based on input features. The primary goal of this output file is to facilitate the selection of the model with the least Mean Squared Error (MSE), indicating the best predictive accuracy among the tested models.

### File Details
- **Filename**: results.csv
- **Format**: CSV
- **Size**: 9 rows × 5 columns

### Columns
1. **Model**: The name of the regression model used (e.g., Decision Tree, XGBoost).
2. **Mean Squared Error**: The mean squared error of the model's predictions, numeric. Lower values indicate better performance.
3. **R-squared**: The coefficient of determination, numeric. Higher values indicate better model fit.
4. **Average Error**: The average error of the model's predictions, numeric.
5. **Median Error**: The median error of the model's predictions, numeric.

## Purpose
This dataset is specifically curated to assess and compare the predictive performance of various regression models. By examining metrics like Mean Squared Error, R-squared, Average Error, and Median Error, one can determine which model yields the most accurate predictions with respect to the data it was trained on. The primary use of this dataset is to select the regression model that minimizes the MSE, as it directly corresponds to the accuracy and effectiveness of the model in practical applications.

## Usage
- **Model Selection**: Identify the model with the lowest MSE to ensure the highest predictive accuracy.
- **Model Evaluation**: Compare R-squared, Average Error, and Median Error across models to evaluate their overall performance.
