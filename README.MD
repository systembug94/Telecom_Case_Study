
# Telecom Churn Case Study

## Business Problem
A telecom industry attempts to minimize revenue leakage by preventing its customers from switching to other operators. Since it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has become even more important than customer acquisition.

To reduce customer churn, telecom companies need to predict which customers are at a high risk of churn. The aim is to analyze customer-level data and build predictive models to identify customers at high risk of churn, and identify the main indicators of churn in the Indian and Southeast Asian markets where prepaid services are predominantly used.

We will consider usage-based churn, which deals with customers who have not done any usage over a period of time. A potential shortcoming of this definition is that when the customer has stopped using the services for a while, it may be too late to take any corrective actions to retain them.

In the Indian and Southeast Asian markets, approximately 80% of revenue comes from the top 20% of customers (called high-value customers). Thus, if we can reduce the churn of high-value customers, we will be able to reduce significant revenue leakage.

The business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. To do this task well, understanding the typical customer behaviour during churn will be helpful.

## Goal
Retaining high profitable customers

## Installation
To run this project, you will need to have Python installed on your computer. You can download Python from [here](https://www.python.org/downloads/).

Once you have Python installed, you can install the necessary libraries by running `pip install -r requirements.txt` in your command prompt or terminal.

## Usage
To use this project, you will need to import the necessary libraries. Here is a list of libraries that are used in this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.decomposition
- sklearn.preprocessing
- sklearn.linear_model
- sklearn.feature_selection
- imblearn.over_sampling
- statsmodels.api
- sklearn.model_selection
- sklearn.metrics
- statsmodels.stats.outliers_influence
- sklearn.tree
- sklearn.ensemble

You can then run the code in a Python interpreter or Jupyter notebook.
