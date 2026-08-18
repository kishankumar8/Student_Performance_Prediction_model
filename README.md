# Student_Performance_Prediction_model .


In this repo I Evaluate  model that gives the prediction (using ANN ) of  Students by analyzing the past data of student .


# Student Performance Prediction using ANN

Based on your dataset (5000 students, with fields like study hours, attendance, parental education, internet access, extracurricular activities, subject-wise marks, final percentage, performance level, and pass/fail), here's a ready-to-use problem statement, objective, and 

# Problem Statement
Student academic performance is influenced by multiple factors — study habits, attendance, family background, access to resources, and participation in extracurricular activities. Educational institutions often lack a data-driven way to identify which factors most strongly affect a student's performance and to predict at-risk students early, making timely intervention difficult. There is a need to analyze student data to uncover performance patterns and build a system that can predict outcomes (Pass/Fail, Performance Level) based on measurable inputs.

# Objective
To analyze the relationship between student attributes (study hours, attendance, parental education, internet access, extracurricular activities) and academic performance (Math, Science, English, Final Percentage).
To identify the key factors that most significantly influence whether a student passes or fails.
To build a predictive model (classification/regression) that can estimate a student's Final Percentage, Performance Level, or Pass/Fail status using the available features.
To provide actionable insights that help teachers/parents identify at-risk students early and improve academic outcomes.
Solution
Approach — Data Analysis + Machine Learning pipeline:

Data Cleaning & Preprocessing – Handle missing values, encode categorical columns (Gender, Parental_Education, Internet_Access, Extracurricular_Activities) using label/one-hot encoding.
Exploratory Data Analysis (EDA) – Visualize correlations between Study_Hours, Attendance, Parental_Education, etc., vs. Final_Percentage/Pass_Fail (using bar charts, heatmaps, boxplots).
Feature Engineering – Derive features like average subject score, study-hour buckets, attendance bands.

# Model Building:
Classification model (Logistic Regression / Decision Tree / Random Forest) to predict Pass/Fail or Performance_Level.
Regression model (Linear Regression / Random Forest Regressor) to predict Final_Percentage.
Model Evaluation – Accuracy, Precision, Recall, F1-score (classification); RMSE, R² (regression).
Insight Generation – Identify top predictors (likely: Study_Hours_Per_Day, Attendance_Percentage) and generate a dashboard/report so educators can flag at-risk students early and recommend interventions (e.g., extra tutoring, attendance monitoring).
Outcome: A working model + visual report that predicts student performance and highlights the most impactful factors, enabling proactive academic support.

