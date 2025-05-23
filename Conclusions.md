# 📌 Conclusions

## 🧠 Project Summary

This project involved developing a regression model to predict the market price of residential houses based on several key features. The goal was to assist a Real Estate Investment Trust in identifying the most impactful variables when valuing residential properties. The dataset included information such as square footage, number of bedrooms, presence of a waterfront view, and more.

## 🔍 Key Findings

### 1. **Model Performance (Linear Ridge Regression)**
- Using a Ridge regression model with a regularization parameter (`alpha = 0.1`), we achieved an **R² score of 0.6479** on the test dataset.
- This indicates that approximately **64.8% of the variability in house prices** can be explained by the selected features using this linear approach.

### 2. **Polynomial Feature Transformation**
- By applying a **second-order polynomial transformation** to the features and training the Ridge model again:
  - We improved the model’s performance with an **R² score of 0.7003**.
- This suggests that **non-linear relationships** exist between the predictors and the price, and modeling these interactions helps capture more variance in the target variable.

### 3. **Feature Importance & Intuition**
- Some features, such as:
  - `sqft_living`, `grade`, and `bathrooms`, had a strong influence on the final price prediction.
  - The presence of a `waterfront` and the `view` also contributed significantly, highlighting the value placed on visual and locational appeal.

## ✅ Final Conclusion

- **Polynomial Ridge Regression (degree = 2)** proved to be more effective than simple Ridge Regression for this dataset.
- The combination of feature engineering (polynomial tran
