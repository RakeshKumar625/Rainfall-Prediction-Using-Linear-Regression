# Rainfall-Prediction-Using-Linear-Regression

Rainfall Prediction Project
📌 Overview

This project focuses on predicting daily rainfall (precipitation) using historical weather data from Austin, Texas. The dataset contains information such as temperature, humidity, dew point, wind speed, and other weather-related attributes.

The main objective of this project is to understand how different weather parameters influence rainfall and to build a Linear Regression model that can predict precipitation levels.

📂 Dataset

File Used: austin_weather.csv

The dataset contains daily weather records including:

Temperature (High, Low, Average)

Humidity (High, Low, Average)

Wind Speed

Dew Point

Visibility

Precipitation (Target Variable)

The target variable used for prediction is:
PrecipitationSumInches

🛠️ Steps Performed
1️⃣ Data Cleaning

Removed unnecessary columns like Date and Events

Replaced special symbols such as "T" and "-"

Converted all columns to numeric format

Handled missing values using mean imputation

2️⃣ Feature Engineering

To improve model performance, additional features were created:

Temperature Range

Humidity Range

Wind Range

Dew Point Difference

Interaction Feature (Humidity × Temperature)

These engineered features helped improve correlation with precipitation.

3️⃣ Exploratory Data Analysis

Generated correlation matrix

Visualized precipitation trends

Plotted regression trend graphs between precipitation and important weather attributes

Compared original features with engineered features

4️⃣ Model Building

Applied Linear Regression using sklearn

Performed train-test split (80-20)

Standardized features using StandardScaler

Evaluated model using:

Mean Squared Error (MSE)

R² Score

📊 Results

The model was able to capture the relationship between humidity-related features and rainfall.

Feature engineering improved correlation and overall model performance.

Humidity-based features showed stronger influence on precipitation compared to temperature and wind speed.

📈 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
