# Thyroid Disease Detection

## Overview

Thyroid Disease Detection is a project aimed at predicting thyroid disease based on various medical parameters. The project utilizes machine learning algorithms to analyze patient data and classify individuals into different categories: Hyperthyroid, Hypothyroid, or Negative (no thyroid disease).

## Dataset

The dataset used in this project contains information about thyroid patients, including age, sex, thyroid hormone levels (TSH, T3, TT4, T4U, FTI), and other relevant medical attributes. The dataset was preprocessed to handle missing values, encode categorical variables, and prepare it for model training.

## Models Used

Three machine learning models were trained and evaluated for thyroid disease prediction:

1. **K-Nearest Neighbors (KNN)**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**

## Results and Analysis

The performance of each model was assessed based on training and testing scores, as well as confusion matrix analysis. Here are the key findings:

- **KNN**:
  - Training Score: 96.8%
  - Testing Score: 95%
  - Misclassifications: Few errors in distinguishing Hyperthyroid and Hypothyroid from Negative.

- **Random Forest**:
  - Training Score: 100%
  - Testing Score: 97.6%
  - Misclassifications: Fewer errors compared to other models; best overall performance.

- **SVM**:
  - Training Score: 92.6%
  - Testing Score: 94.6%
  - Misclassifications: More errors, particularly for Hypothyroid predicted as Negative.

## Conclusion

Based on the analysis, the Random Forest Classifier emerged as the best model for thyroid disease detection due to its high accuracy and robust generalization. Further insights were gained from analyzing misclassifications, suggesting potential areas for improvement in feature selection and preprocessing.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks to explore the dataset, train the models, and evaluate performance.
4. Experiment with different algorithms or preprocessing techniques to improve results.

## Contributors

- [Arslan](https://github.com/iamarslankhalid)
- [Zainab Nadeem](https://github.com/imzainabnadeeem)
