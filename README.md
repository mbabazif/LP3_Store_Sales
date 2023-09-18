# Corporation Favorita Sales Prediction

### Project Objective

This is a time series forecasting problem that predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer. This project involves predicting future sales for a grocery retailer based on historical sales data and other relevant information. Time series forecasting techniques are used to analyze patterns in the data and make predictions about future sales trends. The goal is to help the retailer optimize inventory management and make informed decisions to improve sales and profitability.

### Data Understanding

train.csv

The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.

store_nbr identifies the store at which the products are sold.

family identifies the type of product sold.

sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).

onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv

The test data, having the same features as the training data. You will predict the target sales for the dates in this file.

The dates in the test data are for the 15 days after the last date in the training data.

transaction.csv

Contains date, store_nbr and transaction made on that specific date.
sample_submission.csv

A sample submission file in the correct format.
stores.csv

Store metadata, including city, state, type, and cluster.

cluster is a grouping of similar stores.

oil.csv

Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)
           
### Project Structure

The project's primary focus is the analysis and interpretation of the provided data, with the aim of deriving meaningful insights and drawing conclusions from the analysis. The following steps outline the project's workflow:

Data preprocessing

EDA

Feature Engineering

Research on stationary test

perform stationary test

Training and evaluate 4 models

Advanced model evaluation

Predict on test data


## Usage

Clone the repository.

Install the necessary libraries listed in the requirements file.

Run the provided scripts to preprocess the data and perform the machine-learning tasks.

Examine the results and analyses in the notebook or scripts.
