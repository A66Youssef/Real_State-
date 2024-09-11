# UAE_Real_State
# Real Estate Rent Prediction

## Overview

This project focuses on predicting real estate rent prices using machine learning techniques. It leverages a dataset containing various features related to real estate listings to train and evaluate predictive models. The project demonstrates the application of exploratory data analysis, feature engineering, and advanced machine learning techniques such as XGBoost for regression.

## Project Structure

- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter notebooks with code for exploratory data analysis, feature engineering, and model building.
- `scripts/`: Python scripts for data preprocessing, model training, and evaluation.
- `README.md`: This file.

## Features

- **Data Exploration**: Analyzing the dataset to understand its structure, missing values, and feature distributions.
- **Data Visualization**: Visualizing key aspects of the dataset using bar plots, heatmaps, and sunburst charts.
- **Feature Engineering**: Encoding categorical variables and dropping irrelevant features to prepare the dataset for modeling.
- **Model Training**: Implementing and training XGBoost Regressor for predicting rent prices.
- **Hyperparameter Tuning**: Using GridSearchCV and RandomizedSearchCV to optimize model performance.
- **Cross-Validation**: Applying K-fold cross-validation to ensure the model's robustness and generalization.

## Getting Started

### Prerequisites

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- xgboost
- scikit-learn
- plotly

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn xgboost scikit-learn plotly
