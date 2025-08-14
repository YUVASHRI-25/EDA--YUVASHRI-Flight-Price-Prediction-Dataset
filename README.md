✈️ Flight Fare Prediction – Data Science Project
📌 Overview

This repository contains datasets for a flight fare prediction project.
The training dataset (Data_Train (1).xlsx) contains historical flight booking information including airline, date of journey, source, destination, route, duration, total stops, and ticket prices.
The test dataset (Test_set.xlsx) contains similar details but without ticket prices — intended for model evaluation and prediction.

This project is useful for practicing data cleaning, feature engineering, exploratory data analysis (EDA), and regression modeling.

📂 Dataset Description
Files:

Data_Train (1).xlsx – Training dataset with ticket prices

Test_set.xlsx – Test dataset without ticket prices

Training Set Size: ~10,683 rows
Test Set Size: ~2,679 rows

🎯 Objectives

Possible goals for analysis:

Predict ticket prices based on available features

Identify most expensive and cheapest airline routes

Analyze the impact of travel time and number of stops on ticket prices

Study seasonal patterns in flight prices

Explore airline-specific pricing strategies

🛠️ Requirements

To run the analysis, install the following Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


🔍 Potential Analyses

Exploratory Data Analysis (EDA) – Visualize airline popularity, price distributions, and travel time trends

Feature Engineering – Extract day, month, and time components from dates

Predictive Modeling – Train regression models (Linear Regression, Random Forest, XGBoost) to predict ticket prices

Outlier Detection – Identify unusually high or low prices compared to similar flights

