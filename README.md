
# House Price Prediction Project

## Overview

This project is part of a data analysis and machine learning assignment where I worked as a Data Analyst for a Real Estate Investment Trust (REIT). The objective of this project is to analyze residential real estate data and predict housing prices based on several key attributes such as square footage, number of bedrooms, bathrooms, location, and other features.

Using Python and relevant data science libraries, I developed various models to understand the relationship between features and house prices, and evaluate the performance of linear and polynomial regression models, including Ridge regularization.

## Dataset

The dataset includes features of residential properties such as:

- `floors`: Number of floors in the house
- `waterfront`: Whether the house has a waterfront view
- `lat`: Latitude coordinate of the house
- `bedrooms`: Number of bedrooms
- `sqft_basement`: Size of the basement in square feet
- `view`: Quality of view from the house
- `bathrooms`: Number of bathrooms
- `sqft_living15`: Living area in 2015
- `sqft_above`: Square footage of house apart from basement
- `grade`: Overall grade given to the housing unit
- `sqft_living`: Total living area in square feet

The target variable is:

- `price`: Sale price of the house

## Objectives

- Load and explore the dataset.
- Perform data preprocessing.
- Visualize key relationships between variables.
- Create training and test datasets.
- Fit and evaluate linear and polynomial regression models.
- Apply Ridge regression to avoid overfitting.
- Assess the models using R² score.

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## Modeling Steps

1. **Data Preparation**: Selected relevant features and split the dataset into training and test sets.
2. **Linear Regression**: Built a baseline model using linear regression and evaluated its performance.
3. **Ridge Regression**: Implemented Ridge regression with a regularization parameter `alpha=0.1` and computed R² score.
4. **Polynomial Regression with Ridge**: Performed a second-order polynomial transformation and applied Ridge regression to evaluate improvement.

## Results

- **R² (Linear Ridge Regression)**: `0.6479`
- **R² (Polynomial Ridge Regression)**: `0.7002`

## Usage

To run this notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
Open the notebook and follow the code sections to execute each step.

## Project Screenshots

![10-Polynomial Transform](https://github.com/user-attachments/assets/7f71090b-d2f1-4884-b1e9-782de3cde8a5)


## Author

This project was completed as part of a Data Science learning module.
