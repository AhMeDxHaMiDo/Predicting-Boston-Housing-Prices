# Predicting-Boston-Housing-Prices
This project is part of Udacity Machine Learning Nanodegree projects.

## Table of Content
1. [Project Overview](#project-overview)
2. [Description](#description)
3. [Prerequisites](#prerequisites)
4. [Starting the Project](#starting-the-project)
    1. [Code](#code)
    2. [Run](#Run)
    3. [Data](#data)



## Project Overview
In this project, we will apply basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. We will first explore the data to obtain important features and descriptive statistics about the dataset. Next, we will properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. We will then analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This will enable us to pick the optimal model that best generalizes for unseen data. Finally, we will test this optimal model on a new sample and compare the predicted selling price to our statistics.


## Description
The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with our peers, we decide to leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. Luckily, we\'ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for our clients\' homes.

## Prerequisites
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

- `boston_housing.ipynb`: This is the main file where you will find the work on the project.
- `housing.csv`: The project dataset. Which is loaded in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project. Do not modify.

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file.

### Run

In a terminal or command window, navigate to the top-level project directory `Predicting-Boston-Housing-Prices/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

* **Features**
    1.  `RM`: average number of rooms per dwelling
    2. `LSTAT`: percentage of population considered lower status
    3. `PTRATIO`: pupil-teacher ratio by town

* **Target Variable**
    
    4. `MEDV`: median value of owner-occupied homes
