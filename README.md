# Kaggle Competition Practice

### Housing Prices Competition 
[Kaggle Housing Prices Competition Link](https://www.kaggle.com/c/home-data-for-ml-course/overview/description)

**Objective**: Predict the sales price of individual residential property in Ames, Iowa from 2006 to 2010. For each Id in the test set, a prediction value should be populated for the SalePrice variable.

Disclaimer: `submission.csv` is not coded for optimal prediction yet. Currently the file has a high Root-Mean-Squared-Error (RMSE) score between the logarithm of the predicted value and the logarithm of the observed sales price. 


---


### Titanic Competition 
[Kaggle Titanic Competition Link](https://www.kaggle.com/c/titanic)

**Objective**: Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck by using passenger data (ie name, age, gender, socio-economic class, etc).

Notes on Submissions: 
- `first-submission.csv` 
	- Model: Random Forests
	- Features: Ticket class, Gender, number of siblings/spouses aboard the Titanic, number of parents / children aboard the Titanic
	- Categorization accuracy score: 0.59569

- `second-submission.csv`
	- Model: Random Forests
	- Features: Ticket class, Gender, number of siblings/spouses aboard the Titanic, number of parents / children aboard the Titanic
	- Used Hyperparameter Tuning - GridSearchCV
	- Categorization accuracy score: 0.76555

- `third-submission.csv`
	- Model: Logistic Regression
	- Features: Ticket class, Gender, number of siblings/spouses aboard the Titanic, number of parents / children aboard the Titanic
	- Used Hyperparameter Tuning - GridSearchCV
	- Categorization accuracy score: 0.77511