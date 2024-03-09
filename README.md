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



## **CONCLUSION AND RECOMMENDATION**

**Findings**
--

- **Age Group Influence:** Older age groups exhibit higher vaccination rates, possibly due to increased susceptibility or greater awareness. For instance, individuals aged 55 and above show higher rates of vaccination compared to younger age groups like 18-34 years.

- **Household Composition:** While vaccination rates decrease slightly with an increase in the number of children in the household, the differences are relatively small. For instance, households with no children tend to have slightly higher vaccination rates compared to those with three or more children.

- **Gender Differences:** Both genders have similar vaccination rates, with slightly more females vaccinated compared to males. However, the differences in vaccination rates between genders are not substantial.

- **Perception of Effectiveness:** Respondents' perceived effectiveness of the vaccine significantly influences their likelihood of vaccination. Higher perceived effectiveness correlates with increased vaccination uptake, indicating the importance of addressing misconceptions and promoting awareness about vaccine efficacy.

- **Doctor Recommendation:** Recommendations from healthcare professionals play a crucial role in vaccination decisions. Respondents who received a recommendation from a doctor for the H1N1 vaccine exhibited a higher likelihood of vaccination compared to those who did not receive such recommendations.

- **Knowledge Level:** Greater knowledge about the H1N1 flu is associated with higher vaccination rates. Individuals with higher levels of knowledge about the flu are more likely to opt for vaccination, emphasizing the importance of education and awareness campaigns.

- **Regional Disparities:** While variations in vaccination rates exist across regions, the differences are not substantial. Most regions show vaccination rates ranging from approximately 17% to 23%, indicating a relatively consistent pattern of vaccination behavior across geographic regions.


**Best Model Selection:**
--

Both Logistic Regression and SVM consistently demonstrated the highest F1 scores among the listed algorithms. This suggests that they excel in achieving a balance between precision and recall, which is crucial for accurately identifying positive instances while minimizing false positives.

If interpretability and simplicity are paramount considerations, Logistic Regression may be the preferable option. On the other hand, if sacrificing some interpretability in favor of potentially higher accuracy is acceptable, SVM could be the more suitable choice.

**Recommendations:**
--

- **Targeted Education Campaigns:** Develop campaigns to raise awareness of vaccination benefits, especially targeting younger age groups and individuals with limited knowledge of H1N1 flu.

- **Healthcare Provider Training:** Train healthcare professionals to advocate for H1N1 vaccination, enhancing uptake among eligible individuals.

- **Improved Access:** Ensure easy access to vaccination services, particularly in regions with low vaccination rates, to increase overall uptake.

- **Public Messaging:** Address misconceptions about vaccine effectiveness through public messaging, emphasizing vaccination's role in preventing disease spread.

- **Research and Monitoring:** Continuously monitor vaccination rates and factors influencing behavior to tailor interventions effectively.

- **Community Engagement:** Involve communities in vaccination promotion strategies, considering their concerns and preferences.


