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

- To explore **General Data Information**, such as data overview, feature descriptions, and handling of missing values, check the [information.ipynb](https://github.com/lilihosieni-amin/data-mining-Project/blob/main/preprocessing/information.ipynb) file.
- For **Data Visualizations** and exploratory analysis, refer to the [visualizations.ipynb](https://github.com/lilihosieni-amin/data-mining-Project/blob/main/preprocessing/visualizations.ipynb) file. This file includes frequency distributions, bar charts for categorical features, and a correlation heatmap.
- **Data Preprocessing**: To understand the preprocessing steps applied to the data, including data cleaning, handling outliers, encoding categorical variables, and scaling numerical features, see the [preprocessing.ipynb](preprocessing/preProcessing.ipynb) file. This notebook provides the foundational steps to prepare the data for modeling.
- **Model Training 1**: For model training and evaluation, including decision tree classifiers with various criteria (Gini, Entropy, Log Loss) and Random Forest, review the [model_training.ipynb](DecisionTree_RandomForest/training_model.ipynb) file. This file also includes performance metrics such as accuracy, precision, recall, F1-score, and confusion matrices for each model.
- **Model Training 2**: For model training and evaluation, including implementations of K-Nearest Neighbors (KNN), Support Vector Machine (SVM) with different kernels (linear, rbf, poly), and Naive Bayes (GaussianNB, BernoulliNB), review the files in the [SVM_KNN_naiveBayes](https://github.com/lilihosieni-amin/data-mining-Project/tree/main/SVM_KNN_naiveBayes) folder.
- **Model Training 3**: For model training and evaluation, including implementations of Ensemble method algorithm, review the files in the [Ensemble method algorithm](https://github.com/lilihosieni-amin/data-mining-Project/tree/main/Ensemble%20method%20algorithm) folder. 

### Clone the repository:
```bash
git clone https://github.com/lilihosieni-amin/data-mining-Project.git
