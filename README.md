# Admission Prediction
![R² Score](https://img.shields.io/badge/R²-0.82-brightgreen)

A machine learning project that predicts a student's chance of graduate admission based on academic factors, using regression models and scikit-learn.

## Dataset

The dataset ('Admission_Predict_Ver1.1.csv') contains 500 records with 9 columns.

## Workflow

1. **Exploratory Data Analysis (EDA)** — correlation heatmap, pairplot, and distribution analysis
2. **Data Preparation** — dropped irrelevant columns, defined features (X) and target (y)
3. **Model Comparison** — compared 6 regression models using GridSearchCV with 5-fold cross-validation
4. **Model Training** — trained the best model (Linear Regression) on an 80/20 train-test split
5. **Evaluation** — achieved an R² score of **0.82** on the test set

## Tools Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
