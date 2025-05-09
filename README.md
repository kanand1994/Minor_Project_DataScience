# National Health and Nutrition Examination Survey Analysis

## Table of Contents
- [Overview](#overview)
- [Data Analysis](#data-analysis)
- [Methodology](#methodology)


## Overview
This project uses the **National Health and Nutrition Examination Survey (NHANES)** dataset to analyze the health and nutritional status of a population. The objective of this analysis is to explore relationships between various health metrics, demographic factors, and nutrition data. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization of key findings.

## Data Analysis

The dataset used in this analysis is from the **National Health and Nutrition Examination Survey**. This dataset contains information about individuals' demographics, health conditions, medical history, and dietary intake.

### Steps Followed in the Analysis:
1. **Data Import and Cleaning**:
   - The dataset was imported using **Numpy,Pandas**, and initial inspection was performed to check for missing values, duplicates, or outliers.
   - Missing data were handled using imputation techniques like replacing with the mean or median, and rows with too many missing values were dropped.

2. **Exploratory Data Analysis (EDA)**:
   - Key insights were extracted by exploring the distribution of health metrics such as BMI (Body Mass Index), cholesterol levels, and blood pressure.
   - Visualizations were created to understand the relationships between variables like age, gender, and nutrition.

  
   
3. **Correlation Analysis**:
   - The correlation between **BMI**, **cholesterol levels**, and other health variables was examined using a heatmap to visualize the relationships.
   
  

## Methodology

### Data Preprocessing:
- **Data Types**: Data types for each column were checked and corrected if necessary (e.g., converting categorical variables to categories).
- **Missing Values**: Rows with missing values were imputed using the mean for continuous features and the mode for categorical features.

### Statistical Analysis:
- **Descriptive Statistics**: Summary statistics were generated for key variables such as BMI, blood pressure, and age.
  
