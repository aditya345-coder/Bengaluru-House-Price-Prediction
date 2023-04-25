# Bengaluru House Price Prediction

This is a group project on predicting house prices in Bengaluru, India using Python for data analysis, Flask for the back-end, and HTML, CSS, and JavaScript for the front-end.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Web Application](#web-application)
- [Files and Folders](#Files-and-Folders)
- [Conclusion](#conclusion)

## Introduction

In this project, we aim to build a machine learning model that can accurately predict house prices in Bengaluru based on various features such as location, area, number of bedrooms, etc. We will be using Python for data analysis and machine learning, Flask for the back-end, and HTML, CSS, and JavaScript for the front-end of our web application. Our model was trained on several algorithms, including Linear Regression, Decision Tree, and Lasso, and the best accuracy was achieved using Linear Regression.

## Data

We obtained our dataset from Kaggle, which contains information on various houses in Bengaluru, such as their location, area, number of bedrooms, and more. The dataset can be found here: [kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

## Data Preprocessing

Before building our machine learning model, we performed several preprocessing steps on our dataset, including handling missing values, removing outliers, and encoding categorical variables. We used Python and the Pandas library for these tasks.

## Data Visualization

To gain a better understanding of our dataset, we created several visualizations using Python and the Pandas profiling library. We visualized the distribution of various features, the correlation between features, and more.

## Model Building

For our machine learning model, we trained several algorithms, including Linear Regression, Decision Tree, and Lasso, using Python and the Scikit-learn library. We evaluated the performance of each algorithm and found that Linear Regression gave the best accuracy.

## Model Evaluation

To evaluate the performance of our model, we used the `.score` method. We also created visualizations to compare the predicted and actual house prices.

## Web Application

To create a user-friendly interface for our model, we built a web application using HTML, CSS, and JavaScript for the front-end and Flask for the back-end. Users can input the features of a house, and our model will predict the price.

## Files and Folders
- .idea: Contains configuration files for the PyCharm IDE.
- client: Contains the front-end of our web application, built using HTML, CSS, and JavaScript.
- Dataset: Contains the dataset we used for training our machine learning model.
- Model: Contains the Python file that has Data Analysis Process, machine learning model we trained.
- server: Contains the back-end of our web application, built using Flask.
- requirement.txt: Contains a list of Python packages required to run our project.
- readme: Contains information about our project and how to use it.

## Conclusion

In conclusion, we were able to build a machine learning model that can accurately predict house prices in Bengaluru. We used several algorithms to train our model and found that Linear Regression gave the best accuracy. We also created a web application to make our model accessible to users. We took reference for this project from this playlist: [YouTube](https://youtube.com/playlist?list=PLeo1K3hjS3uu7clOTtwsp94PcHbzqpAdg).
