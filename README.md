# Project 8: Machine Learning for Predictive Analytics
## Project : Reducing monthly churn by identifying high risk customers well in advance

__About the Project:__
The project relates to applying predictive analytics on customer churn. A major telecom company’s postpaid business of voice-only plans is struggling to maintain its strong foothold in local market because of:
-	High churn rate amongst customers leading to a revenue decline of ~500k USD every month
-	Decline in overall customer base (high churn rate combined with low acquisition rate), leading to a decline in total market share

### Aim: 
1.	Build a classification model to predict churners one month in advance
2.	Identify key churn drivers

### Hypothesis:
Company CEO believes that existing models can predict churners precisely, but it’s too late to take any retention actions, as customer usage has significantly declined by then.

### Objectives/Exercise:
1.	Perform initial data preparation
a.	Number of customers with zero monthly revenue?
b.	Number of customers with missing values percentage > 5%?
c.	Remove outliers for columns ‘UniqueSubs’ and ‘DirectorAssistedCalls’ is any.
2.	Perform exploratory analysis to analyse customer churn
a.	Do customers with high overage minutes also have high revenue?
b.	Does high number of active subscribers lead to low monthly revenue?
c.	Does credit rating have an impact on churn rate?
3.	Create additional features to help predict churn
a.	Percent of current active subs over total subs
b.	Percent of recurrent charge to monthly charge
c.	Percent of overage minutes over total monthly minutes
4.	Build classification model to predict customer churn
a.	Build a simple logistic regression model to predict churn and evaluate model accuracy on test data set
b.	Build Random Forest classifier to compare model accuracy over the logistic regression model
c.	Identify most important features impacting churn (Model evaluation metrics to be used: GINI, AUC, Precision and Recall)
5.	Use the ‘Prediction Data’ provided to predict churners using the best model identified in step 4
6.	Calculate lift chart and total monthly revenue saved by targeting top 10-20% of the customers using your best predictive model
### Data:
![data](https://github.com/AINE-Projects/Project8/blob/main/data_columns.png)

### Skills to use:
__1.	Exploratory data analysis__

a.	Missing value identification and treatment, outlier detection, etc.

b.	Univariate analysis - histograms to check distribution, box/violin plot, summary stats such as mean, median, mode, etc.

c.	Correlation analysis, scatter plots

d.	Time analysis to monitor trend and seasonality

__2.	Feature engineering__

a.	Target variable creation (dependent variable) - align with the objectives

b.	New feature creation based on business and the objectives

c.	Trend variables such as moving average, st. dev. over time, etc.

__3.	ML model build__

a.	Model type – classification vs regression

b.	Algorithm type – logistic regression, linear regression, Random forest, etc.

c.	Train and test data split (e.g., 70:30 split)

d.	Hyperparameter tuning for model optimization

e.	Feature importance

__4.	Model evaluation__

a.	Model evaluation metrics

b.	Regression – R-Square, Mean Absolute Error (MAE), Mean Square Error 

c.	Classification – Confusion metrics, precision, recall, GINI, AUC, etc.

d.	Lift and Gain charts

e.	Prediction data set for model validation

