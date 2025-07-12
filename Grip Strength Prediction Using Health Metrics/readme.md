    Predicting Grip Strength from Physical & Health Metrics

A Machine learning project that uses regression models to predict grip strength based on various physical and health-related parameters.

    Project Overview

Grip strength is a powerful indicator of an individual’s overall health and functional fitness. This project explores how physical and physiological features—such as age, weight, height, BMI, and gender—can be used to predict grip strength using machine learning models.

    🎯 Objective

Predict the gripForce (grip strength) of individuals using regression techniques.

Evaluate multiple models and select the most accurate one.

Interpret which physical metrics contribute the most to grip strength prediction.

    📂 Dataset

Source: Physical and Health Metrics.csv

Rows: ~3000+

Features: Age, Gender, Height, Weight, BMI, Fat %, Muscle %, Basal Metabolic Rate, etc.

Target Variable: gripForce

    🔄 Preprocessing Steps

Removed irrelevant columns.

Confirmed absence of missing values.

Encoded categorical values (gender was already numeric).

Normalized features using StandardScaler.

Split into training and test sets.

    🤖 Models Used

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Support Vector Regressor

Gradient Boosting Regressor

📌 Best Model: Gradient Boosting Regressor

📌 Tuned R² Score: ~0.79 after hyperparameter optimization

    🧪 Techniques Applied
Model comparison using R², MAE, RMSE

5-fold Cross-validation

Hyperparameter tuning with GridSearchCV

Feature importance analysis

Actual vs. Predicted visual comparison

    📊 Key Findings
Grip strength can be predicted with a high degree of accuracy using physical metrics.

The most influential features include muscle mass, fat percentage, and basal metabolic rate.

Gradient Boosting performed best in balancing error metrics and generalization.

    🔍 Why Grip Strength Matters
Research shows that grip strength is a reliable biomarker of:

Overall muscle strength

Longevity and aging

Cardiovascular health

Risk of chronic disease

Studies:

Grip strength as an indicator of health status

Handgrip strength predicts mortality

    📁 Repository Structure
Copy
Edit
📦 capstone_project_grip_strength
│

├── 📔 Grip Strength Prediction Using Health Metrics.ipynb

├── 📄 Physical and Health Metrics.csv

└── 📄 README.md

    🚀 Future Scope
Add deep learning models (like DNNs) for improved predictions.

Explore gender-specific or age-specific model tuning.

Deploy as a web app for fitness assessments.

    🛠️ Technologies Used
Python, Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

Jupyter Notebook

    👤 Author: Arun Hariharan

📧 Email: arunhariharan2047@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/iarunhariharan/


