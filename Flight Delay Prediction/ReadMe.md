## Level - Intermediate
### Problem Description
We have a dataset that has been collected and published by **DOT's Bureau of Transportation Statistics** and we have to build a prediction model such that it can predict flight delay well in advance.

**Dataset Link**- https://www.kaggle.com/usdot/flight-delays?select=flights.csv 
#### Microtask-1 Data Collection
- Download the dataset available in CSV format
- Use pandas library to read the CSV file
- Take out a subset of data containing only 100000 rows.

**Assessment Question: How many samples got diverted in the sample dataset?**

**Answer:** 224

#### Microtask-2 Exploratory Data Analysis
- Visualize the dataset using Matplotlib and Seaborn library
- Time since posted column should be preprocessed to make it into integers

**Assessment Question: Which feature shows perfect correlation with 'ARRIVAL DELAY'?**

**Answer:** DEPARTURE_DELAY

#### Microtask-3 Data Cleaning and processing
- Drop irrelevant columns having little correlation coefficient
- Impute NaN values inside the rows with the mean of respective columns

**Assessment Question: How many flights got delayed by more than 15 minutes of ARRIVAL_TIME?**

**Answer:** 36221

#### Microtask-4 Model Creation
- Select important features from the dataset and make a decision tree classifier model
- Use StandardScaler to standardise the features.
- Divide the dataset into 70% for training and 30% for testing/validation.

**Assessment Question: How will you fit the method if 'clf' is the instance for the DecisionTreeClassifier algorithm and 'x_train' and 'y_train' are training samples. Write the exact code statement.**

**Answer:** clf.fit(x_train,y_train)

#### Microtask-5 Model Prediction

- Make prediction on the validation set.
- Calculate the AUC_ROC score of the model on validation/test data.

**Assessment Question: What is the ROC-AUC score of your model?**

**Answer:** 99

#### Microtask-6 Knowledge Eval

**Ques.1 What is the method to read csv in Pandas?**

**Answer:** read_csv()

**Ques.2 Which of the libraries is not used for visualization?**

**Answer:** sklearn

**Ques.3 How are null values represented in Pandas?**

**Answer:** NaN

**Ques.4 Which method is used to split data into training and test datasets?**

**Answer:** train_test_split()

**Ques.5 What is the abbreviation of ROC?**

**Answer:** Receiver Operating Characteristics
