# Housing Price Prediction Projects

A collection of machine learning projects focused on housing price prediction using the California housing dataset. This repository includes model training, preprocessing pipelines, regression model comparison, and prediction workflows built with Python and scikit-learn.

## Projects

### 1. California House Prediction Project
- Folder: `california-house-prediction-project`
- Type: End-to-end machine learning prediction workflow
- Focus: Train a housing price prediction model, save the preprocessing pipeline, and run inference on input data
- Key techniques:
  - Stratified train split using income categories
  - Numerical and categorical preprocessing pipelines
  - Random Forest regression
  - Saved pipeline and prediction workflow

### 2. Housing Regression Project
- Folder: `housing-regression-project`
- Type: Regression model comparison project
- Focus: Compare multiple regression models for housing price prediction and evaluate their performance
- Key techniques:
  - Stratified sampling
  - Data preprocessing with `ColumnTransformer`
  - Linear Regression, Decision Tree, and Random Forest
  - RMSE and cross-validation based evaluation

## Tech Stack

- Python
- Pandas
- NumPy
- scikit-learn
- Joblib

## Repository Structure

```text
Housing-Price-Prediction-projects/
├── README.md
├── .gitignore
├── california-house-prediction-project/
│   ├── README.md
│   ├── housing.csv
│   ├── input.csv
│   ├── main.py
│   ├── main_old.py
│   └── pipeline.pkl
└── housing-regression-project/
    ├── README.md
    ├── housing.csv
    ├── input.csv
    ├── main.py
    ├── Joblib.py
    └── pipeline.pkl
```

## Notes

- Large trained model files such as `model.pkl` are not included in this repository because they exceed GitHub's normal file size limit.
- Generated artifacts and notebook checkpoint files are also excluded to keep the repository clean.

## How to Run

1. Clone the repository.
2. Install the required dependencies:

```bash
pip install pandas numpy scikit-learn joblib
```

3. Open a project folder and run the Python script:

```bash
python main.py
```

## Purpose

This repository is part of a machine learning portfolio and demonstrates practical skills in data preprocessing, model training, evaluation, serialization, and prediction workflows for regression problems.
