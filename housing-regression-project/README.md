# Housing Regression Project

This project compares multiple regression models for predicting housing prices using the California housing dataset. It focuses on preprocessing, model training, and evaluation using RMSE and cross-validation.

## Project Type

Supervised machine learning regression project with model comparison.

## Files

- `housing.csv`: Main training dataset
- `input.csv`: Input dataset used in the project workflow
- `main.py`: Main training and evaluation script
- `Joblib.py`: Alternate script for model saving and inference workflow
- `pipeline.pkl`: Saved preprocessing pipeline

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Workflow

1. Load the housing dataset
2. Create income categories for stratified sampling
3. Split the data into training and test sets
4. Separate features and target values
5. Build preprocessing pipelines for numerical and categorical data
6. Train multiple regression models
7. Evaluate model performance using:
   - RMSE
   - cross-validation scores

## Features Used

- `longitude`
- `latitude`
- `housing_median_age`
- `total_rooms`
- `total_bedrooms`
- `population`
- `households`
- `median_income`
- `ocean_proximity`

## Target Variable

- `median_house_value`

## How to Run

```bash
pip install pandas numpy scikit-learn joblib
python main.py
```

## Notes

- The large trained `model.pkl` file is intentionally excluded from the repository to avoid GitHub size limit issues.
- This project is useful for understanding how different regression models perform on the same housing dataset.
