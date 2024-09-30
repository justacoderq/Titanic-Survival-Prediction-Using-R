# Titanic Survival Prediction using R

## Overview
This project predicts the survival of Titanic passengers using the famous Titanic dataset. By analyzing key features like age, gender, class, and more, we aim to build a machine learning model that forecasts the likelihood of survival. The project is developed using R, with data preprocessing, feature engineering, and model building using Random Forest.

## Dataset
The dataset consists of the following:
1. **train.csv** - Training data containing features and survival labels.
2. **test.csv** - Test data for making predictions.
3. **gender_submission.csv** - Sample submission file for reference.

## Project Structure
- **Data Loading**: Loading both training and test data into R.
- **Feature Engineering**: Creating new features like titles, family size, and deck from the dataset.
- **Missing Value Imputation**: Handling missing data using imputation techniques.
- **Modeling**: Building and evaluating a Random Forest classifier to predict survival.

## Tools Used
- **R**: For data manipulation, visualization, and modeling.
  - Libraries: `dplyr`, `ggplot2`, `mice`, `randomForest`, `scales`

## Steps
1. **Data Cleaning**: Handling missing values, imputing ages, and filling missing embarked data.
2. **Feature Engineering**: Extracting titles from names, creating family size features, and more.
3. **Model Building**: Using Random Forest to predict survival and visualize feature importance.
4. **Prediction**: Making predictions on the test dataset and saving results.

## Key Insights
- **Title Importance**: Extracted titles play a significant role in determining survival.
- **Family Size**: Smaller families have higher survival chances, while larger ones are at more risk.
- **Class Influence**: As expected, passengers in higher classes had better survival rates.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
