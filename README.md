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
- [.idea](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/tree/main/.idea): Contains configuration files for the PyCharm IDE.
- [client](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/tree/main/Client): Contains the front-end of our web application, built using HTML, CSS, and JavaScript.
- [Dataset](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/tree/main/Dataset): Contains the dataset we used for training our machine learning model.
- [Model](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/tree/main/Model): Contains the Python file that has Data Analysis Process, machine learning model we trained.
- [server](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/tree/main/Server): Contains the back-end of our web application, built using Flask.
- [requirement.txt](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/blob/main/requirement.txt): Contains a list of Python packages required to run our project.
- [readme](https://github.com/aditya345-coder/Bengaluru-House-Price-Prediction/blob/main/README.md): Contains information about our project and how to use it.

## Conclusion

In conclusion, we were able to build a machine learning model that can accurately predict house prices in Bengaluru. We used several algorithms to train our model and found that Linear Regression gave the best accuracy. We also created a web application to make our model accessible to users. We took reference for this project from this playlist: [YouTube](https://youtube.com/playlist?list=PLeo1K3hjS3uu7clOTtwsp94PcHbzqpAdg).

## Screenshots:
## Step1-
In order to test this project on your local pc, first open the main folder in pycharm, in the terminal of it enter command `cd Server` so as to go inside the Server. Now run the server.py by entering the following command `python server.py`. Now the server will start. *NOTE:* Do not close pycharm, but you can minimize it.
![Screenshot (207)](https://github.com/karti3k/tournament-style-guide-html-css-webpage/assets/97697722/7e456a6c-ca8d-4fab-a6c8-b337414d3ba9)

## Step2- 
Now you can open the same main folder(i.e Benguluru-House-Price-Pridiction folder) that you opened it using pycharm, this time using vs code editor. When you vs code editor opens, you meed to navigatge to the Client folder, from there you need to open html css and js file in different tabs as shown in the screenshot below. And if you have the live server extension installed then you need to click on go live as shown (but note among the 3 tabs opened for html, css and js file: you html tab must be clicked, then click on go live button.
![Screenshot (210)](https://github.com/karti3k/tournament-style-guide-html-css-webpage/assets/97697722/3d03fceb-4025-4cf1-83bd-1514930f0608)

## It will be displayed as the screenshot below:
![Screenshot (205)](https://github.com/karti3k/tournament-style-guide-html-css-webpage/assets/97697722/452e322b-68da-4895-b658-ada771b25c4d)

## Finally:
You can choose the enter the square feet you want for your house and then can select the number of bhk and bathroom and finally can select your favourite location. On clicking the Estimate Price button, The estimated price for your house will be infront of your eyes.
![Screenshot (206)](https://github.com/karti3k/tournament-style-guide-html-css-webpage/assets/97697722/0fb4e205-0248-47eb-b6b4-554e81978b2f)
