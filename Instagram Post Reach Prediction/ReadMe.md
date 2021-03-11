## Level - Beginner
### Problem Description
We have a dataset that has been taken from instagram and we have to build a prediction model such that it can predict, how many people the post will reach at a particular timeframe depending on number of followers.

#### Microtask-1 Introduction to Machine Learning and Scikit-Learn module

**Assessment Question: Your features or columns in the dataset should have only ___________ to ensure that the ML model is built in the right manner.[Fill in the blank]**

**Answer:** numbers

#### Microtask-2 Data Collection & Cleaning
- Download the dataset available in CSV format
- Use pandas library to read the CSV file
- Visualize the dataset
- Drop irrelevant columns
- Time since posted column should be preprocessed to make it into integers

**Assessment Question: What is the output variable in the dataset?**

**Answer:** Likes

#### Microtask-3 Build your ML model
- Use train_test_split to split the dataset for training and evaluation
- Use Linear Regression algorithm in sklearn to build the model  

**Assessment Question: Which function do you use to split your dataset in sklearn?**

**Answer:** train_test_split

#### Microtask-4 Make Predictions

- Make prediction on the validation set
- Calculate the MSE of the model

**Assessment Question: What is the final MSE value that your model computed? Round off to 2 decimal places.**

**Answer:** 541.01 (for my model)
