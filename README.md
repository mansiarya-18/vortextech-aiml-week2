# vortextech-aiml-week2

Week 2 project for the Vortex Tech AI & ML Internship Track — building a binary classification model.

## What this is

A machine learning model that predicts whether a person has heart disease (0 = no, 1 = yes) using scikit-learn. Trains and compares a Logistic Regression model and a Decision Tree model, evaluated with accuracy, precision, recall, and F1 score.

## Dataset

[Heart Disease Dataset - 3000 Records, 2025](https://www.kaggle.com/datasets/pratyushpuri/heart-disease-dataset-3k-rows-python-code-2025) from Kaggle.

Download the CSV and place it in this repo's root folder as `heart_disease.csv` before running the notebook.

## How to run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/vortextech-aiml-week2.git
   cd vortextech-aiml-week2
   ```
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn jupyter
   ```
3. Download the dataset from Kaggle and place `heart_disease.csv` in this folder.
4. Launch Jupyter and run the notebook top to bottom:
   ```bash
   jupyter notebook week2_heart_disease_classification.ipynb
   ```
5. Check `df.columns` after loading — if the target column isn't named `heart_disease` in your copy, update `TARGET_COL` in the "Identify target and feature columns" cell.

## What's inside

- Load and inspect the dataset
- Identify target (`heart_disease`) and feature columns
- Convert any categorical columns to numbers with `pd.get_dummies()`
- Split data into train/test sets (80/20)
- Train a Logistic Regression classifier
- Evaluate using accuracy, precision, recall, and F1 score
- Train and compare a Decision Tree classifier
- Written summary interpreting model performance and ideas for improvement

## Results

See the "Model Performance Summary" markdown cell in the notebook for accuracy/F1 scores and interpretation, filled in after running.

## Author

Vortex Tech AI & ML Internship — Week 2 submission.
