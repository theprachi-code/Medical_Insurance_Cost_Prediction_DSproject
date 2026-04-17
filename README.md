# Medical_Insurance_Cost_Prediction_DSproject

So, I have performed the following steps:

1.  **Data Loading and Initial Inspection**:
    I have loaded the `insurance_dataset` from a CSV file. then inspected its shape, data types, and checked for any missing values.
    
2.  **Exploratory Data Analysis (EDA)**:
    I have performed various analyses to understand the data distribution. This included:
    *   Displaying statistical measures of the dataset.
    *   Visualizing the distribution of 'age', 'bmi', and 'charges' using `distplot`.
    *   Counting and visualizing the distribution of categorical features like 'sex', 'children', 'smoker', and 'region' using `countplot`           and `value_counts()`.
3.  **Data Pre-processing**:
    I have prepared the data for model training by:
    *   Encoding categorical features ('sex', 'smoker', 'region') into numerical representations using `replace`.
    *   Splitting the `insurance_dataset` into features (X) and the target variable (Y), where 'charges' is the target.
