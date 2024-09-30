Overview
Parkinson's disease is a progressive neurological disorder without a definitive diagnostic method. This project leverages machine learning techniques to predict its presence in patients based on biomedical voice measurements.

Features
Data Preprocessing: Cleaning and preparing data for analysis.
Feature Selection: Using correlation analysis and chi-square tests.
Handling Class Imbalance: Applied RandomOverSampler.
Models Used
Logistic Regression
XGBoost
Support Vector Machine (SVM)
Dependencies
numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost, imbalanced-learn
Usage
Load the dataset (parkinson_disease.csv).
Preprocess data.
Perform feature selection.
Handle class imbalance.
Train and evaluate models.
Visualize results.
Results
The best-performing model achieves 75-80% accuracy in predicting Parkinson's disease.

Conclusion
Machine learning shows promise in assisting Parkinson's diagnosis, demonstrating its value in addressing real-world medical challenges.
