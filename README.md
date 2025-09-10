# titanic-dataset-preprocessing

## Overview
This project demonstrates the **full data preprocessing workflow** for the Titanic dataset. The goal is to transform raw data into a **clean, numeric, machine learning-ready dataset**. This is an essential step before training any predictive model.

## What I Did
- **Explored the dataset:** inspected rows, columns, data types, missing values, and basic statistics  
- **Handled missing values:**  
  - Filled missing `Age` values with median  
  - Filled missing `Embarked` values with the most frequent category  
  - Dropped `Cabin` column due to too many missing values  
- **Encoded categorical features:**  
  - Converted `Sex` and `Embarked` into numeric values  
- **Feature engineering:**  
  - Created `FamilySize = SibSp + Parch + 1`  
  - Created `IsAlone` to indicate passengers traveling alone  
- **Dropped irrelevant columns:** `PassengerId`, `Name`, `Ticket`  

## Skills Learned
- **Pandas:** data exploration, selection, `.loc[]`, `.drop()`, `.fillna()`, `.map()`, `.mode()`  
- **Data Cleaning & Preprocessing:** handling missing values, encoding categorical variables, dropping unnecessary columns  
- **Feature Engineering:** creating new features to improve model insights  
- **Python Programming:** applying logical workflows for dataset preparation  
- **Exploratory Data Analysis (EDA):** inspecting data and understanding distributions  

## Outcome
The final dataset is **clean, numeric, and ready for machine learning models**. This project reinforces core data science skills such as data cleaning, preprocessing, and feature engineering.

