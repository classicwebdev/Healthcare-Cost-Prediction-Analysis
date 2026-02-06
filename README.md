🏥 Health Insurance Cost Prediction & Analysis📖

Introduction

This project analyzes a healthcare dataset of 1,338 patients to determine the primary drivers of medical insurance costs. By leveraging Multiple Linear Regression, we aim to provide insurance providers with a data-driven approach to risk assessment and premium pricing.

🎯 Project Objectives
Identify the strongest correlations between patient demographics (Age, BMI, Smoking status) and total medical charges.Preprocess and encode categorical medical data for machine learning compatibility.Build and evaluate a predictive model to forecast future healthcare expenditures.
🛠️ The Technical Workflow
Data Cleaning: Handled categorical variables using mapping (Smoker: Yes=1, No=0) and Label Encoding.
Exploratory Data Analysis (EDA): * Visualized cost distributions (found a right-skewed pattern).
Created a Correlation Heatmap to identify cost drivers.
Modeling: Implemented a Linear Regression model using a 80/20 train-test split.
Evaluation: Measured performance using R-squared ($R^2$) and Mean Absolute Error (MAE).

📊 Key Insights & Results

The "Smoking Gun": Smoking status is the most significant predictor of high medical costs, showing a 0.79 correlation.

Model Performance: The model achieved an R-squared score of 0.78, successfully explaining 78% of the variance in charges.
Prediction Error: The Mean Absolute Error was $4,260, providing a clear baseline for the model's accuracy.

🚀 Business Recommendations
Targeted Wellness: Insurance companies should prioritize smoking cessation programs as the most effective way to lower claims.
Risk-Based Pricing: Premiums should be heavily weighted toward smoking status and BMI to maintain a sustainable insurance pool.


