# Titanic Survival Prediction Project

## Overview
This project focuses on predicting the survival of Titanic passengers using machine learning models. By analyzing key passenger characteristics such as age, gender, and class, the model achieved an accuracy of **83.2%** on validation data. The project leverages **Logistic Regression** and **Decision Tree** algorithms for classification and includes detailed exploratory data analysis (EDA) and visualization.

## Tools & Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn
- **Visualization Tool**: Power BI
- **Dataset Source**: Kaggle Titanic Dataset (Train and Test datasets)

## Key Features
- Identified critical factors influencing survival, such as:
  - **Age**
  - **Class (Socio-economic status)**
  - **Gender**
- Achieved high accuracy by preprocessing data and tuning models.
- Saved predictions for further analysis in Power BI.

## Workflow
1. **Data Preprocessing**
   - Handled missing values (e.g., age imputation).
   - Dropped irrelevant columns like `PassengerId`, `Name`, and `Ticket`.
   - Encoded categorical variables (e.g., gender, class).

2. **Exploratory Data Analysis (EDA)**
   - Visualized survival rates based on age, gender, and class.
   - Analyzed correlations between features.

3. **Model Training**
   - Trained Logistic Regression and Decision Tree models.
   - Evaluated performance using validation accuracy and classification metrics.

4. **Performance Metrics**
   - Validation Accuracy: **83.2%**
   - Classification Report:
     ```
                  precision    recall  f1-score   support

           0.0       0.85      0.87      0.86       105
           1.0       0.81      0.78      0.79        74

      accuracy                           0.83       179
     macro avg       0.83      0.83      0.83       179
   weighted avg       0.83      0.83      0.83       179
     ```

5. **Results**
   - Predictions saved in:
     - `titanic_predictions_final.csv`
     - `titanic_predictions_for_pbi.csv`

6. **Visualization**
   - Used Power BI to create interactive dashboards for deeper insights.

## How to Run the Project
1. Clone this repository:
