# House price prediction: Overview
The main aim of this project is to predict the house price based on various features.
## Data Collection
Dataset to downloaded from the below link

<https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data>
## All the Lifecycle In A Data Science Projects¶
1.	Data Analysis
2.	Feature Engineering
3.	Feature Selection
4.	Model Building
5.	Model evaluation
### Libraries Included:
Pandas, numpy, matplotlib, seaborn, sklearn, scipy.

#### Assumptions of regression
Linearity, Homoscedasticity, multivariate normality, multicollinearity all checked before proceeding for regression.

#### EDA
•	**List comprehension**- Used list comprehension throughout the analysis as they are generally more compact and faster than normal functions and loops for creating list.

•	**Plots used** - Histogram, density plot, boxplot,barplot.

•	**Missing values** -Found missing values in both numerical & categorical features.

•	**Distribution of data** - Data distribution seems skewed, outliers detected with the help of boxplot.

•	**Correlation Matrix** – Found features highly correlated to the target variable.

•	**Categorical variable** – With barplot explored relationship between categorical variable & target variable.

![download](https://user-images.githubusercontent.com/66988391/93751140-3c587200-fc1a-11ea-96d2-fa6e67503122.png)

![Capture](https://user-images.githubusercontent.com/66988391/93751586-f059fd00-fc1a-11ea-9ba5-07cc8e467a4a.PNG)



##### Feature Engineering

•	**Missing value treatment**
•	**Transformation**- Transformation of date or year feature as datetime variable. 
•	**Categorical variables** : Handling of rare labels
•	**Skewness treatment with log transformation** - Standardize the values of the variables to the same range.
•	**Label Encoding** –with sklearn’s label encoder converted Categorical data into numeric.
•	**Feature Scaling**- Used sklearn’s minmaxscaler to normalize the data within a particular range.

##### Feature selection

**Used regularization technique** -**Lasso Regression model** for feature selection to enhance the prediction accuracy and to minimize prediction error.


##### Data modeling with selected features

	Prepared data for modeling using train test split from sklearn model selection.

##### Models Used

• **Linear Regression
• **Random Forest**

##### Model Evaluation
•	**MSE
•	R square score**
	
#### Acknowledgments
• Hat tip to anyone whose code was used


















