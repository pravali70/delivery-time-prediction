# 🚚 Delivery Time Prediction - Mini Project
👋 Welcome to this machine learning project on predicting food delivery time using regression models!

## 📝 Project Overview
In this project, we explore a real-world dataset focused on food delivery logistics. The dataset includes various features that impact delivery time, such as:

Delivery Person’s Age and Ratings

Restaurant and Delivery Location Coordinates

Order Details (e.g., type of order, vehicle used)

Distance Metrics

Our objective is to build an end-to-end machine learning pipeline—from data preprocessing and visualization to model development and evaluation—to predict delivery time (in minutes).

## 🎯 Objective
The goal is to build and compare regression models that can accurately predict delivery time based on multiple human, geographic, and service-related factors.

These predictions help:

Food delivery platforms optimize route planning

Enhance customer satisfaction with accurate ETA estimates

Reduce operational delays and inefficiencies

Improve resource allocation (e.g., assigning delivery partners)

## 🤖 Models Evaluated
The following regression models are implemented and compared:

Linear Regression

Polynomial Regression

Support Vector Regression (SVR)

Random Forest Regressor

Tuned Random Forest Regressor

XGBoost Regressor

Each model is evaluated for its ability to predict continuous delivery durations accurately.

## 📊 Evaluation Metrics
We use the following regression metrics to assess performance:

MAE (Mean Absolute Error) – Measures the average absolute prediction error

MSE (Mean Squared Error) – Penalizes larger errors

RMSE (Root Mean Squared Error) – Indicates overall model accuracy in the same unit (minutes)

These metrics help us understand how close the predicted times are to the actual delivery durations.

## 🧰 Tools & Libraries
This project is implemented using Python, with the help of the following libraries:

pandas – Data loading and transformation

numpy – Numerical computations

matplotlib & seaborn – Visualization and EDA

scikit-learn – Regression models, preprocessing, and evaluation

xgboost – Gradient boosting for improved accuracy

scipy – Hyperparameter tuning (e.g., for Random Forest)

## ✅ Outcome
By training and evaluating multiple models, we aim to:

Select the best-performing regression algorithm for delivery time prediction

Identify key influencing features such as distance, order type, and delivery person’s rating

Offer actionable insights to streamline delivery operations and enhance overall customer experience

💡 Thanks for exploring this project! We hope it showcases how machine learning can power real-time logistics and smarter delivery systems in the food tech industry.
