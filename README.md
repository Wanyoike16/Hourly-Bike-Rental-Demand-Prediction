# Hourly-Bike-Rental-Demand-Prediction
Forecasting Stable Urban Mobility with Weather &amp; Time Features
Bike-sharing systems have emerged as an essential element of urban mobility, offering a convenient, eco-friendly, and efficient transportation option. However, ensuring a stable supply of bikes throughout the city — especially during peak hours — remains a logistical challenge.

This project focuses on predicting the hourly demand for rental bikes using historical data, with the aim of helping urban planners and bike-sharing operators:

Reduce wait times for users

Optimize bike redistribution

Ensure a balanced and accessible system for the public

🎯 Objectives
Forecast the number of bikes rented per hour

Leverage weather, temporal, and seasonal features to improve predictions

Develop a regression model to support operational decision-making for rental services

🗃️ Dataset Description
The dataset includes records of hourly bike rental counts in an urban city, alongside detailed weather and date/time information.
Each row represents one hour of bike rental activity.

🔁 Workflow
1. Data Cleaning & Feature Engineering
Extracted time-based features (hour, day of week, season)

Created lag and rolling window features for time-series modeling

Normalized and handled missing weather data

2. Exploratory Data Analysis (EDA)
Visualized rental trends across hours, seasons, weather types

Examined correlation between bike count and environmental conditions

3. Model Building
Trained and compared several regression models including:

Linear Regression
Multiple Linear Regression
Regression with Neural Networks
Neural Networks

Selected the best model based on predictive accuracy and robustness

Tools & Technologies
Python: Pandas, NumPy, Matplotlib, Seaborn, tensorflow, sklearn
Modeling: Scikit-learn
Feature Engineering: Lag features, rolling statistics, datetime parsing
Evaluation: RMSE, MAE, R² Score
