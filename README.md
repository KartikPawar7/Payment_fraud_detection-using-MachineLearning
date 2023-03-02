# Payment_fraud_detection-using-MachineLearning

# What is fraud detection?
* Fraud is the crime of getting money by deceiving people, where these kinds of fraud has been around for years and years now in many different ways, but one of the most is Money Fraud in digital world.
* Fraud has become an major issue with regular changes and transformation like scamming, online banking, fake websites, unsecured websites, insurance etc. even through offline.
* Detecting, preventing, and fighting fraud are among the primary concerns in the modern-day world. One of the most effective ways of managing attacks and risks is by using machine learning algorithms for fraud detection. Detecting, preventing, and fighting fraud are among the primary concerns in the modern-day world. One of the most effective ways of managing attacks and risks is by using machine learning algorithms for fraud detection.

# Project objective
* Machine Learning algorithms nowadays has been an action oriented solutions to solve problems using the available relevant data in a faster way possible with accuracy.
* The informations collected across all the platforms especially in Transactions of payments helps in better for alogrithms to spot the behaviours, patterns and learn about the data and provide a best results as possible.

# Datasets 
## About Dataset
To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud. For this task, I collected a dataset from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:

- step: represents a unit of time where 1 step equals 1 hour
- type: type of online transaction
- amount: the amount of the transaction
- nameOrig: customer starting the transaction
- oldbalanceOrg: balance before the transaction
- newbalanceOrig: balance after the transaction
- nameDest: recipient of the transaction
- oldbalanceDest: initial balance of recipient before the transaction
- newbalanceDest: the new balance of recipient after the transaction
- isFraud: fraud transaction

# Tasks
- Understanding Data informations, Data preprossessing to get insights how the data looks like numeric features, categorical vvalues, Size of data etc.
- Data Cleaning to remove missing values, correction in data types, checking balance of the datasets.
- Analyzing different features correlations, Exploratory Data analysis, Features Lable encoding for categorical columns.
- Model Building with Machine learning Algorithms i.e Logistic Regression algorithms, training and testing data, checking accuracy Score.

# Model Performance
- Model has been trained and fitted with 80% of Data points and being tested with remaining 20% of data points.
- Successfully implemented the Logistic Regression algorithm and model has predicted wiht 97% accuracy score to detect the payments being either fraud or not i.e column named isFraud in dataset has value 1 considered as Fraud payment and value 0 is considered as genuine payment.
