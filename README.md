Heart Disease Prediction using XGBoost
📌 Overview

This project predicts the likelihood of heart disease based on patient health data using the XGBoost machine learning algorithm.
It uses a dataset containing various medical attributes such as age, blood pressure, cholesterol level, and other cardiovascular indicators.

⚙️ Features

Data preprocessing and cleaning.
Exploratory Data Analysis (EDA) with visualizations.
Model training using XGBoost Classifier.
Model evaluation using accuracy, precision, recall, and F1-score.
Saves the trained model for future predictions.

📂 Dataset

The dataset contains medical records with features such as:
age – Age of the patient.
sex – Gender of the patient.
cp – Chest pain type.
trestbps – Resting blood pressure.
chol – Serum cholesterol level.
thalach – Maximum heart rate achieved.
exang – Exercise induced angina.
oldpeak – ST depression induced by exercise.
...and other relevant medical features.

💾 Saving the Model

The trained model is saved as xgboost_heart_model.pkl and can be loaded later for predictions without retraining.

