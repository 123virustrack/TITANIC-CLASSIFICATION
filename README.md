# TITANIC-CLASSIFICATION
This project aims to predict passenger survival on the Titanic using machine learning techniques. By exploring and analyzing the Titanic dataset, we uncover key insights into the factors that influenced survival rates. The project includes data preprocessing, feature engineering, model training, and visualization of survival trends.

Project Overview
1. Data Exploration and Cleaning
Loaded the Titanic dataset and examined its structure with df.info().
Identified and addressed missing values, particularly in the 'Age' and 'Embarked' columns.
Removed irrelevant features such as 'PassengerId', 'Name', 'Ticket', and 'Cabin'.
2. Feature Engineering
Converted categorical variables 'Sex' and 'Embarked' into numerical representations using one-hot encoding.
Imputed missing 'Age' values using KNN imputation, leveraging information from similar passengers.
3. Model Training and Evaluation
Trained a Random Forest Classifier to predict survival based on the preprocessed features.
Split the dataset into training and testing sets to evaluate model performance.
Achieved an accuracy of [mention the accuracy score you obtained] on the test set.
4. Visualizing Survival Trends
Created bar charts and pie charts to illustrate the relationship between survival and key features such as sex.
Uncovered significant differences in survival rates between male and female passengers.
5. Feature Importance Analysis
Analyzed the importance of different features in the Random Forest model's predictions.
Identified 'Age', 'Fare', and 'Sex' as the most influential factors affecting survival.  
