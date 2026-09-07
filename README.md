# Diabetes Prediction

## Overview

This project develops a machine learning classification model to predict whether a patient is likely to have diabetes based on demographic and health-related features.

The project focuses on building an end-to-end machine learning workflow, including exploratory data analysis, data preprocessing, model training, evaluation, and feature importance analysis.

## Dataset

The dataset contains patient-level information including features such as:

* Age
* Gender
* BMI
* Hypertension
* Heart disease
* Smoking history
* HbA1c level
* Blood glucose level

The target variable indicates whether the patient has diabetes.

## Project Workflow

The project follows an end-to-end machine learning workflow:

1. Data loading and initial inspection
2. Exploratory data analysis
3. Data cleaning and preprocessing
4. Feature and target separation
5. Train-test split
6. Model training
7. Model evaluation
8. Feature importance analysis
9. Final model selection

## Exploratory Data Analysis

Exploratory analysis was performed to understand the distribution of the target variable and investigate relationships between the features and diabetes status.

Special attention was given to class imbalance, as the dataset contains considerably more non-diabetic than diabetic observations.

## Data Preprocessing

The preprocessing stage included handling categorical and numerical features using appropriate transformations.

A Scikit-learn pipeline was used to keep preprocessing and model training organized and to reduce the risk of data leakage.

## Models

Several classification algorithms were evaluated, including:

* Logistic Regression
* Random Forest Classifier

The models were compared using multiple evaluation metrics rather than relying only on accuracy.

## Model Evaluation

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Because of the class imbalance in the dataset, precision, recall, and F1-score were considered alongside accuracy when evaluating model performance.

## Feature Importance

Feature importance was analyzed to identify which variables contributed most to the Random Forest model's predictions.

This provides additional insight into the factors that are most influential in the model's decision-making process.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
diabetes-prediction/
│
├── data/
│   └── diabetes_prediction_dataset.csv
│
├── Diabetes-prediction-project.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Conclusion

This project demonstrates a complete machine learning classification workflow for diabetes prediction, from exploratory data analysis and preprocessing to model evaluation and interpretation.

The project also highlights the importance of selecting appropriate evaluation metrics when working with imbalanced classification datasets.
