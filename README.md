# Diabetes Prediction Analysis

## Problem Statement
The goal of this analysis is to determine whether a patient will develop diabetes within five years based on certain medical records. This analysis uses patient demographic, medical history, and lifestyle data to predict the onset of diabetes. The dataset describes the medical records for Pima Indians, with fields including the number of times pregnant, plasma glucose concentration, diastolic blood pressure, triceps skinfold thickness, 2-hour serum insulin, body mass index, diabetes pedigree function, age, and the diabetes class variable.

## Data Description
- **preg**: Number of times pregnant
- **plas**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- **pres**: Diastolic blood pressure (mm Hg)
- **skin**: Triceps skin fold thickness (mm)
- **test**: 2-Hour serum insulin (mu U/ml)
- **mass**: Body mass index (weight in kg/(height in m)^2)
- **pedi**: Diabetes pedigree function
- **age**: Age (years)
- **class**: Class variable (1: tested positive for diabetes, 0: tested negative for diabetes)

## Techniques for Analysis
1. **Data Cleaning and Preprocessing**: Handling missing values, normalization, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Analyzing data distributions and relationships using visualizations.
3. **Feature Engineering**: Creating new features that can enhance model performance.
4. **Predictive Modeling**: Building machine learning models such as logistic regression, decision trees, random forests, and gradient boosting.
5. **Model Evaluation**: Using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to evaluate model performance.
6. **Cross-Validation and Hyperparameter Tuning**: Optimizing model parameters using cross-validation and grid search techniques.

## Findings
### Exploratory Data Analysis (EDA)
- Continuous variables' distributions and boxplots.
- Correlation heatmap.
- Data cleaning and handling of missing values.

### Most Important Features
Based on the feature importance from the Random Forest model, the most important features are:
1. **Plasma glucose concentration**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
2. **Body mass index**: Body mass index (weight in kg/(height in m)^2)
3. **Age**: Age (years)
4. **Diabetes pedigree function**: Diabetes pedigree function

### Model Performance
- **Logistic Regression**:
  - Accuracy: 0.7359
  - Precision: 0.6173
  - Recall: 0.6250
  - F1 Score: 0.6211
  - ROC AUC: 0.7099

- **Decision Tree**:
  - Accuracy: 0.7056
  - Precision: 0.5600
  - Recall: 0.7000
  - F1 Score: 0.6222
  - ROC AUC: 0.7043

- **Random Forest**:
  - Accuracy: 0.7576
  - Precision: 0.6463
  - Recall: 0.6625
  - F1 Score: 0.6543
  - ROC AUC: 0.7352

- **Gradient Boosting**:
  - Accuracy: 0.7446
  - Precision: 0.6265
  - Recall: 0.6500
  - F1 Score: 0.6380
  - ROC AUC: 0.7224

- **Best Random Forest Model after Hyperparameter Tuning**:
  - Accuracy: 0.7576
  - Precision: 0.6500
  - Recall: 0.6500
  - F1 Score: 0.6500
  - ROC AUC: 0.7323

### Important Findings
- The most important features in predicting diabetes are Plasma glucose concentration, Body mass index, Age, and Diabetes pedigree function.
- Random Forest provided the best overall performance after hyperparameter tuning.
- Logistic Regression, Decision Tree, and Gradient Boosting models also showed competitive performance.

## Suggestions for Next Steps
- Further feature engineering to enhance model performance.
- Testing additional machine learning algorithms.
- Conducting a deeper analysis of feature importance.
- Collecting more data for better generalization.

## Link to Notebooks
- [Exploratory Data Analysis](notebooks/EDA.ipynb)
- [Model Building and Evaluation](notebooks/Modeling.ipynb)
