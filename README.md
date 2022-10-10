# Laptop-Price-Prediction
Problem Statement for Laptop Price Prediction
We will make a project for Laptop price prediction. The problem statement is that if any user wants to buy a laptop then
our application should be compatible to provide a tentative price of laptop according to the user configurations.

# Table of Contents
* Describing Problem Statement

* Overview about dataset
* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Machine learning Modeling
* ML web app development
* Deployment Machine learning app 


# DATA
Now let us start working on a dataset in our Jupyter Notebook. The first step is to import the libraries and load data.
After that we will take a basic understanding of data like its shape, sample, is there are any NULL values present in the dataset.
Understanding the data is an important step for prediction or any machine learning project.

* import numpy as np
* import pandas as pd
* import matplotlib.pyplot as plt

# EDA of Laptop Price Prediction Dataset

EDA helps to perform hypothesis testing. We will start from the first column and explore each column and understand what impact it creates on the target column. 
At the required step, we will also perform preprocessing and feature engineering tasks,our aim in performing in-depth EDA is to prepare and clean data for better 
machine learning modelling to achieve high performance and generalized models,so let's get started with analyzing and preparing the dataset for prediction.

![1 1 ](https://user-images.githubusercontent.com/100569156/194825998-e0c617c3-f2ac-4fe2-a3ab-cccda624621a.png)


# Machine Learning Modeling for Laptop Price Prediction

Now we have prepared our data and hold a better understanding of the dataset. 
so let’s get started with Machine learning modeling and find the best algorithm with
the best hyperparameters to achieve maximum accuracy.

![1 2](https://user-images.githubusercontent.com/100569156/194827371-7744e5b0-9718-4586-948f-eab5d270b95d.png)


# Create Web Application for Deployment of Laptop Price Prediction Model
Now we will use streamlit to create a web app to predict laptop prices. In a web application, 
we need to implement a form that takes all the inputs from users that we have used in a dataset, 
and by using the dumped model we predict the output and display it to a user.


![1 3](https://user-images.githubusercontent.com/100569156/194828503-1788e3d6-a37b-4178-a670-3cf4687c58f8.png)


Now when you run the app file using the above command you will get two URL and it will automatically open the web application 
in your default browser or copy the URL and open it. the application will look something like the below figure.

![1 4](https://user-images.githubusercontent.com/100569156/194833962-f43ddd28-3c6c-4175-a1e2-b524036f37b7.png)
![1 5](https://user-images.githubusercontent.com/100569156/194834114-2f8323c3-f047-427f-be66-97ec72eede9c.png)


Enter some data in each field and click on predict button to generate prediction.
I hope you got the desired results and the application is working fine.
