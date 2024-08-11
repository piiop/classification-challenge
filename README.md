# classification-challenge
# Module 13 Challenge
This is the challenge assignment for Bootcamp Module 13. This used starter code provided by the bootcamp.

## Instructions

### Background
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

### Instructions
This challenge consists of the following subsections:

Split the data into training and testing sets.

Scale the features.

Create a logistic regression model.

Create a random forest model.

Evaluate the models.

Split the Data into Training and Testing Sets
Open the starter code notebook and then use it to complete the following steps.

Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csvLinks to an external site. into a Pandas DataFrame.

In the appropriate markdown cell, make a prediction as to which model you expect to do better.

Create the labels set (y) from the “spam” column, and then create the features (X) DataFrame from the remaining columns.

note
A value of 0 in the “spam” column means that the message is legitimate. A value of 1 means that the message has been classified as spam.

Check the balance of the labels variable (y) by using the value_counts function.

Split the data into training and testing datasets by using train_test_split.

Scale the Features
Create an instance of StandardScaler.

Fit the Standard Scaler with the training data.

Scale the training and testing features DataFrames using the transform function.

Create a Logistic Regression Model
Employ your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the scaled training data (X_train_scaled and y_train). Set the random_state argument to 1.

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Create a Random Forest Model
Employ your knowledge of the random forest classifier to complete the following steps:

Fit a random forest classifier model by using the scaled training data (X_train_scaled and y_train).

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Evaluate the Models
In the appropriate markdown cell, answer the following questions:

Which model performed better?

How does that compare to your prediction?

