# Binary-Prediction-of-Poisonous-Mushrooms
Kaggle Playground Series - Season 4, Episode 8

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

- **XGBoost Classifier**: A gradient boosting framework that uses tree-based learning algorithms.
- **CatBoost Classifier**: A machine learning algorithm that uses gradient boosting on decision trees and handles categorical features intrinsically.
- **Voting Classifier**: An ensemble meta-model that combines predictions from multiple models to improve accuracy.

## Results

The models were evaluated using accuracy, and the ensemble approach provided a robust prediction on the test data.
The final competition was 98.359%.

![image](https://github.com/user-attachments/assets/4c0ff6fa-5b56-4d8a-90a8-0a58b7347b5d)


