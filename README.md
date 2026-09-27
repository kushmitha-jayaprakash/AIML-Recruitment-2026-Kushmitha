# AIML-Recruitment-2026-Kushmitha

## 1. Candidate Details
- **Name:** J Kushmitha
- **Register Number / ID:** RA2611003010871
- **Year of Study:** 1st Year

## 2. Tasks Completed
- **Task 1:** Data Exploration & Preprocessing (Auto MPG Dataset)
- **Task 2:** Linear Regression Model Implementation

## 3. Problem Statement
To preprocess and clean the Auto MPG dataset by handling missing values and duplicates, performing basic statistical analysis, and implementing a Linear Regression model from scratch to predict vehicle fuel efficiency (MPG) based on vehicle weight.

## 4. Approach
1. **Task 1:** Read data via standard `csv` module, identify missing `'?'` values in horsepower, impute missing values using median horsepower, convert strings to appropriate numerical types, remove duplicate rows, and calculate aggregations by origin.
2. **Task 2:** Extract `weight` as feature $X$ and `mpg` as target $Y$, perform an 80/20 train-test split with a fixed seed (`random_state=42`), calculate slope ($m$) and intercept ($c$) using closed-form analytical formulas on training data, and evaluate predictions on test data using MAE, MSE, and RMSE.

## 5. Technologies Used
- Python 3
- `csv` library
- `random` library

## 6. Results
- **Median Horsepower:** 93.5
- **Regression Equation:** Predicted MPG = (m * Weight) + c
- **Evaluation Metrics:**
  - MAE  (Mean Absolute Error): 3.8411
  - MSE  (Mean Squared Error):  24.3484
  - RMSE (Root Mean Squared Error): 4.9344

## 7. Key Learnings
1. How to perform data cleaning and median imputation using standard Python libraries without pandas.
2. How to derive linear regression slope ($m$) and intercept ($c$) analytically using formula summation.
3. The importance of splitting data into train and test sets to evaluate model performance on unseen data.

## 8. Challenges
- **Handling Missing Values:** Handled `'?'` missing data strings by converting valid values to floats, sorting, calculating median explicitly, and replacing missing entries.
