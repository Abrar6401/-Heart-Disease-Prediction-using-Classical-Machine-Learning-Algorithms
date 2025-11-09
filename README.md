Heart Disease Prediction Using Classical Machine Learning Algorithms
📘 Overview

This project focuses on predicting the likelihood of heart disease in individuals using several classical machine learning algorithms.
The aim is to compare the performance of multiple models and determine which provides the best prediction accuracy.

By analyzing medical features such as age, cholesterol, blood pressure, and heart rate, the project demonstrates how data-driven methods can support early diagnosis and prevention of heart disease.

⚙️ Algorithms Used

The following seven machine learning algorithms were implemented and compared:

K-Nearest Neighbors (KNN)

Logistic Regression

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier

Naive Bayes Classifier

XGBoost Classifier

📊 Dataset

Source: Kaggle - Heart Disease Dataset

(You can replace this link with your specific Kaggle dataset URL.)

Description: The dataset includes various health-related features that help in identifying the presence or absence of heart disease.

Features

Age – Age of the individual

Sex – Male or Female

Chest Pain Type (cp) – Type of chest pain experienced

Resting Blood Pressure (trestbps)

Serum Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG (restecg)

Maximum Heart Rate Achieved (thalach)

Exercise Induced Angina (exang)

Oldpeak – ST depression induced by exercise

Slope, Ca, Thal – Other heart-related indicators

Target – 1 = Heart disease, 0 = No heart disease

🧠 Project Workflow

Data Collection: Import and explore the dataset from Kaggle.

Data Preprocessing: Handle missing values, encode categorical variables, and normalize data.

Exploratory Data Analysis (EDA): Visualize distributions, correlations, and feature importance.

Model Training: Train seven classical ML algorithms.

Model Evaluation: Compare models using accuracy, precision, recall, F1-score, and ROC-AUC.

Model Selection: Identify the model with the best overall performance.

🛠️ Technologies Used

Language: Python 🐍

Libraries:

NumPy and Pandas – Data manipulation

Matplotlib and Seaborn – Data visualization

Scikit-learn – ML algorithms and metrics

XGBoost – Gradient boosting

Jupyter Notebook – Interactive development
