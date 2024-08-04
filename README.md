# House Price Prediction

## Project Overview
This project focuses on predicting house prices based on a given set of features. The process involves data cleaning, feature engineering, dimensionality reduction, and outlier removal. We used various machine learning models to predict house prices and selected the best-performing model. The final model was then saved using Python's pickle module for future use.

### Key Concepts
Data Description
The dataset used for this project includes various features that influence house prices, such as the number of bedrooms, size of the house, location, and more. The target variable is the house price.

Project Workflow
1. Data Cleaning
Handled missing values.
Removed unnecessary columns.
Corrected data types where necessary.
2. Feature Engineering
Created new features to improve model performance.
Transformed categorical variables into numerical formats using one-hot encoding.
3. Dimensionality Reduction
Applied techniques like PCA (Principal Component Analysis) to reduce the number of features while retaining important information.
4. Outlier Removal
Identified and removed outliers to improve model accuracy.
5. Data Visualization
Used Matplotlib to create various plots (scatter plots, histograms, etc.) to understand data distribution and relationships between variables.
6. Model Selection and Training
Implemented multiple machine learning models:

1. Linear Regression (LR)
2. Decision Tree Classifier (DTC)
3. Lasso Regression

Split the data into training and testing sets.
Trained each model and evaluated their performance using appropriate metrics.

7. Model Evaluation
Compared the models based on performance metrics like RMSE, R², etc.
Selected the best-performing model for house price prediction.

8. Saving the Model
The best-performing model was saved using Python's pickle module for later use in predictions.

Results
The model with the best performance was identified and used to predict house prices.
The final predictions were stored and can be used for further analysis.
