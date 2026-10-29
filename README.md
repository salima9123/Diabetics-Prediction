# Diabetes Prediction Using Logistic Regression

## Project Overview

This project uses Machine Learning to predict whether a person may belong to the diabetes or non-diabetes category based on the input data.

The model is built using Logistic Regression in Python. It includes data preprocessing, model training, and performance evaluation to understand how well the model classifies the data.

## Problem Statement

Diabetes is a common health condition, and identifying patterns in health-related data can help with preliminary risk assessment. This project uses Machine Learning to classify data into diabetes and non-diabetes categories based on the features available in the dataset.

## Objectives

- Build a Machine Learning model for diabetes prediction.
- Prepare and clean the dataset before training.
- Train a Logistic Regression classification model.
- Evaluate model performance using classification metrics.
- Predict the output for new input data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised Machine Learning algorithm used for classification problems. In this project, it predicts one of two classes based on the input features.

## Project Workflow

1. Loaded and inspected the dataset.
2. Checked and prepared the data for model training.
3. Performed data preprocessing.
4. Separated the input features and target variable.
5. Split the dataset into training and testing sets.
6. Trained the Logistic Regression model.
7. Evaluated the model using accuracy, precision, recall, F1-score, and a classification report.
8. Used the trained model to make predictions.

## Model Evaluation

The model was evaluated on 19,230 test samples.

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 96% |
| Macro Average Precision | 92% |
| Macro Average Recall | 81% |
| Macro Average F1-score | 86% |
| Weighted Average F1-score | 96% |

### Class-wise Performance

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Class 0 | 97% | 99% | 98% |
| Class 1 | 87% | 64% | 74% |

The model achieved 96% overall accuracy. However, the recall for Class 1 was 64%, showing that the model did not identify all actual positive cases. This highlights the importance of evaluating recall and F1-score in addition to accuracy.

*Note: Class 0 and Class 1 represent the target labels in the dataset. Confirm their meanings before interpreting them as non-diabetes and diabetes.*

## Key Features

- Data preprocessing and preparation.
- Binary classification using Logistic Regression.
- Evaluation using multiple classification metrics.
- Prediction based on input features.
- Performance analysis using a classification report.

## Dataset

The project uses a diabetes prediction dataset containing health-related input features and a target label.

Add the original dataset source link here:
[Diabetes Prediction Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?utm_source=chatgpt.com)

## How to Run the Project

1. Open the notebook in Google Colab.
2. Upload the required dataset.
3. Run the notebook cells in order.
4. Train the Logistic Regression model.
5. Review the evaluation results and predictions.

## Future Improvements

- Improve recall for the positive class.
- Compare Logistic Regression with other classification algorithms.
- Test different preprocessing techniques.
- Evaluate the model on additional data.

## Disclaimer

This project is developed for educational purposes only. Its predictions are not a substitute for professional medical advice, testing, or diagnosis.

## Author

Machine Learning project developed using Python and Scikit-learn.
