# Binary-Prediction-of-Poisonous-Mushrooms
Kaggle Playground Series - Season 4, Episode 8

## File Explanations
- main.ipyb - code
- submission.csv - submission file for the competition
- the dataset is too large to be posted here, but you can find the train and test files [here](https://www.kaggle.com/competitions/playground-series-s4e8/data)

## Overview

This project involves building a machine learning model to classify mushrooms as either edible or poisonous based on various attributes. The dataset includes features such as cap color, gill color, habitat, and more.

## Libraries Used

- Numpy
- Pandas
- Scipy
- Matplotlib
- Scikit-learn
- XGBoost
- CatBoost

## Steps Performed

1. **Data Loading**: Loading train and test datasets.
2. **Data Analysis**: Basic explorations such as shape, info, null value checks, and duplication checks.
3. **Feature Importance**: Performed Chi-square test of independence to identify relevant features.
4. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables.
   - Performed feature engineering to create interaction terms and ratios.
   - Scaled numerical features using StandardScaler.
5. **Modeling**:
   - Used `XGBClassifier` and `CatBoostClassifier` with specific hyperparameters optimized for the dataset.
   - Implemented a voting classifier that combines predictions from both models.
6. **Evaluation**:
   - Used metrics such as accuracy, confusion matrix, and classification report to evaluate models.
7. **Submission**:
   - Predicted test set labels and prepared a submission file.

## Models Used

- **XGBoost Classifier**
- **CatBoost Classifier**
- **Voting Classifier**: with XGB and CAT

## Results

The models were evaluated using accuracy, and the ensemble approach provided a robust prediction on the test data.
The final competition was 98.359%.

![image](https://github.com/user-attachments/assets/4c0ff6fa-5b56-4d8a-90a8-0a58b7347b5d)


