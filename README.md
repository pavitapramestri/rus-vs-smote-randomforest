# Random Forest Resampling Comparison

This project contains a Jupyter notebook for comparing Random Under Sampling (RUS) and SMOTE on a Random Forest model for maintenance severity prediction.

## Project Contents
- `model.ipynb` - main notebook for data loading, preprocessing, training, evaluation, and visualization
- `results_cv_ratio_variation.csv` - cross-validation summary results
- `results_test_ratio_variation.csv` - test-set evaluation results

## What the Notebook Does
- Loads maintenance data from the database
- Encodes categorical features and prepares the target label
- Tests multiple resampling ratios for RUS and SMOTE
- Evaluates models with 10-fold cross-validation and test data
- Generates comparison plots and saves result tables

## Requirements
Typical packages used in the notebook:
- `pandas`
- `numpy`
- `scikit-learn`
- `imbalanced-learn`
- `matplotlib`
- `seaborn`
- `sqlalchemy`
- `pymysql`

## Run
1. Open `model.ipynb` in Jupyter Notebook or VS Code.
2. Make sure the database connection variables are available in your environment.
3. Run the cells from top to bottom.

## Output
After running the notebook, the result tables will be saved as:
- `results_cv_ratio_variation.csv`
- `results_test_ratio_variation.csv`