# PRODIGY_DS_02
# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

Welcome to my Titanic dataset analysis project! This repository showcases my approach to data cleaning and exploratory data analysis (EDA) using the famous Titanic dataset from Kaggle.

## Project Overview

In this project, I analyze the Titanic dataset to gain insights into passenger survival patterns. The goal is to understand the relationships between various features and the likelihood of survival, using techniques like data cleaning, feature engineering, and data visualization. 

Key tasks in this project:
Data cleaning: Handling missing values, removing duplicates, and handling outliers.
Exploratory Data Analysis (EDA): Visualizing the distribution of features and uncovering trends in the data.
Feature engineering: Creating new features to enhance predictive analysis.
Machine learning : Using the cleaned dataset to build a machine learning model to predict survival.

## Steps Involved

1. Data Loading:-
    Load the Titanic dataset from Kaggle.
    Inspect the first few rows to understand the structure.

2. Data Cleaning:-
    Handle missing values for columns like Age, Fare, and Embarked.
    Remove duplicate rows to ensure clean data.
    Identify and handle outliers (e.g., extreme values in Age and Fare columns).

3. Exploratory Data Analysis (EDA):-
    Univariate Analysis: Explore the distribution of features like Age, Fare, Pclass, and Survived.
    Bivariate Analysis: Explore relationships between key features, particularly focusing on survival rates (Survived column).
    Correlation Analysis: Visualize correlations between numerical variables using heatmaps.

4. Feature Engineering:-
    Family Size: Create a new feature by combining SibSp and Parch.
    Title Extraction: Derive titles (e.g., Mr, Mrs, Miss) from the Name column for better insights.

5. Modeling:-
    Machine Learning: Using Random Forest or Logistic Regression to predict survival based on the cleaned data.
    Model Evaluation: Evaluate the model using accuracy metrics such as precision, recall, and accuracy score.

## Libraries Used

 pandas: Data manipulation and analysis.
 numpy: Numerical operations.
 matplotlib: Data visualization.
 seaborn: Statistical data visualization.
 scikit-learn: Machine learning and model evaluation.

## Results

Through this analysis, we were able to uncover important patterns, such as:
 Gender: Female passengers had a higher chance of survival compared to males.
 Class: Passengers in first class were more likely to survive.
 Family Size: Larger families had a lower survival rate.

## Conclusion

This project helped me develop a better understanding of the Titanic dataset and reinforced my skills in data cleaning, EDA, and feature engineering. I also demonstrated how to create a machine learning model to predict survival rates based on the features.

Feel free to explore the notebooks and code to learn more about my approach!

 
