# adult-dataset.csv

This project implements a complete machine learning pipeline to predict whether an individual earns more than $50K per year using the Adult Census dataset.

## Dataset
The Adult Census dataset contains demographic and employment-related attributes such as age, education, workclass, hours per week, and occupation.

## Project Workflow
- Data loading and exploration
- Handling implicit missing values
- Train-test split to avoid data leakage
- Feature engineering:
  - One-Hot Encoding for categorical features
  - Standard Scaling for numerical features
- Model training using Support Vector Machine (SVM)
- Model evaluation using accuracy

## Files in this Repository
- `data_preprocessing_and_feature_engineering.ipynb` – Jupyter Notebook with full implementation
- `data_preprocessing_and_feature_engineering.html` – HTML export of the notebook
- `adult-dataset.csv` – Dataset file
- `README.md` – Project description

## Tools and Libraries
- Python
- Pandas
- NumPy
- Scikit-learn

## Model
- Algorithm: Support Vector Machine (SVM)
- Evaluation Metric: Accuracy

## Output
The final model is evaluated on unseen test data to ensure unbiased performance.
