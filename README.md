📊 PAP Prediction of Process Parameters using Data Analytics & Machine Learning

Industrial Internship Project – Coromandel International Limited

📌 Project Overview

This project focuses on predicting PAP (Phosphoric Acid Plant) process parameters using Data Analytics and Machine Learning techniques.

The objective was to analyze historical industrial process data, clean and preprocess the dataset, identify important relationships between process variables, build multiple machine learning models, and finally develop an accurate prediction model for process parameter estimation.

The project was carried out as part of my internship at Coromandel International Limited.

🎯 Project Objectives
Merge and preprocess industrial PAP datasets
Perform data cleaning and preprocessing
Handle missing values, duplicate records, and invalid values
Analyze statistical characteristics of process parameters
Perform Exploratory Data Analysis (EDA)
Identify correlations between process variables
Compare multiple Machine Learning algorithms
Predict process parameters with high accuracy
Explain model predictions using SHAP Explainability
🏭 Process Parameters Considered

The project focuses on predicting the following key process parameters:

Free Acid
Filter SpG
Slurry SpG
Product Acid
Return Acid
Solids %
Throughput
📂 Project Workflow
Industrial Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Data Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Correlation Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Building
        │
        ▼
Model Evaluation
        │
        ▼
Random Forest Optimization
        │
        ▼
SHAP Explainability
🧹 Data Cleaning Performed

✔ Combined two industrial datasets

✔ Converted object columns into numerical values

✔ Removed duplicate records

✔ Removed negative values

✔ Preserved valid negative values in Vacuum-related columns

✔ Handled missing values

✔ Counted outliers (without removing them)

✔ Prepared a clean dataset for Machine Learning

📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

Dataset Information
Statistical Summary
Missing Value Analysis
Duplicate Analysis
Distribution Analysis
Box Plot Analysis
Correlation Heatmap
Positive Correlation Analysis
Negative Correlation Analysis
Outlier Analysis
🤖 Machine Learning Models Implemented

The following regression models were developed and compared:

Linear Regression
Ridge Regression
Lasso Regression
Elastic Net Regression
Polynomial Regression
Decision Tree Regressor
Random Forest Regressor
🌲 Best Performing Model

Random Forest Regressor

Performance
Metric	Value
Training R² Score	0.9953
Testing R² Score	0.9703

The Random Forest model achieved the highest prediction accuracy among all evaluated models and demonstrated strong generalization on unseen data.

⚙ Hyperparameter Tuning

The following parameters were experimented with to improve model performance:

Number of Trees (n_estimators)
Maximum Tree Depth (max_depth)
Minimum Samples Split (min_samples_split)
Minimum Samples Leaf (min_samples_leaf)
Random State

These experiments helped identify the optimal model configuration.

🔍 Model Explainability (SHAP)

To improve model interpretability, SHAP (SHapley Additive exPlanations) was applied.

SHAP analysis helped to:

Identify the most influential process parameters
Measure each feature's contribution to predictions
Explain how each variable increases or decreases the predicted value
Improve confidence in the model's predictions
📈 Visualizations Included
Histogram
Box Plot
Correlation Heatmap
Feature Importance Plot
SHAP Summary Plot
Actual vs Predicted Plot
Residual Plot
🛠 Technologies Used
Programming
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SHAP
Development Environment
Jupyter Notebook
Visual Studio Code
Git
GitHub
