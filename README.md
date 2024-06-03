# sales-prediction-using-python

Advertising Data Analysis and Linear Regression Model

This code explores the Advertising.csv dataset to understand the relationship between advertising spend (TV, Radio, Newspaper) and sales. It performs data cleaning, analysis, visualization, and builds a linear regression model to predict sales based on advertising expenditure.

Steps:

Data Loading and Exploration:

Imports libraries (pandas, numpy, etc.)
Reads the Advertising.csv data
Performs initial exploration (shape, data types, missing values)
Drops unnecessary features
Data Visualization:

Creates jointplots to visualize relationships between advertising channels and sales
Generates a heatmap depicting correlations between features
Data Preprocessing:

Splits the data into features (X) and target variable (y)
Applies standardization (z-score) for numerical features
Train-Test Split:

Splits the data into training and testing sets (70% train, 30% test)
Linear Regression Model:

Creates a Linear Regression model
Fits the model to the training data
Prints model coefficients and intercept
Predicts sales for the test data
Evaluates model performance using:
Root Mean Squared Error (RMSE)
R-squared
Prints the model summary from statsmodels
Next Steps:

Explore other machine learning models like Decision Tree or KNN for comparison.
Consider feature engineering to create new features or improve existing ones.
Perform hyperparameter tuning to optimize the model's performance.
Note:

The code currently focuses on linear regression. Future exploration of other machine learning models can be added.
Key Improvements:

Clearer breakdown of steps
Concise explanation of data preprocessing and model selection
Inclusion of model evaluation metrics (RMSE, R-squared)
Consideration of next steps for further analysis
Consistency in formatting and terminology
