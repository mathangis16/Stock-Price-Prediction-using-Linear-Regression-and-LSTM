# SC1015 Project - Stock Market Price Predictor

For a more detailed description of our project, please view this video: 


# Overview

### Problem Statement:
Prediction of stock prices with complete certainty is impossible due to various influencing factors since  financial markets are efficient. However, Machine Learning and Deep Learning techniques such as Linear Regression and LSTM  can be used to predict stock prices with reasonable accuracy for better investment decisions.

In this project, our team explored and implemented **prediction of stock prices using Linear Regression and LSTM**. 

### What we did:
The project aims to compare the accuracy of the two techniques in predicting Apple's stock prices from 2013 to 2023 using the Most Watched Stocks of Past Decade dataset from Kaggle. The historical data for a particular stock (Apple: AAPL) was gathered, cleaned, and split into training and test sets. A linear regression model was trained on the training set, and its performance evaluated using various metrics as seen in the python notebook in this repository. Our team also explored using LSTM using Tensorflow and Keras for more accurate prediction of stock prices, as part of which we normalized, formatted data, and evaluated the outputs using the root mean square error to assess the quality of predictions. 

### Conclusion:
Based on the results that were produced by linear regression vs LSTM, we were able to clearly observe that the LSTM model was able to product visibly better results given its capability to store and remember past information.  
Hence, in order to make more accurate stock price predictions, it is recommended to use deep learning techniques such as LSTM over Linear Regression.


# Tech Stack

### Language: 
* Python


### Libraries:
* Tensorflow
* Keras
* Sklearn
* Numpy
* Pandas
* Seaborn
* Plotly


### Techniques used:
* Linear Regression
* Long Short-Term Memory (LSTM) Neural Network


# A137 Group 2 Repository Contents

### Slides:

The slides provide a quick summary of our project covering the overall aim, data extraction and preparation, our analysis the outputs using linear regression and LSTM, as well as the conclusions we draw from our work.

### Jupyter Notebook:

In an attempt to make it easier to compare and analyze the outputs, we decided to consolidate all our analysis into a single jupyter notebook. This notebook contains our entire code from:

 - Data Extraction, 
 - Data Cleaning, 
 - Data Processing, 
 - Splitting of the dataset into train and test, 
 - Training and testing the model using Linear Regression
 - Assessing the outputs of Linear Regression using Data Visualization techniques learnt in the course
 - Training and testing the model using LSTM
 - Assessing the outputs of LSTM using Data Visualization techniques learnt in the course

# What we learnt

We were able to put everything we learnt in this course into practice such as data extraction, data cleaning, data processing, data visualisation.

We also took this as an opportunity to learn new things. Some of the new things we learnt are:
- sklearn for linear regression
-  [New] Neural Networks (particularly LSTM), Keras and Tensorflow
-  [New] Collaborating using GitHub
