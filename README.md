# Titanic Exploratory Data Analysis (EDA)

## Overview

This project performs a comprehensive exploratory data analysis on the Titanic dataset. The goal is to understand the factors influencing passenger survival through data inspection, cleaning, visualization, and feature engineering.

---

## Contents

1. **Setup & Data Loading**  
   Import essential libraries and load the Titanic dataset.

2. **Initial Inspection**  
   View sample data, dataset shape, data types, and identify missing values.

3. **Data Cleaning**  
   Remove irrelevant or highly incomplete columns and fill missing values for Age and Embarked.

4. **Univariate Analysis**  
   Visualize distributions of gender, survival, passenger class, age, and fare.

5. **Bivariate Analysis**  
   Examine survival rates with respect to gender, passenger class, embarkation port, age, and fare.

6. **Correlation Analysis**  
   Compute and visualize correlations between numeric features.

7. **Feature Engineering**  
   Create new features such as `is_child` (age < 12) and `family_size` (siblings + parents + self) to assess their impact on survival.

8. **Export**  
   Save the cleaned dataset and key visualizations for future use.

---

## Results Summary

- Age and Fare distributions show right-skewed patterns, with some outliers.
- Survival rate varied significantly by gender, passenger class, and embarkation port.
- Children (age < 12) had higher survival probability.
- Larger family sizes showed diverse survival trends.
- Correlation heatmap highlights relationships between numeric features.

---

## Files

- `titanic_cleaned.csv` — Cleaned Titanic dataset ready for modeling or further analysis.
- Jupyter notebooks / Python scripts — Source code for EDA and visualizations.
- Visualizations — Saved images of key plots (optional).

---

## Usage

Run the provided Python scripts or Jupyter notebooks to reproduce the analysis. Modify or extend the analysis by adding further feature engineering or modeling as needed.

---

## References

- [Seaborn Titanic Dataset](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)
- Kaggle Titanic Competition: https://www.kaggle.com/c/titanic

---

*Prepared by Prakash Chaudhary*
