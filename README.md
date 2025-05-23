
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

![1-Data Types](https://github.com/user-attachments/assets/9df955c7-74b5-4787-9ba4-3cf5ac1ed60b)
![2-Drop columns](https://github.com/user-attachments/assets/5e783232-c1c3-4f6c-b6a2-c71f8175c2d1)
![3 - Freq of floors](https://github.com/user-attachments/assets/2667e33b-61ff-4e23-9bf9-a6c926111edf)
![4-Box Plot](https://github.com/user-attachments/assets/4e7d71be-3b37-43f5-b726-bc8fdbffac56)
![5-Reg plot](https://github.com/user-attachments/assets/ebfeec13-d780-4f0b-bbe6-63bcaeeb830c)
![6-Linear Regression Model fit](https://github.com/user-attachments/assets/7e1367dd-9c8e-4b9a-9b15-63d5a2c8eb22)
![7-Features Linear Regression model fit](https://github.com/user-attachments/assets/1a2ac302-5be7-4ff7-99f1-7f5c98a5cd1c)
![8-Pipeline](https://github.com/user-attachments/assets/0417301a-6a82-45fb-b2f9-104e97e6efda)
![9-Ridge Model](https://github.com/user-attachments/assets/449ad414-f796-43b5-b7a3-b9a7a251dfb0)
![10-Polynomial Transform](https://github.com/user-attachments/assets/7f71090b-d2f1-4884-b1e9-782de3cde8a5)

## Author

This project was completed as part of a Data Science learning module.
