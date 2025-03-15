# Churn Prediction Challenge

## 📌 Project Overview
This project aims to build predictive models for customer churn and submit final predictions to the course for evaluation.

## 🔍 Project Workflow
### 1. Data Exploration
- Examined the training and testing datasets to understand the distribution of numerical and categorical features.
- Analyzed feature correlations to identify strong predictors of customer churn.
- Investigated categorical feature distributions across different churn outcomes to determine potential useful predictors.

### 2. Data Preprocessing
- Applied normalization to numerical features.
- Encoded categorical variables for model compatibility.
- Created train-test splits for internal evaluation.

### 3. Model Development & Evaluation
- Tested various classification models using cross-validation and grid search.
- Identified the best-performing model for prediction.
- Generated test set predictions for submission.

### 4. Results
- **Best Model:** Logistic Regression with Elastic Net regularization.
- **Performance:** Achieved a ROC AUC score of **0.7508** in evaluation.

## 📂 Repository Structure
- `ChurnPrediction.ipynb` - Jupyter notebook containing the full analysis, model building, and evaluation process.
- `data_descriptions.csv` - Data catalogue.
- `train.csv` - Training datat containing features and churn.
- `test.csv` - Test data for model evaluation.
- `README.md` - Project documentation.