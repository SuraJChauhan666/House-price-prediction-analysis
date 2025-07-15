#🏡# House Price Prediction – Bengaluru Housing Data
📌 Overview
This machine learning project focuses on predicting house prices in Bengaluru using data-driven techniques. By performing exploratory data analysis (EDA), cleaning, feature engineering, and building a Multiple Linear Regression model, the goal is to estimate property prices with measurable accuracy.

📂 Dataset
Name: Bengaluru_House_Data.csv

Source: Kaggle / Open real estate datasets

Features:

location, size, total_sqft, bath, balcony, price, area_type, availability, etc.

🧪 Technologies Used
Tool/Library	Purpose
Python	Programming language used
Pandas, NumPy	Data cleaning and manipulation
Matplotlib, Seaborn	Data visualization & EDA
scikit-learn	ML model building (Linear Regression)
Google Colab	Development environment

🧹 Data Preprocessing Highlights
Converted complex string values in availability to quarters (Q1–Q4)

Cleaned and standardized total_sqft using regex and average values

Extracted numeric values from size and separated room type

Reduced dimensionality in location by grouping rare values under "other"

Removed outliers in bath, total_sqft, and price columns using IQR filtering

Dropped columns with excessive null values (e.g., society)

📈 Model Used
Multiple Linear Regression

Train-test split: 80/20

Model trained using LinearRegression() from scikit-learn

Performance Metric:

RMSE (Root Mean Squared Error) calculated

Coefficients and intercepts extracted

✅ Final Results
Model Accuracy: Evaluated using RMSE

Predictions: Compared predicted prices vs. actual test prices

Insights show that location and total_sqft are strong price indicators.

