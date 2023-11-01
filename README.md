# Future-sales-prediction ADS-_PHASEWISE SUBMISSION
# Future Sales Prediction using Machine Learning
# Overview:
     This repository contains code and resources for a machine learning project that predicts future sales for a retail company. By analyzing historical sales data and various features, the machine learning model forecasts sales for future periods. 
     This README will guide you through the steps to run the code and make future sales predictions.

# Table of Contents
    Prerequisites
    Installation
    Data Preparation
    Training the Model
    Making Predictions
    Evaluation
Before you can run the code, you will need the following prerequisites:

    Python (>=3.6)
    Pip (Python package manager)
    Jupyter Notebook 
# Installation
# Clone this repository to your local machine:
    git clone https://github.com/imridd/future-sales-prediction.git
# Navigate to the project directory:
     cd future-sales-prediction
# Install the required Python packages:
    pip install -r requirements.txt
    # Data Preparation
    To train and test the model, we'll need to prepare our data. The data should include historical sales data and relevant features.
    Here's how we prepared the data:
    We took the dataset from kaagle: 
    Here is the link:
     https://www.kaggle.com/datasets/chakradharmattapalli/future-salesprediction
# PREPROCESSING DATA
               We can use the following functions for the data pre-processing. They are
          •	Readcsv()
          •	Head()
          •	Tail()
          •	Shape
          •	Columns
          •	Column to list
          •	Isnull
# Training the Model
    To train the model, follow these steps:

    Open a terminal and navigate to the project directory.

# Run the following command to train the model:
    python train.py

    The trained model will be saved in the "models" directory.
# Making Predictions
 After training the model, you can make future sales predictions using it. 
    Follow these steps:

    Update the configuration file with the necessary information, such as the prediction date range.

# Run the following command to make predictions:
     python predict.py
    The predictions will be saved in the "predictions" directory.
# Evaluation
     To evaluate the model's performance, you can use metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). 


    After training the model, you can make future sales predictions using it. 
