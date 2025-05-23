🏠 Housing Price Prediction Project – Final Assignment
Hi! I worked on this project as part of my final assignment in the course. I took on the role of a Data Analyst for a Real Estate Investment Trust that’s planning to invest in residential housing. My task was to predict house prices using different features like square footage, number of bedrooms, location, and more.

🛠️ Tools and Libraries I Used
Python (Jupyter Notebook)

Pandas, NumPy – for data handling

Seaborn, Matplotlib – for data visualization

Scikit-learn – for machine learning models

Statsmodels – for simple linear regression

✅ What I Did
Cleaned the dataset and checked for missing values.

Explored the data using charts like boxplots and value counts.

Built a Linear Regression model and calculated R².

Used Ridge Regression with regularization.

Applied a 2nd-degree Polynomial Transformation to improve the model.

Compared performance on training vs. test data using R² score.

📊 Final Model Results
Ridge Regression (linear features) → R² = 0.648

Polynomial Ridge Regression (2nd order) → R² = 0.700

This shows that adding polynomial features helps the model fit better.

📁 Project Structure
bash
Copy
Edit
final_project/
├── final_notebook.ipynb         # All my code and answers
├── screenshots/                 # Screenshots of results
├── README.md                    # This file
└── conclusions.md               # My takeaways from the project
📌 How to Run the Notebook
Make sure you install the necessary libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook final_notebook.ipynb
