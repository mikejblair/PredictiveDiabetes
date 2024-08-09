### Diabetes Prediction Analysis using Python

#### Overview
This repository contains the code and analysis for a capstone project focused on predicting diabetes using a dataset that includes various health indicators such as age, BMI, blood glucose levels, and more. The project was conducted using Python and Jupyter Notebook with MatplotLib, Seaborn, Pandas, Statsmodel.api, and SciKit-Learn, and it highlights key data analytics skills including data cleaning, exploratory data analysis, data visualization, and model building. 

#### Skills and Techniques Used

- **Data Cleaning:**
  - Identified and handled missing values.
  - Removed duplicate records to ensure data quality.
  - Converted categorical variables to numerical ones for easier analysis (e.g., gender and smoking history).

- **Exploratory Data Analysis (EDA):**
  - Analyzed unique values and distribution of categorical variables.
  - Used box plots and descriptive statistics to examine the distribution and detect outliers in numerical variables like age, BMI, HbA1c level, and blood glucose level.
  - Generated histograms and scatter plots to visualize the distribution and relationships between key variables.

- **Data Transformation:**
  - Performed one-hot encoding on categorical variables to prepare them for machine learning models.
  - Managed outliers by calculating interquartile ranges (IQR) and adjusting bounds accordingly.

- **Statistical Analysis:**
  - Conducted correlation analysis to identify the relationships between independent variables and the target variable (diabetes).
  - Employed Ordinary Least Squares (OLS) regression to understand the impact of different variables on diabetes occurrence.

- **Data Visualization:**
  - Created heatmaps to visualize correlations among selected features.
  - Developed bar plots to show the sorted correlation coefficients with diabetes.
  - Visualized model coefficients using bar plots to interpret the logistic regression model results.

- **Modeling:**
  - Built and evaluated a logistic regression model to predict the likelihood of diabetes.
  - Split the data into training and testing sets to validate the model's performance.
  - Assessed the model using accuracy score, confusion matrix, and classification report to gauge its predictive power.

#### Conclusion
This project demonstrates the application of key data analytics techniques from data cleaning and exploration to model building and evaluation. The resulting model provides insights into the factors most strongly associated with diabetes, and the process highlights the importance of thorough data preparation and analysis in predictive modeling.
