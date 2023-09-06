# Classification Project - Predictive Modeling

## Description
Welcome to the Classification Project repository. In this project, we aimed to build a robust classification model using a dataset comprising 30,000 rows and 25 features. Our objective was to predict a binary outcome using various classification algorithms and employ advanced techniques for feature selection and model optimization.

## Table of Contents
- [Description](#description)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Feature Selection](#feature-selection)
- [Classification Algorithms](#classification-algorithms)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Project Overview
In this project, we tackled a classification problem using a substantial dataset. The primary objectives were as follows:
- Develop a classification model to predict binary outcomes.
- Implement advanced feature selection techniques, including statistical tests, SMOTE, and Sequential Feature Selection.
- Evaluate various classification algorithms to identify the most suitable one.
- Optimize the selected model's performance through hyperparameter tuning.

## Dataset
The dataset used in this project contains 30,000 records with 25 features. While the dataset itself is not included in this repository due to its size, you can obtain it from [provide_dataset_source_link]. The features encompass a range of information, and the dataset has been preprocessed for analysis.

## Feature Selection
Feature selection is a critical part of our project, and we executed various statistical tests to identify the most relevant features. Additionally, techniques like SMOTE (Synthetic Minority Over-sampling Technique) and Sequential Feature Selection were employed to enhance the quality of the feature set.

## Classification Algorithms
Intial Model selection was done using LazyPredict Classifier
We explored several classification algorithms, including but not limited to:
- Logistic Regression
- Random Forest
- Decision Tree
Each algorithm was evaluated based on performance metrics such as Precision, Recall, and F1-score.

## Hyperparameter Tuning
To optimize the model's performance, we applied hyperparameter tuning using GridsearchCV. The XGBoost classifier emerged as the top-performing model, achieving the highest accuracy metrics after hyperparameter tuning.

## Results
After extensive experimentation, our project achieved significant results, including a Precision of 0.836 and a Recall of 0.8, showcasing the model's effectiveness in correctly identifying positive cases while minimizing false positives. Detailed results and performance metrics can be found in our project documentation.
