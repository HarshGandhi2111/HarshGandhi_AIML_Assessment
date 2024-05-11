# Advanced Predictive Analysis for Sourcing Cost Optimization
AI&amp;ML Assessment for A.P. Moller Maersk Recruitment round.

## Project Overview
This project applies advanced machine learning techniques to optimize sourcing costs in a manufacturing context. The primary goal is to build and evaluate predictive models that can accurately forecast sourcing costs based on various product-related features.

## Repository Contents

### [Directory: Notebook]([URL](https://github.com/HarshGandhi2111/HarshGandhi_AIML_Assessment/tree/main/Notebook))
- **HarshGandhi_AIML_Assessment.ipynb**: A detailed Jupyter Notebook that outlines the entire process from data loading, exploratory analysis, model training, and evaluation. The notebook includes comprehensive visualizations and insights into sourcing cost trends and efficiencies.

### Directory: Datasets
- **DS_ML Coding Challenge Dataset (1).xlsx - Training Dataset.csv**: This dataset contains detailed sourcing information used for training predictive models.
- **results.csv**: This dataset contains the performance metrics of different regression models, facilitating the selection of the model with the least mean squared error (MSE).

### Models
- **catboost_model.joblib**: A serialized CatBoost regression model optimized for predicting sourcing costs. This model is chosen based on its performance metrics as detailed in the `results.csv`.

## Key Implementations
1. **Exploratory Data Analysis (EDA)**: Analysis of trends, efficiencies, and costs related to product sourcing.
2. **Modeling**: Evaluation of various regression models (Decision Tree, XGBoost, LightGBM, CatBoost, Linear Regression) to identify the one with the lowest MSE.
3. **CatBoost Model**: Implementation and serialization of the CatBoost model, known for handling categorical data efficiently and providing high accuracy.

## Usage
To use the models or replicate the analysis:
1. Clone the repository.
2. Install the necessary Python packages.
3. Run the Jupyter notebook for detailed steps and explanations.

### Loading the CatBoost Model
```python
from joblib import load
model = load('catboost_model.joblib')
