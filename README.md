Rock vs Mine Prediction using Machine Learning 🪨💣

A classification project to distinguish between rocks (R) and mines (M) using sonar signal data. This project demonstrates practical machine learning workflows including data preprocessing, model training, evaluation, and visualization.

🔍Project Overview

The goal of this project is to accurately classify sonar signals as either rocks or mines. The dataset contains numerical features representing sonar returns from objects underwater.

🛠️ Technologies & Libraries
Python
NumPy & Pandas – Data handling & preprocessing
Scikit-learn – Model training & evaluation
Matplotlib & Seaborn – Data visualization
Logistic Regression – Classification model
PCA (Principal Component Analysis) – Data visualization in 2D

📈 Workflow
Data Preprocessing – Cleaning, scaling, and preparing the dataset.
Train-Test Split – Stratified sampling to maintain class balance.
Model Training – Logistic Regression to classify rocks vs mines.
Evaluation – Accuracy score, confusion matrix, and ROC-AUC analysis.
Data Visualization – PCA plots to explore patterns and limitations.

🎯 Results
Accuracy: 76%
AUC Score: 0.74
PCA visualization revealed overlapping patterns between classes, highlighting limitations of linear models for this dataset.

📖 Reference / Inspiration

This project was inspired by https://www.youtube.com/watch?v=fiz1ORTBGpY&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6

💡 Key Learnings
Data preprocessing and feature scaling techniques
Building and evaluating classification models
Visualizing high-dimensional data with PCA
Understanding model performance metrics (accuracy, AUC, confusion matrix)

🏆 Conclusion
This project provided hands-on experience in machine learning workflows, data visualization, and predictive modeling using Python. It’s a great demonstration of applying ML techniques to real-world sonar signal data.
