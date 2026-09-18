# Heart Disease Prediction

**Created by Rahul Yadav**

## Project Overview

Heart Disease Prediction is a Machine Learning classification project that predicts whether a person is likely to have heart disease using health-related features.

## Dataset Overview

- **Rows:** 918
- **Columns:** 12
- **Problem Type:** Binary Classification
- **Target:** Heart disease prediction

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Dataset Overview
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Data Preprocessing
7. Feature Selection
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Model Comparison
12. Conclusion

## Machine Learning Models

The following classification models were tested:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

## Model Comparison

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Logistic Regression | 87.50% | 89.00% |
| KNN | 85.33% | 87.08% |
| Naive Bayes | 83.15% | 84.58% |
| Decision Tree | 82.61% | 88.34% |
| SVM | 86.41% | 88.04% |

## Classification Report

The classification report shown during evaluation contains:

| Class | Precision | Recall | F1 Score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.82 | 0.87 | 0.84 | 77 |
| 1 | 0.90 | 0.86 | 0.88 | 107 |

**Overall accuracy:** 86%

**Weighted average F1 score:** 0.89

> Note: The classification report above is presented as the evaluation output supplied for the project. The model name associated with this specific report was not provided.

## Model Evaluation Metrics

- **Accuracy:** Measures the percentage of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly detected.
- **F1 Score:** Balances precision and recall.
- **Confusion Matrix:** Shows true and false predictions for each class.

## Conclusion

The project compares five machine learning classification models for heart disease prediction. Logistic Regression achieved 87.50% accuracy and an 89.00% F1 score in the supplied model comparison results.

For medical prediction tasks, model evaluation should not rely on accuracy alone. Precision, recall, F1 score, and the confusion matrix should also be considered.

## Author

**Rahul Yadav**
