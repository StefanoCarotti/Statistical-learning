# Statistical Learning Project

Welcome to my Statistical Learning project! This project is divided into two main parts: a classification problem and a regression problem. Below you'll find an overview of the project, datasets used, methodologies applied, and how to reproduce the results.

## Project Overview

This project is a comprehensive exploration of statistical learning techniques using two datasets:

1. **Classification Dataset**: Titanic passengers, predicting survival.
2. **Regression Dataset**: Auto-mpg data, predicting miles per gallon (MPG).

Each part of the project involves data preprocessing, model implementation, tuning, and evaluation.

## Datasets

- **Titanic Dataset**: Includes information about Titanic passengers such as age, gender, ticket class, etc., with the target variable being whether the passenger survived.
- **Auto-MPG Dataset**: Contains data on various car models, with features like horsepower, weight, and model year, with the target variable being the MPG.

## Project Structure

- **Classification**: 
  - Data loading and preprocessing.
  - Classification models: Decision Trees, Random Forests, and XGBoost.
  - Hyperparameter tuning.
  - Model evaluation using accuracy, confusion matrices, and ROC curves.

- **Regression**: 
  - Data loading and preprocessing.
  - Regression models: Linear Regression, Random Forests, and Spline Regression.
  - Variable selection using backward selection and PCA.
  - Model evaluation using MSE, residual analysis, and ANOVA testing.

## Methodologies

- **Data Preprocessing**: Handling missing values, factor conversion, and data splitting.
- **Model Implementation**: Training models using `rpart`, `randomForest`, `xgboost`, and `mgcv` packages.
- **Hyperparameter Tuning**: Grid search for optimal model parameters.
- **Model Evaluation**: Using confusion matrices, accuracy scores, MSE, and visualizations like ROC curves and residual plots.

## Results

- The best classification model was achieved using a tuned Random Forest with an accuracy of `X%`.
- The regression model with the lowest MSE was a Spline Regression model with significant predictors, achieving an MSE of `Y`.

## Getting Started

### Prerequisites

- R (version 4.0 or later)
- RStudio (optional, but recommended)
- Required R packages: `ggplot2`, `dplyr`, `caret`, `randomForest`, `rpart`, `tidyverse`, `tidymodels`, `missForest`, `vip`, `mgcv`, `xgboost`, `ROSE`, `geosphere`, `rsample`.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Stat_Learning_project_CAROTTI.git
   cd Stat_Learning_project_CAROTTI
