# -Predictive-Modeling-for-Customer-Churn

Data set is attached by the name of bank.csv and test.csv

ANALYSIS
I have used different Machine Learning Models to detect that how many customer are 
churn or not.
To choose which variable is best for model feature selection was used. Top variable comes 
out are -
'duration', 'job_blue-collar', 'job_entrepreneur', 'job_retired','job_self-employed', 
'job_services', 'job_technician', 'job_unemployed','marital_married', 'marital_single', 
'education_unknown', 'housing_yes','loan_yes.
The Model Built are Logistic Regression Model, Decision tree and Random Forest. Random 
forest and Random Forest model perform best on train as well as on test data.
The performance of the model is checked by ROC AUC score, Accuracy, F1 Score, Precision 
and recall.
FLOW OF ANALYSIS
1. Data cleaning and data manipulation.
 - Check and handle duplicate data.
 - Check and handle NA values and missing values.
 - Drop columns. If it contains large amount of missing values and not used for analysis.
 - Imputation of the values.
2. EDA
 - Univariate data analysis,values_count,distribution of variable.
 - Bivariate data analysis,correlation coefficients and pattern between the variable.
 - Feature Scaling, Creating Dummy Variable, Performed Oversampling.
 - Building Model: Logistic regression, Decision Tree, Random forest Model used for the 
model making and prediction.
 - Validation of the model.


BUSINESS ASPECT


The problem was to detect how many customers churn from the company and how many 
stay. The objective to find is that if we can target which category of customer are more likely 
to churn we can prevent that by providing them coupons or to provide them best offer 
which can help the company to reduce the churn rate. But we cannot provide offers or 
coupons to every customer because it may lead to loss to the company. So to target 
customer who are more likely to churn and provide them offers is good approach. We can 
target customers by making a machine learning model and to find the category we can use 
feature selection approach where we can detect which category of customers are have 
chances to churn.
