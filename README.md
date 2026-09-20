# traffic-linear-regression

## To do (Emily)
[X] Examining attributes and target variable(s): Be sure you clearly understand each of the attributes and the target variable.
[X] Check for highly correlated or redundant variables
[X] check for data inconsistency
[X] convert date time to categories 
[X] Examine the various attributes and convert any categorical ones to numerical ones, if needed. 
[X] Obtain and output summary of the attributes. Are the attributes normally distributed? If not, what could be the reason?
[X] handle outliers
[X] Standardize and normalize the attributes.
[X] Find how the attributes are correlated to each other and the target variable. Perform numerical and visual analysis and output plots and results.
[X] Identify a few important attributes and proceed forward. Do not use all attributes blindly.
[X] Split the data into training and testing parts. The ratio is up to you.
[] update report with pre-processing findings (make sure to include plots and interpretation)
[] state time independence assumption in report
[] explain why certain features aren't normally distributed


## To do (Kendra)
[]

## Code specs/tips
Tasks: data pre-processing, loading, model creation, and results analysis
[] create two different regularized models (Stochastic Gradient Descent using SGDRegressor from scikit-learn and Ordinary Linear Regression using Regularized Linear Regression [fit and fit_regularized] from statsmodel)
[] perform pre-processing
[] include as many plots as possible
[] tune as many hyper paramaters as possible

## Report specs/tips
[] include as many plots as possible
[] **interpret results (Tabular results and visual plots are preferred in all cases followed by your interpretation)**
[] discuss whether regularization helped you improve your model
[] log of experiments with hyper parameters used and results obtained
** Please do not include code or code snippets in your report. Instead, submit them as a separate file

## Submission 
[] Python code file (jupyter notebook)
[] Report file
[] check there is no hard coded file paths

---

Language: Python
Libraries used: ucimlrepo, pandas, seaborn, numpy, matplotlib, scikit-learn, statsmodels

Begin by installing the previously listed libraries. Then, open this Jupyter Notebook in an environment of your choosing.

Each node may be run in order to produce the desired results.

NOTE: 3 nodes will take extra time and processing power to run, since they use GridSearchCV to tune hyperparameters. These nodes are marked with the comment: "# NOTE: Takes extra time to run" at the top.

Additionally, these grid searches use "n_jobs=-1" in order to speed up the process. It is recommended you change this value if that is not preferred.