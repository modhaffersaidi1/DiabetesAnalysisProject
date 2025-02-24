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

### Model Performance
- **Logistic Regression**: Accuracy: X, Precision: X, Recall: X, F1 Score: X, ROC AUC: X.
- **Decision Tree**: Accuracy: X, Precision: X, Recall: X, F1 Score: X, ROC AUC: X.
- **Random Forest**: Accuracy: X, Precision: X, Recall: X, F1 Score: X, ROC AUC: X.
- **Gradient Boosting**: Accuracy: X, Precision: X, Recall: X, F1 Score: X, ROC AUC: X.

### Important Findings
- Certain features showed significant correlations with the target variable.
- Random Forest provided the best overall performance after hyperparameter tuning.

## Suggestions for Next Steps
- Further feature engineering to enhance model performance.
- Testing additional machine learning algorithms.
- Conducting a deeper analysis of feature importance.
- Collecting more data for better generalization.

## Link to Notebooks
- [Exploratory Data Analysis](notebooks/EDA.ipynb)
- [Model Building and Evaluation](notebooks/Modeling.ipynb)
