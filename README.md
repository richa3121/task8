# task8
Bank Marketing Subscription Prediction (Decision Tree)

Project Overview

The goal is to build a predictive model using a Decision Tree Classifier to determine if a customer will subscribe to a term deposit based on the UCI Bank Marketing Dataset.

Task Objectives

Identify features relevant to customer subscription behavior.

Clean inconsistent text values and handle missing data.

Encode categorical features for machine learning compatibility.

Train a Decision Tree and optimize it using max_depth to prevent overfitting.

Analyze model performance and interpret decision rules.

Tools & Libraries Used

Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib

Dataset: UCI Bank Marketing Dataset

Implementation Steps

Data Loading: Extracted the dataset from the archive and loaded bank-full.csv.

Preprocessing: Cleaned "unknown" values and applied LabelEncoder to categorical columns.

Model Training: Split the data (80/20) and trained a DecisionTreeClassifier.

Visualization: Plotted the tree to understand the branching logic.

Evaluation: A classification report and compared accuracy scores.

Evaluation Report

Training Accuracy: ~90%

Testing Accuracy: ~89%

Key Rules Extracted:

Rule 1: If the last contact duration is less than a specific threshold, the subscription likelihood is very low.

Rule 2: A "success" in poutcome (previous marketing campaign) is a strong predictor of a new subscription.

Rule 3: Customer age and balance act as secondary filters in determining interest
