# Spark-Machine-Learning-Model-Comparison
This repository showcases my machine learning project focused on analyzing loan data to predict loan default likelihood. The project follows a structured approach to understand the financial behavior of borrowers using Spark ML lib.


Spark Machine Learning Model for Loan Data Analysis

This repository showcases my machine learning project focused on analyzing loan data to predict loan default likelihood. The project follows a structured approach to understand the financial behavior of borrowers using Spark MLlib.

Project Overview:

Executive Summary: Summarizes the project's scope and key findings.

Business Problem: Discusses the motivation behind the project, emphasizing the financial implications of predicting loan defaults.

Exploratory Data Analysis (EDA): Investigates numerical, categorical, and target variables to glean insights and prepare the data for modeling.

Feature Selection and Dimensionality Reduction:

PCA Analysis: Determines the optimal number of features.

Recursive Feature Elimination (RFE): Utilizes logistic regression, gradient boosting, and random forest to identify the most significant features.

Oversampling with SMOTE: Enhances the dataset to address class imbalance for robust model training.

Modelling Steps: Detailed steps of building and tuning models using Spark MLlib.

Model Performance Analysis: Evaluates the efficacy of different models based on various metrics.

Comments on Model Performance: Provides a critical assessment of the models, including insights and potential improvements.

This is an earlier learning project. The notebook and documentation are public, but the source
dataset is not included in this repository, so the analysis is not fully reproducible as checked in.
To run it with a compatible copy of the public lending dataset, place the CSV at
`data/loan_data.csv` and review the notebook's environment requirements.
