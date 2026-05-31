# Assignment 5: Multi-Class Prediction of Obesity Risk

## Overview

This project applies machine learning classification techniques to predict obesity risk categories using demographic, dietary, and lifestyle variables. The dataset was provided through the Kaggle Playground Series competition: Multi-Class Prediction of Obesity Risk.

## Models Evaluated

The following classification models were developed and compared:

1. Multinomial Logistic Regression
2. Linear Discriminant Analysis (LDA)
3. Gaussian Naive Bayes
4. Support Vector Machine (SVM)
5. Regularized Logistic Regression (L2 Penalty)

## Dataset

The dataset contains information related to:

- Gender
- Age
- Height
- Weight
- Family history of overweight
- Eating habits
- Physical activity
- Water consumption
- Transportation methods

Target Variable:

- NObeyesdad (Obesity Risk Classification)

## Results

| Model | Kaggle Public Score |
|---------|---------|
| Support Vector Machine (SVM) | 0.88005 |
| Logistic Regression | 0.86416 |
| Linear Discriminant Analysis (LDA) | 0.82153 |
| Naive Bayes | 0.58995 |

### Best Performing Model

The Support Vector Machine (SVM) achieved the highest Kaggle score and was selected as the best-performing model for this project.

## Repository Contents

- `Assignment5.ipynb` – Jupyter Notebook containing all code and analysis
- `Assignment5 - JupyterLab.pdf` – PDF version of the completed notebook
- `submission_logistic.csv` – Logistic Regression Kaggle submission
- `submission_lda.csv` – LDA Kaggle submission
- `submission_nb.csv` – Naive Bayes Kaggle submission
- `submission_svm.csv` – SVM Kaggle submission

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- JupyterLab
- Kaggle

## Author

Delois Sistrunk Giles


