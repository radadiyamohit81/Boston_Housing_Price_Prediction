## Project: Predicting Boston Housing Prices

# Kaggle Competition Link: 
  https://www.kaggle.com/vikrishnan/boston-house-prices

## Introduction

This repo contains all my work for Project 2 of Udacity's Machine Learning Basic Nanodegree Program. In this project, I applied basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explored the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. Then I analyzed performance graphs for a learning algorithm with varying parameters and training set sizes. This enabled me to pick the optimal model that best generalizes for unseen data. Finally, I tested this optimal model on a new sample and compare the predicted selling price to my statistics.
The main techniques used:
  - Evaluating Model performance
  - Model Evaluation & Validation
  - Model Optimization


## Project Highlights
This project is designed to get you acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of your model.

Things you will learn by completing this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.

## Description
The Boston housing market is highly competitive, and you want to be the best real estate agent in the area. To compete with your peers, you decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, you\'ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients\' homes.

## Software and Libraries
This project uses the following software and Python libraries:

- [Python](https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

## Starting the Project

This project contains three files:

- `Housing Price Prediction.ipynb`: This is the main file where you will be performing your work on the project.
- `data/house_dataset.csv`: The project dataset. You'll load this data in the notebook.

In the Terminal or Command Prompt, navigate to the folder containing the project files, and then use the command `Housing Price Prediction.ipynb` to open up a browser window or tab to work with your notebook. Alternatively, you can use the command `jupyter notebook` or `ipython notebook` and navigate to the notebook file in the browser window that opens. Follow the instructions in the notebook and answer each question presented to successfully complete the project. A **README** file has also been provided with the project files which may contain additional necessary information or instruction for the project.

The dataset for this project originates from the UCI Machine Learning Repository. The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts. For the purposes of this project, the following preprocessing steps have been made to the dataset:

- 16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
- 1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
- The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
- The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.

Thank you...
Happy  Coding :)
