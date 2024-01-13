# Titanic Survival Prediction Analysis

## Introduction

The sinking of the Titanic is a tragic event in history that occurred on April 15, 1912, during its maiden voyage. The collision with an iceberg resulted in the loss of 1,502 lives out of 2,224 passengers and crew. This disaster led to significant improvements in ship safety regulations. One major contributing factor to the high loss of life was the inadequate number of lifeboats on board. However, factors like gender, age, and class also played a role in determining who survived. In this analysis, we will delve into the demographics of the passengers and use machine learning techniques to predict their chances of survival.

## Goal

The primary objective of this analysis is to predict which passengers survived the Titanic sinking through the application of machine learning techniques. The process involves several stages, including data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling. The performance of the model will be assessed using the area under the receiver operating characteristic curve (AUC). Ultimately, the final model will be employed to make predictions on a test dataset provided by Kaggle.

## Methodology

### Tools and Libraries
- Programming Language: Python 3.8.5
- Data Cleaning and Preprocessing: Pandas
- Exploratory Data Analysis: Matplotlib and Seaborn
- Feature Engineering: Custom feature creation
- Predictive Modeling: Scikit-learn and XGBoost

### Data Preparation
The initial step involved cleaning and preprocessing the dataset to ensure data quality and consistency. Pandas was utilized for this task.

### Exploratory Data Analysis (EDA)
To gain insights into the data, exploratory data analysis was performed using Matplotlib and Seaborn. This phase included data visualization and statistical analysis to understand the passenger demographics and the factors influencing survival.

### Feature Engineering
Feature engineering was undertaken to generate new variables that could enhance the predictive power of the model. Creating meaningful features is crucial for the accuracy of machine learning models.

### Predictive Modeling
The predictive model was developed using Scikit-learn and XGBoost, a gradient boosting algorithm. The model was trained on the dataset with the goal of predicting passenger survival.

## Results

The XGBoost model achieved a commendable accuracy rate of 81%, demonstrating its predictive capability. However, there is room for further improvement through model enhancements and additional feature engineering. It is important to note that the predictions have not yet been submitted to Kaggle or assessed using the Kaggle scoring system. The analysis will be refined and optimized before final submission.

This README file serves as an overview of the Titanic Survival Prediction Analysis, detailing the objectives, methodology, and preliminary results. Further documentation and code can be found in the accompanying notebooks and scripts.

Feel free to reach out if you have any questions or require more detailed information about the analysis.

Author: Sondra