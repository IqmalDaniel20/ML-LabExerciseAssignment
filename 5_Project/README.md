 # Machine Learning Project - Mental Health Prediction

## Overview

This repository contains the machine learning project focused on predicting mental health issues among students based on various demographic and academic factors. The project involves comprehensive data preprocessing, exploratory data analysis (EDA), and predictive modeling using several machine learning techniques.

## Objectives

- To understand the impact of demographic and academic factors on students' mental health.
- To apply various machine learning models to predict mental health issues.
- To evaluate and compare the performance of different models.

## Data Description

The dataset includes the following attributes:
- Gender
- Age
- Course
- Year of Study
- CGPA
- Marital status
- Mental health issues (Depression, Anxiety, Panic attacks)
- Treatment

## Data Cleaning and Preprocessing

- Handling missing values and duplicates.
- Normalizing and encoding categorical data.
- Feature engineering to extract meaningful information for model training.

## Exploratory Data Analysis (EDA)

- Visualizations to understand the distribution of key variables.
- Correlation analysis to identify relationships between features.
- In-depth analysis of demographic factors affecting mental health.

## Predictive Modeling

- **Models Implemented**:
  - Support Vector Machine (SVM)
  - Gaussian Naive Bayes
  - Logistic Regression
  - Gradient Boosting
  - Random Forest
  - K-Nearest Neighbors (KNN)

- Model evaluation based on accuracy, confusion matrix, and other relevant metrics.
- Hyperparameter tuning to optimize model performance.

## Results and Discussion

- Summary of model performances.
- Insights derived from model predictions and feature importances.

## Installation and Execution

To interact with the analysis and models:

1. **Open Google Colab**: Visit [Google Colab](https://colab.research.google.com/).
2. **Import the Notebook**: Click on `File` > `Upload notebook` > `Choose file` to upload the `.ipynb` file.
3. **Upload the Dataset**:
   - Navigate to the sidebar, select the `Files` tab, and click on `Upload to session storage`.
   - Drag and drop the `Student Mental health.csv` file from your computer into the Colab session storage. This will ensure the dataset is accessible when running the notebook.
4. **Run the Notebook**: Execute the code cells sequentially to explore the data analysis and model training steps. Ensure each cell that references the dataset points to the correct filename if it was renamed during upload.

