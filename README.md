# Cardiovascular-Risk-Prediction
![image](https://github.com/vks2268/Cardiovascular-Risk-Prediction/assets/117895012/bb4289d0-0965-4230-8e9c-dbad654510aa)

# Problem Statement

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict wheater the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are demographic, behavioral, and medical risk factors.

# Introduction:

* Cardiovascular diseases (CVDs) are the major cause of mortality worldwide. According to WHO, 17.9 million people died from CVDs in 2019, accounting for 32% of all global fatalities.
* Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death.
* As a result, it is critical that we accurately predict the risk of heart disease in order to avert as many fatalities as possible.
* The goal of this project is to develop a classification model that can predict if a patient is at risk of coronary heart disease (CHD) over the period of 10 years, based on demographic, lifestyle, and medical history.

In this project we present our analysis of the data. We have employed some of the most widely used classification algorithms for this project namely;

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

# EDA

In EDA we divided analysis into several part to get better idea about data like we checked distribution of numerical and categorical data checked relationship between independent and dependent variable. We used box plots to visualize how each feature was distributed over each of the two target classes. This gave us a clear idea as to which variable was contributing more. We also used bar plot to check the distribution of category of the independent variable into dataset and also checked their relationship with dependent variable to understand what factors are contributing for different cause.

# Feature Engineering

After that we perform feature engineering, in feature engineering we created some new feature from available features with the goal of simplifying and speeding up data transformation while also improving model performance. Then we used oversampling technique to handle class imbalance to make classes even for training model. As our data was highly Imbalance, We used Random Over Sampler Technique to balance our training set before training model.

After feature engineering we selected feature to use to train our model and encoded categorical variables as ML model works with numerical data to do computation. We used label encoding and one hot encoding.

# Model training and testing

Finally we started the machine learning part on the choosen feature subsets, did cross validation for each of the models' hyperparameters and recorded the performance in each case into a compact dataframe. The evaluation metrics we chose for our project include roc_auc score, precision, recall, f1-score Benchmarked XGBoost Classifier algorithm against Logistic Regression, Decision Tree and Random Forest.
