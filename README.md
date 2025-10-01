# Demand-Forecasting-Sales-Prediction-with-Minimal

<img width="756" height="562" alt="image" src="https://github.com/user-attachments/assets/5d5ab04d-9616-4d5b-beec-9f420781fe3a" />

Accurately predicting product demand is one of the most critical tasks for businesses in retail, logistics, and supply chain management. This notebook demonstrates how to build a sales forecasting model using a minimal set of features, focusing on temporal and categorical data, while still achieving competitive results.

🚀 Key Highlights
Feature Engineering: Extracted time-based features such as month, day of week, week of year, and indicators for weekends and month boundaries.
Handling Categorical Variables: One-hot encoding applied for store, item, and weekday information to enhance model performance.
Modeling Approach: LightGBM, a high-performance gradient boosting framework, is used for regression on log-transformed sales data.
Evaluation Metric: SMAPE (Symmetric Mean Absolute Percentage Error) is employed to measure prediction accuracy.
Minimalistic Design: Focused on keeping the feature set small while capturing the most predictive signals, making the model fast and easy to interpret.
🔍 Notebook Goals
Show how to efficiently preprocess and engineer temporal features for demand forecasting.
Train a LightGBM regression model with minimal features.
Evaluate model performance using SMAPE and interpret results.
Provide a clean, easy-to-follow pipeline for beginners and intermediate practitioners.
Whether you are a data science enthusiast or a professional working on retail sales forecasting, this notebook provides a concise, practical, and reproducible approach to predicting product demand with minimal complexity.
