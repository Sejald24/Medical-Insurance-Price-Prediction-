https://github.com/Sejald24/Medical-Insurance-Price-Prediction-

Medical Insurance Price Prediction Project


**1. Objective:**

The primary goal of the project was to predict medical insurance premiums for individuals based on their demographic and health-related attributes. This could help insurance companies estimate premiums accurately and provide insights into the factors driving insurance costs.



**2. Dataset:**

Source: The dataset contained features like:

Demographics: Age, Gender, Region.

Health Indicators: BMI, Smoking status.

Target Variable: Insurance Charges.

Size and Characteristics: Describe the dataset (number of rows, features, etc.).


**4. Key Steps Taken:**

**Data Preprocessing:**

**Cleaning:**

Checked for missing values and duplicates to ensure data quality.

Addressed anomalies, like outliers, using Cook's Distance.

**Encoding:**

Applied One-Hot Encoding to categorical variables (e.g., Gender, Smoker, and Region).

**Scaling:**

Used normalization/standardization for continuous variables like BMI and Age for models sensitive to feature scaling.

**Exploratory Data Analysis (EDA):**

Used visualizations like scatter plots, box plots, and heatmaps to identify key trends:

Smoking significantly increased premiums.

Higher BMI values were correlated with higher charges.

Region had less influence compared to smoking and BMI.


**Feature Engineering:**

Removed statistically insignificant features using Backward Elimination based on p-values.
Ensured the model used only relevant predictors, improving performance and interpretability.

**Modeling:**

Tried various regression models, including:
Linear Regression: Baseline model to understand feature relationships.
Regularization Models: Ridge and Lasso for handling multicollinearity.
Support Vector Regression (SVR): For better handling of non-linearity.
Random Forest Regressor: Performed the best, achieving an accuracy of 89.5%.


**5. Model Evaluation:**

Used metrics like:
R-squared: To measure the goodness of fit.
MAE & RMSE: To quantify prediction errors.
The Random Forest Regressor was selected for deployment due to its balance of accuracy and robustness.


**6. Challenges and Solutions:**

Challenge: High variance in insurance charges due to smokers.

Solution: Introduced smoker as a categorical variable and ensured feature encoding preserved information.

Challenge: Outliers in insurance charges caused by extreme BMI or age.

Solution: Detected and mitigated using Cook's Distance.


**7. Outcome and Insights:**

**Outcome:**

-Predicted insurance charges with high accuracy.

-Delivered a model that could generalize well to new data.

**Insights:**

-Smokers pay significantly higher premiums than non-smokers.

-BMI and age are strong predictors, while region has limited impact.

**8. Value Proposition:**

-This model can assist insurance companies in:

-Risk assessment and premium pricing.

-Identifying customer segments to target for health interventions.

**10. Takeaways:**

-Learned how to handle real-world data (e.g., outliers, categorical features).

-Gained expertise in feature selection, EDA, and model evaluation.

-Strengthened skills in regression techniques and improving model accuracy.




