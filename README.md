## Overview

Non-Alcoholic Fatty Liver Disease (NAFLD) is a liver disorder caused by fat accumulation, often linked to obesity and metabolic syndromes. Early detection is crucial to prevent severe liver complications such as inflammation, cirrhosis, or non-alcoholic steatohepatitis (NASH).

This project leverages machine learning algorithms including Random Forest, Gradient Boosting, and XGBoost, combined with cross-validation and hyperparameter tuning (Grid Search CV and Randomized Search CV), to accurately predict NAFLD from patient demographic and clinical data. The system achieves high accuracy and reliability, enabling proactive health interventions.

## Tech Stack

Programming Language: Python
Libraries & Frameworks:
Pandas & NumPy (Data manipulation)
Scikit-learn (Machine learning algorithms, preprocessing, evaluation)
XGBoost (Gradient boosting implementation)
Imbalanced-learn (SMOTE for oversampling)
Matplotlib & Seaborn (Data visualization)

## Tools:

Jupyter Notebook / Python IDE
Kaggle dataset for Indian Liver Patient data

### Project Workflow

1. Data Collection:

Dataset downloaded from Kaggle, initially containing 483 rows and 11 columns.

Oversampling (SMOTE) applied to handle class imbalance, expanding dataset to 1057 rows.

2. Data Preprocessing:

Split dataset into training (70%) and testing (30%) sets.

Standardized numeric features using feature scaling (for applicable models).

Handled categorical variables like gender.

3. Model Implementation:

Trained multiple machine learning models: Random Forest, Gradient Boosting, XGBoost.

Performed hyperparameter tuning using Grid Search CV and Randomized Search CV.

4. Model Evaluation:

Used metrics: Accuracy, Precision, Recall, F1-score, Matthews Correlation Coefficient (MCC).

Confusion matrix analyzed for True Positive, False Positive, True Negative, False Negative.

5. Results & Insights:

XGBoost achieved highest accuracy (96%) with strong precision and recall.

Randomized Search CV provided optimal performance with reduced computation time.

Boosting + cross-validation enhanced robustness and generalizability of predictions.

6. Conclusion:

The pipeline successfully predicts NAFLD and can be extended to other liver-related datasets.
