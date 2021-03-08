## Level - Beginner
### Problem Description
We have to build a predict the prices of a Bitcoin by building a predictive model. Before making a model, we are required to go through a series of steps like data collection,
data exploration, data cleaning and then we will make our predictive model.

#### Microtask-1 Introduction to Numpy, Pandas and Requests module
**Assessment Question: How do you install the pandas module using pip3? Mention the entire commnad.**

**Answer:** pip3 install pandas

#### Microtask-2 Data Collection
- Download the dataset available in CSV format
- Use pandas library to read the CSV file
- Now using Pandas find the 1024th value in the column 'btc_market_price'.

**Assessment Question: What is the 1024th value in the column 'btc_market_price'?**

**Answer:** 13.6888

#### Microtask-3 Eploratory Data Analysis
If we notice the dataset 'btc_market_price' column is our target column
- Plot a jointplot using the seaborn library and see which features have great correlation with the target column.

**Assessment Question: What feature shows a perfect correlation with 'btc_market_price', i.e., a Pearson correlation equal to 1?**

**Answer:** btc_market_cap

#### Microtask-4 Data Cleaning
If we notice many features in the dataset consists of NaN values, we need to remove these NaN rows either by dropping these fields or by Data imputation.
- Fill the NaN fields with some values like mean, median or mode.

**Assessment Question: What function in Pandas allows you to fill cells in a column that have NaN values? Just mention the name of the function.**

**Answer:** fillna

#### Microtask-5 Model Formulation & Predictions
- Split the dataset into two parts using 'train_test_split' function in sklearn.
- Make a prediction model using Linear Regression algorithm available in sklearn.
- Train the model on the training set and evaluate the model on the test set and finally compute the 'Mean Squarred Error'.   

**Assessment Question: What is the MSE of your model? Round off to the nearest integral value.**

**Answer:** 429 (for my model)
