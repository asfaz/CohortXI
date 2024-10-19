# Titanic Dataset - Exploratory Data Analysis (EDA)
## Overview
This project explores the famous Titanic dataset to analyze the factors that influenced passenger survival rates. Through various data analysis and visualization techniques, the project uncovers patterns related to demographics, class, and ticket fares, among other factors.

## Project Structure
titanic_eda.ipynb: The main notebook containing all the steps of data cleaning, analysis, and visualization.

## Key Insights
1. Data Cleaning:
Handling missing values, especially in Age, Cabin, and Embarked columns.
Removal of unnecessary columns like PassengerId, Ticket, and Name for streamlined analysis.

2. Visualizations:
Bar plots, histograms, and box plots showing the survival distribution by features such as Sex, Pclass, Age, and Fare.
Heatmap illustrating correlations between features.

3. Feature Engineering:
Created new features such as FamilySize and IsAlone to enrich the dataset.
Categorized ages into age bands for more intuitive analysis.

4. Survival Analysis:
Explored the influence of gender, class, and age on survival rates.
Observed that passengers in higher classes, females, and younger passengers had a higher survival rate.

## Dependencies
1. pandas
2. numpy
3. matplotlib
4. seaborn

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle.

## Future Improvements
1. Feature selection and model training for survival prediction.
2. Application of advanced data imputation techniques for missing values.
3. Optimization of visualizations for more interactive analysis.
