# Car Analytics Project — Task 1 (Data Immersion & Wrangling)

This repository contains Task 1 of my ApexPlanet Data Analytics Internship Project.
The objective of this task is to inspect, clean, preprocess and enrich the raw automotive dataset.

## Contents
- car_data.csv — Raw dataset
- car_data_cleaned.csv — Cleaned dataset
- cleaning_script.ipynb — Jupyter notebook with full cleaning process
- data_dictionary.md — Explanation of all columns
- README.md — Project overview and instructions

## Steps Performed in Task 1
1. Loaded and inspected raw dataset  
2. Performed data profiling using `df.info()`, `describe()`  
3. Removed duplicate rows  
4. Handled missing values:
   - Numeric columns: median
   - Categorical columns: mode
5. Fixed incorrect data types
6. Engineered new features:
   - car_age
   - price_per_cc
   - price_per_km
7. Treated outliers using percentile capping
8. Exported cleaned dataset

## Tools Used
- Python  
- Pandas  
- Jupyter Notebook  
- VS Code  
- Git & GitHub  

## Next Step
Proceeding to Task 2: Exploratory Data Analysis (EDA) on the cleaned dataset.
