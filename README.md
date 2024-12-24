https://github.com/Sejald24/Medical-Insurance-Price-Prediction-

Medical Insurance Price Prediction Project



**Steps Undertaken:**



**Objective:**

To predict the cost of medical insurance premiums based on customer data using regression models.


**Dataset:**

medical_insurance.csv: Contains information about customers (e.g., age, BMI, smoking status, region).


**Data Preprocessing:**

Cleaned the dataset by handling missing values and removing duplicates.
Identified and addressed influential features using Cook’s Distance.


**Exploratory Data Analysis (EDA):**

-Performed detailed analysis using visualizations (scatter plots, box plots, correlation heatmaps) to uncover patterns and relationships between features (e.g., BMI, smoking status, and charges).
-Gained key insights: Smoking and BMI significantly influence insurance charges.

**Feature Engineering:**
-Applied One-Hot Encoding for categorical variables (e.g., region, smoker).
-Performed Backward Feature Selection to identify the most relevant features for prediction.


**Model Building:**

-Trained multiple regression models:
 Linear Regression
 Ridge Regression
 Lasso Regression
 Support Vector Regression (SVR)
 Random Forest Regressor
-Achieved the best accuracy score of 89.5% with Random Forest Regressor.


**Prediction:**

-Used the trained Random Forest model to predict medical insurance charges on new input data.


**Outcome:**

Successfully predicted insurance prices with high accuracy, providing valuable insights into the factors driving premium costs.

