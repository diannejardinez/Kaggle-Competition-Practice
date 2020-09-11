# Kaggle Competition Practice

### Housing Prices Competition 
[Kaggle Housing Prices Competition Link](https://www.kaggle.com/c/home-data-for-ml-course/overview/description)

**Objective**: Predict the sales price of individual residential property in Ames, Iowa from 2006 to 2010. For each Id in the test set, a prediction value should be populated for the SalePrice variable.

Notes on Submissions: 
- `first-submission.csv` 
	- Algorithm: Random Forests
	- Features: `['LotArea', 'YearBuilt', '1stFlrSF', '2ndFlrSF', 'FullBath', 'BedroomAbvGr', 'TotRmsAbvGrd']`
	- Root-Mean-Squared-Error (RMSE) score: 22337.06

- `second-submission.csv`
	- Algorithm: Gradient Boosting Regression
	- Features: All table variables
	- Used Hyperparameter Tuning - GridSearchCV
	- Root-Mean-Squared-Error (RMSE) score: 182906.48

- `third-submission.csv`
	- Algorithm: Gradient Boosting Regression
	- Features: `['LotArea', 'YearBuilt', '1stFlrSF', '2ndFlrSF', 'FullBath', 'BedroomAbvGr', 'TotRmsAbvGrd']`
	- Used Hyperparameter Tuning - GridSearchCV
	- Root-Mean-Squared-Error (RMSE) score: 182906.48

- `fourth-submission.csv`
	- Algorithm: Linear Regression
	- Features: `['MSSubClass', 'LotFrontage', 'LotArea', 'OverallQual', 'OverallCond',
       'YearBuilt', 'YearRemodAdd', 'MasVnrArea', 'BsmtFinSF1',
       'BsmtUnfSF', 'TotalBsmtSF', '1stFlrSF', '2ndFlrSF', 'LowQualFinSF',
       'GrLivArea',  'FullBath', 'HalfBath',
       'BedroomAbvGr', 'KitchenAbvGr', 'TotRmsAbvGrd', 'Fireplaces',
        'GarageCars',  'WoodDeckSF', 'OpenPorchSF',
       'EnclosedPorch',  'ScreenPorch', 'PoolArea']`
	- Root-Mean-Squared-Error (RMSE) score: 20476.40	

---


### Titanic Competition 
[Kaggle Titanic Competition Link](https://www.kaggle.com/c/titanic)

**Objective**: Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck by using passenger data (ie name, age, gender, socio-economic class, etc).

Notes on Submissions: 
- `first-submission.csv` 
	- Algorithm: Random Forests
	- Features: `['Pclass', 'Sex', 'SibSp', 'Parch']`
	- Categorization accuracy score: 0.59569

- `second-submission.csv`
	- Algorithm: Random Forests
	- Features: `['Pclass', 'Sex', 'SibSp', 'Parch']`
	- Used Hyperparameter Tuning - GridSearchCV
	- Categorization accuracy score: 0.76555

- `third-submission.csv`
	- Algorithm: Logistic Regression
	- Features: `['Pclass', 'Sex', 'SibSp', 'Parch']`
	- Used Hyperparameter Tuning - GridSearchCV
	- Categorization accuracy score: 0.77511

- `fourth-submission.csv`
	- Algorithm: Random Forests
	- Features: `['Pclass','Sex','Age','Fare','Family_cnt','Cabin_ind']`
	- Used Hyperparameter Tuning - GridSearchCV
	- Categorization accuracy score: 0.78708


	