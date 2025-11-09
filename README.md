poblem
This project focuses on analyzing a dataset containing health information such as age, blood pressure, heart rate, and other medical indicators of heart patients. The main goal is to build a machine learning model that can predict whether a person has heart disease or not. Since missing even one patient with heart disease could be dangerous, the project gives top priority to recall — meaning the model should correctly detect all people who actually have the disease, even if that means a few healthy people might be wrongly flagged.
Explanation of Objectives:

This project aims to analyze and model heart disease data systematically to build a reliable prediction system.

Explore the Dataset:
Understand the data by finding patterns, trends, and relationships among health factors like age, blood pressure, and cholesterol.

Perform Exploratory Data Analysis (EDA):
Study how each feature relates to the target (presence or absence of heart disease) to gain deeper insights.

Data Preprocessing:

Remove features that don’t contribute to prediction.

Handle missing values and outliers.

Encode categorical (non-numeric) data.

Transform skewed features for better model performance.

Model Building:

Create pipelines for models that need feature scaling.

Train and fine-tune classification algorithms like KNN, SVM, Decision Tree, and Random Forest.

Focus on achieving high recall to ensure that almost all heart disease cases are identified.

Model Evaluation and Comparison:
Use metrics such as precision, recall, and F1-score to measure how well each model performs and choose the best one.


step by step:

Step 1 | Import Libraries
Step 2 | Read Dataset

Step 3 | Dataset Overview
Step 3.1 | Dataset Basic Information
Step 3.2 | Summary Statistics for Numerical Variables
Step 3.3 | Summary Statistics for Categorical Variables
Step 4 | EDA
Step 4.1 | Univariate Analysis
Step 4.1.1 | Numerical Variables Univariate Analysis
Step 4.1.2 | Categorical Variables Univariate Analysis
Step 4.2 | Bivariate Analysis
Step 4.2.1 | Numerical Features vs Target
Step 4.2.2 | Categorical Features vs Target
Step 5 | Data Preprocessing
Step 5.1 | Irrelevant Features Removal
Step 5.2 | Missing Value Treatment
Step 5.3 | Outlier Treatment
Step 5.4 | Categorical Features Encoding
Step 5.5 | Feature Scaling
Step 5.6 | Transforming Skewed Features
Step 6 | Decision Tree Model Building
Step 6.1 | DT Base Model Definition
Step 6.2 | DT Hyperparameter Tuning
Step 6.3 | DT Model Evaluation
Step 7 | Random Forest Model Building
Step 7.1 | RF Base Model Definition
Step 7.2 | RF Hyperparameter Tuning
Step 7.3 | RF Model Evaluation
Step 8 | KNN Model Building
Step 8.1 | KNN Base Model Definition
Step 8.2 | KNN Hyperparameter Tuning
Step 8.3 | KNN Model Evaluation
Step 9 | SVM Model Building
Step 9.1 | SVM Base Model Definition
Step 9.2 | SVM Hyperparameter Tuning
Step 9.3 | SVM Model Evaluation
