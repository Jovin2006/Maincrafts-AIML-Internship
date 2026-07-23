# Task 2 – Feature Engineering, Model Optimization & Performance Comparison

## Overview

This project was completed as part of my AI & Machine Learning Internship.

The objective of this task is to improve the performance of a house price prediction model by applying feature engineering techniques and comparing multiple machine learning regression models. The project includes data preprocessing, feature scaling, model training, performance evaluation, and selecting the best-performing model.

---

## Dataset

The project uses the California Housing dataset provided by the Scikit-learn library.

The dataset contains information about housing districts in California, including features such as median income, house age, average number of rooms, population, and geographical location. The target variable represents the median house value.

---

## Project Workflow

- Imported the required Python libraries
- Loaded and explored the dataset
- Performed data preprocessing
- Checked for missing and duplicate values
- Visualized the dataset using charts
- Applied feature scaling using StandardScaler
- Split the dataset into training and testing sets
- Trained multiple regression models
- Compared model performance using evaluation metrics
- Selected the best-performing model
- Saved the trained model using Joblib

---

## Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Decision Tree Regressor

---

## Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare the performance of each model and determine the best-performing regression algorithm.

---

## Files Included

- `task2_feature_engineering.ipynb` – Jupyter Notebook containing the complete implementation.
- `best_model.pkl` – Saved machine learning model.
- `report.pdf` – Project report.
- `requirements.txt` – List of required Python packages.
- `README.md` – Project documentation.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook
- Visual Studio Code

---

## Outcome

The project demonstrates the complete workflow of a regression-based machine learning solution, including preprocessing, feature engineering, model training, evaluation, comparison, and model saving. The best-performing model was selected based on evaluation metrics and stored for future use.
