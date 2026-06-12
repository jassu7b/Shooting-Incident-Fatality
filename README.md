# Shooting Incident Fatality

## Project Overview
This project aims to analyze shooting incident data and predict fatality outcomes using Machine Learning techniques. The objective is to identify key factors associated with fatal incidents and develop predictive models that can assist in data-driven decision-making and public safety research.

##Problem Statement
Shooting incidents have significant social and public safety implications. By leveraging historical incident data, this project seeks to predict whether an incident is likely to result in fatalities based on various demographic, geographic, and incident-related factors.

##Dataset
The dataset contains historical shooting incident records. Detailed information regarding the dataset with respect to each column is given in "description.txt" .

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib

## Project Workflow
1. Data Collection
• Imported and explored the shooting incident dataset.
• Verified data quality and feature consistency.

2. Data Preprocessing
• Handled missing values.
• Removed duplicate records.
• Encoded categorical variables.
• Performed feature scaling where required.

3. Exploratory Data Analysis (EDA)
• Analyzed fatal and non-fatal incident distributions.
• Identified trends across locations and time periods.
• Visualized key relationships using charts and graphs.

4. Feature Engineering
• Selected relevant predictors.
• Created additional derived features to improve model performance.

5. Model Development
• Logistic Regression
• Random Forest
• XGBoost

6. Hyperparameter Tuning
• Applied GridSearchCV for model optimization.
• Improved model generalization and performance.

7. Model Evaluation
• Accuracy
• Precision
• Recall
• F1-Score

## Results
Best Model: Random Forest & XGBoost
Accuracy: 85.05% & 85.16%

## Author
Jasmeet Singh
