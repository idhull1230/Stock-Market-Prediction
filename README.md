# Stock-Market-Prediction
Python Code for Idris' Stock Market Prediction

This repository contains a complete Google Colab workflow for predicting stock price direction using a user-uploaded CSV dataset. The notebook covers the full pipeline—from exploratory data analysis and visualization to feature engineering, model training, and evaluation,using widely adopted machine learning libraries.
The workflow supports flexible CSV inputs, performs robust date parsing across common formats, and engineers calendar-based features such as quarter-end indicators. It generates descriptive statistics, distribution plots, boxplots, correlation heatmaps, and yearly aggregated visualizations to support data understanding before modeling.
Multiple classification models are trained and compared, including Logistic Regression, Support Vector Machines, and XGBoost, with performance evaluated using ROC-AUC and confusion matrices. Feature scaling, stratified train-validation splitting, and target construction based on next-day price movement are handled explicitly to ensure reproducibility and statistical soundness.

This project is well-suited for:
-Financial data analysis and time-series feature engineering
-Binary classification of market direction
-Model comparison and evaluation in a Colab environment
-Educational demonstrations of applied machine learning on stock data
