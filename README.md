# Titanic Dataset — Exploratory Data Analysis

## Overview
Exploratory data analysis on the Titanic dataset (891 passengers) to uncover survival patterns across gender, class, and age.

## Dataset
- Source: Kaggle Titanic Dataset
- 891 rows, 12 columns
- Key columns: Survived, Pclass, Sex, Age, Fare, Embarked

## Data Cleaning
- Filled 177 missing Age values with median age
- Dropped Cabin column (77% missing values)
- Filled 2 missing Embarked values with mode

## Key Findings
1. Only **38%** of passengers survived overall
2. **74%** of female passengers survived vs only **19%** of males
3. **1st class** passengers had 63% survival rate vs only **24%** in 3rd class
4. **Children (0-10)** had the highest survival rate at 59% — young adults (18-30) had the lowest at 33%

## Charts
- Survival count — overall survived vs died
- Survival by gender — female vs male survival rates
- Survival by passenger class — 1st vs 2nd vs 3rd class
- Age distribution — survived vs died across age groups

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run
1. Clone the repo
2. Install requirements: `pip install pandas matplotlib seaborn`
3. Open `titanic_analysis.ipynb` in Jupyter or VS Code
4. Run all cells