# H1N1 Vaccination Status Prediction

## Overview

This project aims to predict individuals' H1N1 vaccination status using data collected from the National 2009 H1N1 Flu Survey. By analyzing various factors such as demographics, opinions, and health behaviors, the project seeks to understand the determinants of H1N1 vaccination uptake and develop predictive models to inform public health strategies.

## Business Problem

With the goal of improving vaccination rates and mitigating the spread of influenza viruses, public health organizations face the challenge of addressing vaccine hesitancy and refusal among the population. By identifying factors influencing vaccination decisions and developing predictive models, organizations can tailor interventions and communication campaigns to enhance vaccination acceptance and uptake.

## Data Understanding

The dataset utilized in this project originates from the NHFS National Flu Survey conducted in 2009. It captures responses from approximately 26,000 individuals regarding their vaccination status for both seasonal flu and H1N1 flu. Additionally, the survey collects information on demographic, behavioral, and health factors of the respondents.

For this particular project, the target variable selected is the H1N1 vaccination rate. All features available in the survey are used for analysis. 

- **training_set_features.csv:** This dataset contains the features (independent variables) for the training set. Each row represents a sample, and each column represents a feature.

- **training_set_labels.csv:** This dataset contains the corresponding labels (target variables) for the training set features. Each label indicates whether the respondent received the seasonal flu vaccine or the H1N1 flu vaccine.

- **test_set_features.csv:** This dataset contains the features similar to the training set features but without the corresponding labels. This dataset is used to make predictions after training the model.

## Code Overview

The provided code includes data preprocessing, exploratory data analysis (EDA), and implementation of machine learning models for predicting H1N1 vaccination status. It covers steps such as handling missing values, encoding categorical variables, feature selection based on correlation, scaling features, model training, evaluation, and hyperparameter tuning.

1. Importing necessary libraries
2. Reading in the feature and target data
3. Data preprocessing: handling missing values, dropping unnecessary columns, encoding categorical variables, etc.
4. Exploratory Data Analysis (EDA): visualizing data distributions, exploring relationships between variables, analyzing vaccination rates by different factors (e.g., age group, gender, opinions about the vaccine, doctor recommendation, awareness levels, etc.)
5. Model implementation: training various classification models (e.g., Decision Tree, Random Forest, K-Nearest Neighbors, Naive Bayes, Support Vector Machines, Logistic Regression) to predict H1N1 vaccination status
6. Model evaluation: assessing model performance using metrics such as accuracy, ROC-AUC score, F1 score, and generating classification reports
7. Generating visualizations to interpret model results and explore insights from the data



## Conclusion


