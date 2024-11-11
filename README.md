# data-mining-Project

## Overview
This project focuses on analyzing a healthcare dataset aimed at predicting stroke occurrences. Through exploratory data analysis (EDA) and data visualization, we seek to identify patterns and correlations among patient attributes, such as age, gender, BMI, and lifestyle factors, that may contribute to stroke risk. This analysis serves as a foundational step, providing insights into the data structure and relationships that may guide future predictive modeling efforts to improve stroke risk assessment.

## Dataset Overview

The dataset used in this project is sourced from [Kaggle's Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). It includes health and demographic data for individuals, focusing on features relevant to stroke risk. Each row represents a unique patient record, with 5,110 entries and 12 features in total.

### Key Features
- **age**: The age of the patient (numeric).
- **gender**: Gender of the patient (categorical: Male, Female, Other).
- **hypertension**: Whether the patient has hypertension (0 = No, 1 = Yes).
- **heart_disease**: Whether the patient has a heart condition (0 = No, 1 = Yes).
- **ever_married**: Marital status of the patient (Yes or No).
- **work_type**: Type of employment (e.g., Private, Self-employed).
- **Residence_type**: Type of residence (Urban or Rural).
- **avg_glucose_level**: Average glucose level in the blood (numeric).
- **bmi**: Body mass index (numeric, with some missing values).
- **smoking_status**: Smoking status of the patient (e.g., formerly smoked, never smoked).
- **stroke**: Target variable indicating if the patient had a stroke (0 = No, 1 = Yes).

The dataset includes both numerical and categorical features, allowing for a mix of statistical and visual analysis methods to understand distributions and relationships in the data. Some columns, like BMI, have missing values that are handled in the analysis process. This dataset serves as a valuable resource for identifying factors associated with stroke risk.


## Usage

- To explore **General Data Information**, such as data overview, feature descriptions, and handling of missing values, check the `information.ipynb` file.
- For **Data Visualizations** and exploratory analysis, refer to the `visualizations.ipynb` file. This file includes frequency distributions, bar charts for categorical features, and a correlation heatmap.

### Clone the repository:
```bash
git clone https://github.com/YourUsername/StrokePredictionDataAnalysis.git
