# Mental_Health_and_Social_Media_Balance
Project Overview

This project analyzes the relationship between social media usage and mental health indicators such as stress, sleep quality, screen time, and digital detox days.
The goal is to predict the Happiness Index of individuals based on their online habits and lifestyle factors using machine learning techniques.

🎯 Objective

To build a predictive model that estimates the Happiness Index from features such as:

Screen Time (hours/day)

Stress Level

Sleep Quality

Digital Detox Days

Online Activity Patterns

This helps understand how different aspects of digital behavior influence mental well-being.

📊 Dataset

The dataset contains information about users’ social media habits and mental health indicators.

Column Name	Description
User_ID	Unique identifier for each user
Screen_Time	Average hours spent online per day
Stress_Level	Self-reported stress score (1–10)
Sleep_Quality	Sleep rating (1–10)
Digital_Detox_Days	Number of days per week spent offline
Happiness_Index	Target variable (1–10 scale)

(If your dataset is from Kaggle or another source, add the link here.)

🧹 Data Preprocessing

Steps performed:

Handled missing values

Converted categorical variables into numerical format (if any)

Normalized numerical columns

Visualized correlations between features and the Happiness Index

🧠 Model Building

Several regression algorithms were tested to predict the Happiness Index:

Linear Regression

Random Forest Regressor

XGBoost Regressor

The model performance was evaluated using:

RMSE (Root Mean Square Error)

R² Score
