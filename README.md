# Loan-Prediction
Building a Prediction model for banking loan approval 


## Introduction
This project aims to solve a specific problem using machine learning techniques. The code provided in this repository analyzes a dataset and uses XGBoost classifier to predict the status of customers. The goal is to demonstrate the implementation of XGBoost and evaluate the model's performance.

## Libraries and Packages
The following libraries and packages are used in the code:
- Pandas: Data manipulation and analysis
- Matplotlib: Data visualization
- Seaborn: Statistical data visualization
- Scikit-learn: Machine learning library
- XGBoost: Gradient boosting framework

Please make sure to install the required packages using `!pip install <package-name>`.

## Code Explanation
1. Data cleaning: The code starts by cleaning the column names and checking for missing values.
2. Data encoding: The 'SEX' and 'NEW_CUST' columns are encoded using LabelEncoder to convert categorical variables into numeric form.
3. Data scaling: Numeric columns ('AGE', 'MON_IN_OCC', 'INCOM_EXP_GMI', 'LTV', 'TENURE') are scaled using MinMaxScaler.
4. Data visualization: Various visualizations are generated to explore the data, including a heatmap, histograms, and bar plots.
5. Data splitting: The dataset is split into training and testing sets using a 80:20 ratio.
6. Model training and prediction: An XGBoost classifier is trained on the training set and used to predict the target variable on the testing set.
7. Model evaluation: The accuracy, confusion matrix, and classification report are calculated to evaluate the model's performance.
8. Hyperparameter tuning: GridSearchCV is used to find the best hyperparameters for the XGBoost classifier.
9. Train model with best hyperparameters: The XGBoost classifier is retrained using the best hyperparameters obtained from the grid search.
10. Feature importance: The feature importances are calculated and visualized using a bar plot.
11. Final evaluation: The final model's performance is evaluated on the testing set, including the accuracy, confusion matrix, and classification report.

## Results
The XGBoost classifier achieved an accuracy of XX% on the testing set. The confusion matrix and classification report provide detailed insights into the model's performance.

Please refer to the code for more detailed explanations and implementation details.


