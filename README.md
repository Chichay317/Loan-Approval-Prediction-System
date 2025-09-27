# Loan-Approval-Prediction-System

This is a machine learning system that predicts whether a loan application will be approved or rejected. 
It uses data preprocessing techniques for cleaning and encoding categorical and numerical features, standardization for scaling, and multiple machine learning models for classification.

Features
1. Cleans and preprocesses the dataset (handles missing values, encodes categorical features, scales numerical features)
2. Converts categorical features into numerical values using Label Encoding
3. Standardizes features using StandardScaler to improve model performance
4. Trains and evaluates multiple models such as Random Forest, Decision Tree, K-Nearest Neighbors, and Naive Bayes
5. Provides accuracy score for model evaluation

How it Works
1. Prepares the dataset with applicant information such as Gender, Married status, Education, Income, Loan Amount, Credit History, etc.
2. Handles missing values using mean (for numerical features) and mode (for categorical features)
3. Encodes categorical features using LabelEncoder and ensures all features are numerical
4. Scales numerical features using StandardScaler
5. Trains multiple machine learning models on the processed data (Random Forest, Decision Tree, KNN, Naive Bayes)
6. Predicts loan approval for new, unseen applicants
7. Provides evaluation metrics to compare model performance and select the best one
