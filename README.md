# PRODIGY_ML_01 - Linear Regression Model for House Price Prediction

This repository contains the code for implementing a **Linear Regression** model to predict house prices based on features such as square footage, number of bedrooms, and bathrooms, as part of my **Prodigy InfoTech** internship.

## Task Overview

The objective of this task was to predict house prices using the **Kaggle House Prices** dataset. The model was implemented using **Linear Regression**, with a focus on:

- Data preprocessing
- Feature selection
- Model evaluation

## Highlights

- **Data Preprocessing**: Cleaned the dataset, handled missing values, and scaled the features for consistency.
- **Model**: Built and trained a **Linear Regression** model to predict house prices.
- **Performance Metrics**: Evaluated the model using:
  - **Mean Squared Error (MSE)**
  - **R-squared (R²)**
- **Visualization**: Used **scatter plots** to compare actual vs predicted house prices.

## Requirements

To run the project, make sure to have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Elysian0987/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Download the **Kaggle House Prices dataset** (`train.csv`) from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/dataimport).
2. Place the dataset (`train.csv`) in the root directory of the project.
3. Run the **linear_regression_model.py** script:

   ```bash
   python linear_regression_model.py
   ```

This will:

- Train the Linear Regression model on the data.
- Output the **Mean Squared Error** and **R-squared** values.
- Display visualizations comparing **actual** vs **predicted** prices.

## Results

The model's performance will be displayed through evaluation metrics, and visual plots will showcase the relationship between predicted and actual house prices.
