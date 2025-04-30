# MGT 665 Comprehensive Assessment Question 2

## Problem

In this problem, I am using a dataset from Kaggle named [weight-height.csv](https://www.kaggle.com/datasets/mustafaali96/weight-height?resource=download) to predict an individual's weight based on their gender and height. 

## Dataset

The dataset contains 10,000 individuals and their gender, weight, and height. Weight and height are numeric variables, and I convert gender (male or female) into a numeric variable as well by encoding. 

## Methodology

I split the dataset up into testing and training, and then built a Logistic Regression model using the training set, and predicted the weight values using the testing set.

## Results

Using the MSE, we can see that our model is relatively accurate, but has room for improvement. The plot of actual vs predicted weights also shows that the regression model is relatively accurate in its predictions. I am sure that the model performance can be improved using feature engineering or further tuning the model. Models like these can be useful in healthcare to accurately and effectively identify treatment plans for patients.
