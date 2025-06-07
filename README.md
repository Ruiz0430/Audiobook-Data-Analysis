# Audiobook-Data-Analysis

## Table of Contents
- [Description](#Description)
- Part 1
  - [Features](#Features_1)
  - [Plots](#Plots_1)
- Part 2
  - [Features](#Features_2)
  - [Plots](#Plots_2)
- [Acknowledgements](#Acknowledgements_1)


## Description_1
This project leverages a dataset from an audiobook mobile application to build predictive models that determine which users are likely to make repeat purchases. The dataset spans two years of user behavior, including metrics such as listening time, completion rates, support interactions, and purchase patterns. The primary business objective is to optimize advertising efforts by identifying and targeting customers who are most likely to return, thereby increasing sales efficiency and reducing wasted ad spend on low-conversion users.

## Features_1
- Pandas and NumPy for data loading, exploration, and preprocessing tasks such as normalization and feature engineering.
- Matplotlib and Seaborn for data visualization and exploratory data analysis to uncover trends and relationships within the dataset.
- Scikit-learn for implementing and evaluating machine learning models, including Logistic Regression and Linear Discriminant Analysis (LDA). These models are used to classify customer behavior based on historical engagement data.
- Scikit-learn's K-Fold Cross-Validation is used to validate model performance across multiple data splits, ensuring robust evaluation and reducing overfitting.
- Polynomial Regression to capture nonlinear relationships between features and target outcomes.

## Plots_1
<img width="848" alt="Screenshot 2025-06-06 at 11 04 44 PM" src="https://github.com/user-attachments/assets/85d31245-45a3-4086-ba60-3a8efef35763" />
<img width="873" alt="Screenshot 2025-06-06 at 11 04 57 PM" src="https://github.com/user-attachments/assets/41b8effe-586c-458f-bef4-aaac337b49dc" />
<img width="1232" alt="Screenshot 2025-06-06 at 11 05 05 PM" src="https://github.com/user-attachments/assets/d69862fa-4a5c-4695-8d72-39b885daa8fb" />

## Features_2
- Model Evaluation: accuracy_score, confusion_matrix, cross_val_score
- Confusion Matrix
- R² Score and RMSE (for regression models)
- Silhouette Score and Davies-Bouldin Score (for clustering models)
- Dimensionality checks using VIF (Variance Inflation Factor)

## Plots_2
<img width="560" alt="Screenshot 2025-06-07 at 12 32 06 AM" src="https://github.com/user-attachments/assets/98531c7b-cdd6-4e2f-95bf-f2f84c300eb8" />
<img width="1051" alt="Screenshot 2025-06-07 at 12 33 14 AM" src="https://github.com/user-attachments/assets/eb49b900-da72-4d6e-a097-eb9fa09385d3" />
<img width="1050" alt="Screenshot 2025-06-07 at 12 33 41 AM" src="https://github.com/user-attachments/assets/718e72a2-1c13-4efd-afdc-8dd14efed9ec" />
<img width="1414" alt="Screenshot 2025-06-07 at 12 31 24 AM" src="https://github.com/user-attachments/assets/cd536a45-b7fb-4981-8f7c-b0cf1def330c" />
<img width="857" alt="Screenshot 2025-06-07 at 12 31 38 AM" src="https://github.com/user-attachments/assets/aeb607e7-d025-42f3-9346-0a8970331111" />


## Acknowledgements
- [Dataset](https://www.kaggle.com/datasets/snehangsude/audible-dataset))

