Heart Disease Prediction Using Classical Machine Learning Algorithms
📘 Overview

This project aims to predict the likelihood of heart disease in patients using various classical machine learning algorithms. The goal is to compare different models’ performance and determine which provides the highest prediction accuracy.

The project utilizes a heart disease dataset containing medical attributes such as age, cholesterol level, blood pressure, and more. By applying data preprocessing, visualization, and model evaluation, this project helps demonstrate how machine learning can assist in early heart disease diagnosis.

⚙️ Algorithms Used

The following 7 machine learning models are implemented and compared:

K-Nearest Neighbors (KNN)

Logistic Regression

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier

Naive Bayes

XGBoost Classifier

📊 Dataset

Dataset Source: UCI Heart Disease Dataset
 (or your custom dataset link)

Features: Includes patient information such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Serum Cholesterol

Fasting Blood Sugar

Maximum Heart Rate Achieved

Exercise Induced Angina

And others

Target Variable:

1 → Presence of heart disease

0 → Absence of heart disease

🧠 Project Workflow

Data Collection: Import and explore the dataset.

Data Preprocessing: Handle missing values, encode categorical data, and scale features.

Exploratory Data Analysis (EDA): Visualize data distributions and feature correlations.

Model Training: Train all seven algorithms.

Model Evaluation: Compare accuracy, precision, recall, F1-score, and ROC-AUC.

Model Selection: Identify the best-performing algorithm for heart disease prediction.

🛠️ Technologies Used

Python

NumPy, Pandas – data handling

Matplotlib, Seaborn – data visualization

Scikit-learn – machine learning models

XGBoost – gradient boosting implementation
