# California House Prediction Project

This project builds a machine learning workflow for predicting California housing prices. It includes data loading, preprocessing, model training, model serialization, and inference using saved artifacts.

## Project Type

End-to-end regression and prediction workflow using scikit-learn.

## Files

- `housing.csv`: Main housing dataset used for training
- `input.csv`: Sample input data used for prediction
- `main.py`: Main training and inference script
- `main_old.py`: Older version of the workflow script
- `pipeline.pkl`: Saved preprocessing pipeline

## Workflow

1. Load the California housing dataset
2. Create income-based categories for stratified sampling
3. Split training data using `StratifiedShuffleSplit`
4. Build preprocessing pipelines for:
   - numerical features with imputation and scaling
   - categorical features with one-hot encoding
5. Train a `RandomForestRegressor`
6. Save the trained pipeline and model artifacts
7. Run inference on `input.csv` when saved artifacts are available

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

- The original trained `model.pkl` file is excluded from the repository because it is larger than GitHub's standard size limit.
- You can regenerate the model locally by running the training workflow.

