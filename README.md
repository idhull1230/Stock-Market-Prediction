# Stock-Market-Prediction

This repository contains a complete Google Colab workflow for predicting stock price direction using an uploaded CSV dataset provided by the user. The notebook covers the full pipeline, from exploratory data analysis and visualization to feature engineering, model training, and evaluation, using widely adopted machine learning libraries.
The workflow supports flexible CSV inputs, performs robust date parsing across common formats, and incorporates calendar-based features, including quarter-end indicators. It generates descriptive statistics, distribution plots, boxplots, correlation heatmaps, and yearly aggregated visualizations to support data understanding before modeling.
Multiple classification models are trained and compared, including Logistic Regression, Support Vector Machines, and XGBoost, with performance evaluated using ROC-AUC and confusion matrices. Feature scaling, stratified train-validation splitting, and target construction based on the next day's price movement are handled explicitly to ensure reproducibility and statistical soundness.

This project is well-suited for:
<br>-Financial data analysis and time-series feature engineering
<br>-Binary classification of market direction
<br>-Model comparison and evaluation in a Colab environment
<br>-Educational demonstrations of applied machine learning on stock data
