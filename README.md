# Stroke Prediction Dataset Analysis

This project is a data analysis of a stroke prediction dataset. The dataset contains health-related data and aims to predict whether a person is at risk of having a stroke based on certain features.

## Dataset Description

The dataset contains the following columns:
- `id`: Unique identifier for each row
- `gender`: Gender of the patient (Male/Female)
- `age`: Age of the patient
- `hypertension`: Whether the patient has hypertension (0 = No, 1 = Yes)
- `heart_disease`: Whether the patient has heart disease (0 = No, 1 = Yes)
- `ever_married`: Whether the patient has ever been married (0 = No, 1 = Yes)
- `work_type`: The patient's work type (Various categories)
- `Residence_type`: Whether the patient lives in an urban or rural area
- `avg_glucose_level`: The patient's average glucose level
- `bmi`: Body mass index
- `smoking_status`: The patient's smoking status (Never smoked, Formerly smoked, etc.)
- `stroke`: Whether the patient has had a stroke (Target variable, 0 = No, 1 = Yes)

## Objective

The goal of this analysis is to explore the relationship between different features and the likelihood of having a stroke. Various statistical and machine learning techniques have been used to explore and understand the data.

## Steps:

1. Data Preprocessing:
   - Handled missing values, outliers, and transformed categorical columns.
2. Exploratory Data Analysis (EDA):
   - Visualized correlations between different features.
   - Analyzed the distribution of numerical features.
3. Feature Engineering:
   - Created and encoded categorical features.
   - Examined relationships between features and target variable (stroke).
4. Machine Learning:
   - Built predictive models to forecast the likelihood of a stroke.
   - Evaluated models for accuracy and performance.

## Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Conclusion

Through this analysis, we gain insights into how factors like age, gender, glucose levels, and BMI can influence the likelihood of a stroke. Further improvements can be made by training more complex models to enhance prediction accuracy.
