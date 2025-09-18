# ✈️ Flight Fare Prediction

This project focuses on building a machine learning model that predicts flight ticket prices based on various features such as airline, route, duration, and departure/arrival times. The dataset was sourced from Kaggle and includes flights between March and June 2019.

## 📌 Problem Statement

Accurate flight fare prediction can benefit:
- **Travelers**: to make cost-effective travel decisions.
- **Airlines**: to adjust pricing strategies and stay competitive in the market.

We use supervised regression techniques to predict the fare of a flight given relevant features.

## 📊 Dataset

- Source: [Kaggle – Flight Fare Prediction](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)
- Training set: 10,683 records
- Test set: 2,671 records

## 🛠️ Workflow Overview

- **Data Inspection & Cleaning**: Checked for null values, removed inconsistencies
- **Exploratory Data Analysis (EDA)**: Analyzed distributions, relationships, and outliers
- **Feature Engineering**: Extracted duration, day/month from date/time columns, and processed route info
- **Encoding**: Handled categorical variables using Label Encoding
- **Model Building**: Trained multiple regression models
- **Model Selection**: Chose Random Forest Regressor based on performance
- **Hyperparameter Tuning**: Used GridSearchCV to fine-tune the model

## 📈 Results

- **Final Model**: Random Forest Regressor
- **R² Score**: 82% on test data
- The model demonstrates strong predictive power and is useful for fare forecasting tasks.

## 🧠 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook


