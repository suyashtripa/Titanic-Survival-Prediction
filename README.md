This repository showcases a machine learning project focused on predicting passenger survival on the Titanic. Using a dataset containing various passenger attributes, the project explores data preprocessing, model training, and evaluation for classification tasks.

Key Features:

Data Loading & Preprocessing: Handles missing values, converts categorical features using LabelEncoder, and scales numerical features with StandardScaler.
Exploratory Data Analysis (EDA): Initial data exploration to understand the dataset's structure and feature distributions.
Machine Learning Models: Implements and compares two classification models:
Logistic Regression: A fundamental linear model for binary classification.
Support Vector Machine (SVM) with RBF Kernel: A powerful non-linear model capable of handling complex decision boundaries.
Model Evaluation: Utilizes various metrics such as accuracy score, confusion matrix, and classification report to assess model performance.
Cross-Validation: Employs k-fold cross-validation to provide a more robust estimate of the model's generalization capabilities.
Dataset:

The project uses the classic Titanic dataset, which includes information like passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and port of embarkation.

Usage:

Clone this repository and follow the Jupyter Notebook to replicate the analysis and model training steps.

Dependencies:

numpy
pandas
seaborn
matplotlib
scikit-learn
