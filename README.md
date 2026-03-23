# House-Price-Prediction
House Price Prediction Using Linear Regression

# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting house prices using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and model building using Linear Regression.

The goal is to analyze various factors such as property type, size, furnishing status, and location to accurately estimate house prices.



## 🎯 Objectives

* Perform data cleaning and preprocessing
* Analyze relationships between features and house prices
* Build a predictive model using Linear Regression
* Evaluate model performance using multiple metrics
* Visualize insights for better understanding



## 📂 Dataset Information

The dataset contains real estate information with the following key features:

* Price_in_Lakhs (Target Variable)
* Size_in_SqFt
* BHK (Number of Bedrooms)
* Property_Type
* Furnished_Status
* City
* Parking_Space
* Security
* Public_Transport_Accessibility
* Availability_Status



## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn



## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed unnecessary columns (ID, Locality)
* Handled categorical variables using Ordinal Encoding
* Converted text data to lowercase
* Checked for missing values and data types

### 2️⃣ Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Feature relationship analysis using plots

### 3️⃣ Model Building

* Used Linear Regression model
* Data split into training and testing sets
* Feature transformation using DictVectorizer

### 4️⃣ Model Evaluation

The model was evaluated using:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* R² Score



## 📊 Visualizations

### 🔹 1. Actual vs Predicted Prices

This plot compares the actual house prices with the predicted values from the model.
Points close to the diagonal line indicate accurate predictions.



### 🔹 2. Residual Plot

This plot shows the difference between actual and predicted values.
A random distribution of residuals indicates a well-performing model.



### 🔹 3. City-wise Price Distribution

A boxplot visualization that shows how house prices vary across different cities.
It highlights median prices, spread, and outliers for each city.



### 🔹 4. BHK vs Price

This visualization shows how the number of bedrooms (BHK) affects house prices.
Higher BHK values generally correspond to higher prices.



## 📈 Model Performance

The Linear Regression model provides a good baseline for price prediction.
Performance metrics help evaluate prediction accuracy and error margins.



## 🚀 Key Insights

* House size and BHK are strong indicators of price
* Location (City) significantly impacts property value
* Furnishing and amenities influence pricing
* The model shows a positive correlation between features and target



## 📌 Conclusion

This project demonstrates how machine learning can be applied to real estate data to predict house prices and extract meaningful insights.





