
# Car Price Prediction

Overview
This project focuses on predicting the prices of cars using machine learning techniques. The goal is to develop a model that can accurately estimate the price of a car based on various features such as make, model, year, mileage, and other relevant factors. The dataset used for training and testing the model is sourced from [provide dataset source].

## Table of Contents
#### Getting Started
Make sure you have the foloowing installed on your system-

- python 
- loblib == 1.3.2
- numpy == 1.24.2
- pandas == 2.0.2
- scikit-learn == 1.3.2
- streamlit == 1.28.0
- xgboost == 2.0.1

You can also get this libraries in requirements.txt

####. Data Collection
- You can get the data set in any online site. I mostly prefered Kaggle.

#### Data Preprocessing
- Checking missing values
- Handle null values
- Preparing the data Prediction
- removing outliers
- Handle inappropiate data types

####  Exploratory Data Analysis(EDA)
- Plotting some sort of graphs and charts to get a short Overview of the data.

#### Feature Engineering
- In this step we are manage all the categorical column before puting the data int the model.
- Encoding the categorical Variables

#### Model Training
- Splitting the dataset into test data and train data
- Importing the model
- Fiting the data into model
- Testing the Prediction
7. Model Evaluation
- Checking the accuracy of the model in comparison various ML  algorithms.

#### Save the Model  
- Saving the model for deployment
- Saving the model in JSON fdromat for deployment on streamlit
## Deployment
The Deployment phase is cricial. To complete this phase follow following steps-
- Create app.py or main.py
  This the file which consist of the GUI of our model
- Put given three files into one folder
  - Car_Price_Prediction.ipynb
  - main.py
  - xgb_model.json
  - require2.txt or requirement.txt
- Now go to the same folder and open command prompt into it. Now run the following command
  streamlit run main.py
  ![WhatsApp Image 2023-11-22 at 6 41 04 AM (1)](https://github.com/Deepesh0289/Car-Price-Prediction/assets/76846273/7f0398c9-260d-4caf-9c97-7ff2d62c5771)

  - Then enter your email
  - After entering your email you will be redirected to the interface of your application

### Now Your Project is Complete

# This Repository is Under Construction.

