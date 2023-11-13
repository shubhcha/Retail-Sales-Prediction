**1#Retail-Sales-Prediction**

Machine Learning : Regression Project

We are provided with historical sales data for 1,115 Rossmann stores. We have to create a Machine Learning model to predict the sales.

**Introduction**

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

This project include Exploratory data analysis, Data preprocessing, Feature Engineering, Model building and evaluation. The models we used are Linear Regressor, Lasso Regressor, Ridge Regressor, DecisionTree Regressor, RandomForest Regressor. For evaluating the model we use MSE, RMSE, RMPSE, R2 score.

**DATASET INFORMATION**

This dataset consist of two csv files:

Rossmann.csv - Data including sales Rossmann.csv file

Store.csv - Data about the store Store.csv file

**Approach to the Project**

**1.Data Collection and Cleaning**

Check for duplicate values in the dataset

Checking null values

Examining the dataset to get basic informations

Performed data cleaning to handle missing values and ensure data consistency.

Merging the two dataset

**2.Exploratory Data Analysis**

Using different interactive plots made needed analysis

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Extracted meaningful insights to inform future decision-making in the machine learning pipeline.

**3.Feature Engineering**

Nullvalue Treatment

Outlier Treatment

Encoding

Multicolenearity

Feature Scaling

Feature Selection

5.Model Evaluation

**4 Evaluation matrics are used for the evaluation of the Models.**

Split the preprocessed data into training and testing sets.

Utilized a variety of machine learning algorithms, including linear regression, decision trees, random forests.

Employed regularization techniques (e.g., Lasso, Ridge) for improved model performance.

MSE - Mean squared error

RMSE - Root mean squared error

RMPSE - Root mean squared percentage error

R2 - R squared

**5.Conclusion**

Developed a comprehensive machine learning pipeline that combines data processing, feature engineering, and model evaluation.

Overall, this project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. The insights gained from the analysis provide valuable information for decision-making within the retail industry.
