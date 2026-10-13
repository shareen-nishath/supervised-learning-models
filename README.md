

# Supervised Regression Learning Models

This project implements and compares multiple supervised machine learning regression algorithms across three distinct datasets to predict continuous numerical values.

## Datasets & Tasks
1. **Salary Dataset**: Predicting employee salaries based on years of experience.
2. **Student Performance Dataset**: Predicting a student's Performance Index using hours studied, previous scores, extracurricular activities (encoded), sleep hours, and sample question papers practiced.
3. **Insurance Dataset**: Predicting medical insurance charges using medical attributes (age, sex, BMI, children, smoker status, and geographical region) processed using One-Hot Encoding.

## Implemented Models
- **Linear Regression**: Baseline regression modeling.
- **Decision Tree Regressor**: Non-linear modeling capable of capturing feature thresholds.
- **Random Forest Regressor**: Ensemble learning technique to minimize overfitting and improve generalization.

## Key Results

### 1. Salary Dataset
- **Linear Regression**: R² ~ 0.902, MAE ~ 6,286.45
- **Random Forest**: R² ~ 0.875, MAE ~ 6,872.01
- **Decision Tree**: R² ~ 0.802, MAE ~ 8,640.17

### 2. Student Performance Dataset
- **Linear Regression**: R² ~ 0.989, MAE ~ 1.61
- **Random Forest (depth=5)**: R² ~ 0.976, MAE ~ 2.37
- **Decision Tree (depth=5)**: R² ~ 0.965, MAE ~ 2.93

### 3. Insurance Dataset
- **Random Forest (depth=5)**: R² ~ 0.874, MAE ~ 2,558.19
- **Decision Tree (depth=5)**: R² ~ 0.834, MAE ~ 2,930.77
- **Linear Regression**: R² ~ 0.784, MAE ~ 4,181.19

## Getting Started

### Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install -r requirements.txt
```

### Usage
Run the Python script or notebook to execute preprocessing, model training, and comparative evaluation metrics (R² score and Mean Absolute Error).
```