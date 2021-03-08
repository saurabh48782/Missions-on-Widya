## Level - Beginner
### Problem Description
We have to predict the prices of a stock in future by building a predictive model using Linear Regression.

#### Microtask-1 Data Collection and Analysis
- Using the quandl API for collecting the stock price data.
- Use pandas library to read the CSV file
- Analye the features present in the dataset
**Assessment Question: How many features (columns) are there in the given dataset?**

**Answer:** 12

#### Microtask-2 Data Manipulation and Feature Engineering
- Evaluate the features and drop those columns that are redundant or are irrelevant
- Add new features using feature engineering
- Impute the NaN fields inside the dataset

**Assessment Question: Which symbil is used for shift method in the current scenario (+ or -)?**

**Answer:** -

#### Microtask-3 Build & Train your ML model
- Divide the dataset into dependent features (X) and independent features (Y)
- Scaling of the features
- Split the dataset into two parts using 'train_test_split' function in sklearn.
- Make a prediction model using Linear Regression algorithm available in sklearn.
- Train the model using the train set.
**Assessment Question: What is the name of the class in which linear regression classifier is present in sklearn?**

**Answer:** LinearRegression

#### Microtask-4 Test your model
- Check out the performance of the model using the accuracy metrics.
- Calculate the mean squarred error of your model on the test set.

**Assessment Question: What is the MSE of your model?**

**Answer:** 1.2371561355237783

#### Microtask-5 Knowledge Eval

**Question 1: Which evaluation metric is better to be used to evaluate a model while modelling a continuous output variable?**

**Answer:** MSE

**Question 2: What is the method to convert a dataframe to numpy array?**

**Answer:** to_numpy

**Question 3: What kind of data is used in classification problem in ML?**

**Answer:** Categorical data

**Question 4: Quandl helps you detect data related to?**

**Answer:** Stock Markets
