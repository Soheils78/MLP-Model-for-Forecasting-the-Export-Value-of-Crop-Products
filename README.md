# Multilayer Perceptron Model for Forecasting Export Value of Crop Products

This repository contains the implementation of a Multilayer Perceptron (MLP) model designed to 
forecast the export value of crop products three years into the future. 
The project was completed as part of the Machine Learning coursework for my master’s degree at the University of Sussex.


## Project Overview
The Main goal of this project is to develop a neural network model capable of predicting the export value of
agricultural products based on historical data. The dataset comprises multiple indicators related to 
food and agriculture, collected across several categories. The forecasting task involves training 
a Multilayer Perceptron (MLP) model using this data to provide accurate export value predictions.

### Key Features

•	**Algorithm**: Multilayer Perceptron (MLP)
•	**Task**: Regression (Time-Series Forecasting)
•	**Dataset**: 13 CSV files covering various indicators related to agriculture and food production
•	**Objective**: Forecast export values for three years into the future


## Dataset

The dataset used in this project are 13 CSV files, each representing a 
distinct category of variables relevant to food and agriculture. 
The dataset is sourced from the FAOSTAT database and covers the following categories:

  1.	Consumer Price Indicators
	2.	Crops Production Indicators
	3.	Emissions
	4.	Employment
	5.	Exchange Rate
	6.	Fertilizers Use
	7.	Food Balances
	8.	Food Security Indicators
	9.	Food Trade Indicators
	10.	Foreign Direct Investment (FDI)
	11.	Land Temperature Change
	12.	Land Use
	13.	Pesticides Use


## Data Structure

Each CSV file includes historical records of various indicators, 
with common columns for `Country` (which showing area in the files) and `Year`. But, 
the number of rows and columns are diffrent across files due to 
variations in the data coverage period and the number of sub-categories.

## Installation

To run this project from locally, make sure you have _Python_ installed. Then, install the required Python packages which 
is mentioned in `requirements.txt` file. 









