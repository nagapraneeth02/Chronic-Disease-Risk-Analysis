# Chronic-Disease-Risk-Analysis
**Overview**
This project uses advanced data analytics and machine learning to predict and understand chronic diseases such as hypertension, diabetes, heart disease, and chronic kidney disease (CKD). Starting with Kaggle’s Diabetes Prediction Dataset, the dataset was enriched with patient demographics, detailed medical history, laboratory test results, and lifestyle factors essential for healthcare predictive analysis.

**Purpose**
The goal is to develop multi-target classification models that provide actionable insights for early intervention strategies. By identifying key predictors and uncovering hidden trends, the project aims to support improved patient outcomes and drive strategic decision-making in healthcare.

**Methodology**
Data Collection & Enrichment: Augmented the original dataset by incorporating additional healthcare-relevant features.
Data Preprocessing: Performed cleaning, normalization, and encoding to ensure high-quality, consistent data.
Exploratory Data Analysis (EDA): Used statistical techniques and visualizations to identify trends and anomalies.
Feature Engineering & Selection: Applied Principal Component Analysis (PCA), Isolation Forest for anomaly detection, and Recursive Feature Elimination (RFE) to optimize the feature set.
Model Development: Trained multiple machine learning models (e.g., Random Forest, Gradient Boosting, XGBoost) using multi-output classification frameworks.
Evaluation: Assessed models using accuracy and F1 score metrics to determine performance across various chronic conditions.
**Key Findings**
PCA showed that the first principal component explains over 90% of the variance in blood pressure data.
Advanced models like XGBoost achieved high accuracy for predicting diabetes and hypertension.
Anomaly detection identified a 5% anomaly rate, pinpointing rare cases for further clinical review.
Insights gained offer significant potential for early intervention strategies and improved patient care.
