# Explainable AI-Based Clinical Decision Support System for Heart Disease Risk Prediction

## About the Project

This is my M.Sc. Data Science mini project. The main aim of this project is to predict the likelihood of heart disease using Machine Learning.

The system not only predicts the result but also explains why the model gives that prediction using Explainable AI techniques.

## Objectives

- To predict heart disease using clinical data.
- To identify and correct data quality issues.
- To compare different Machine Learning models.
- To explain predictions using SHAP and LIME.
- To measure the agreement between SHAP and LIME.
- To provide predictions and explanations for new patients.

## Dataset

- Total records: 918
- Clinical features: 11
- Heart disease cases: 508
- No heart disease cases: 410

## Technologies Used

- Python
- Machine Learning
- Pandas and NumPy
- Scikit-learn
- Random Forest
- XGBoost
- SHAP
- LIME
- Data Visualization

## Models Compared

- Logistic Regression
- Random Forest
- Tuned Random Forest
- XGBoost

## Results

- Selected Model: Tuned Random Forest
- Test Accuracy: 87.50%
- Test ROC-AUC: 0.9271
- Recall: 91.18%
- SHAP–LIME Top-Five Feature Agreement: 80.4%

The tuned Random Forest model was selected based on its five-fold cross-validation ROC-AUC score.

## Key Features

- Data preprocessing and cleaning.
- Heart disease risk prediction.
- Model performance evaluation.
- SHAP-based explanations.
- LIME-based explanations.
- New-patient prediction module.

## Future Improvements

- Test the model with additional datasets.
- Improve the explanation methods.
- Develop a web interface.
- Explore a natural-language chatbot.

## Disclaimer

This project is an academic prototype for learning and research purposes. It is not a medical diagnostic tool and should not be used to make medical decisions.

## Author

**Divya D**

M.Sc. Data Science  
KPR College of Arts Science and Research  
Academic Year: 2025–2026
