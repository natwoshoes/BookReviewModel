
# Book Review Helpfulness Predictor

This project implements a machine learning model to predict whether a book review will be considered helpful or not. The model analyzes various features of book reviews including text content, length, and word count to make its predictions.

## Overview

The model is built using text preprocessing and TF-IDF vectorization, along with comparisons of multiple ML algorithms (Logistic Regression, Naive Bayes, SVM, Random Forest). It incorporates hyperparameter tuning using GridSearchCV and evaluates performance using accuracy, precision, recall and F1-score metrics.

## Key Features

The system includes text preprocessing and feature extraction capabilities, comprehensive model comparison and selection, performance visualization using confusion matrices, and the ability to make predictions on random reviews.

## Results

The final logistic regression model achieved strong performance metrics with an accuracy of 0.81, precision of 0.82, recall of 0.81, and F1 Score of 0.81.

## Requirements

The project requires pandas, numpy, scikit-learn, matplotlib, seaborn, and nltk libraries to run successfully.

## Usage

The notebook contains a complete step-by-step implementation. It begins with data loading and preprocessing, moves through feature engineering, continues with model training and evaluation, and concludes with example predictions.

## Limitations

The model's performance is constrained by the size of the training dataset. Additionally, there is inherent subjectivity in what constitutes a "helpful" review. The binary classification approach may oversimplify the nuanced nature of review helpfulness.
