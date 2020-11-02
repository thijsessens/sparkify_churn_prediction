# sparkify_churn_prediction
Repository for Churn Prediction notebook

# General Overview
This repository contains a notebook which provides a practical machine learning implementation to predict churn using a fictional digital music streaming service called Sparkify.

We are using Spark since the dataset is 12GB and we need the power of distributed machine learning technologies to help us with the heavy lifting.

# Problem statemnt
We have several of our customers leaving. Oh no! Let's try to find a way to predict them leaving before it happens. We will try to use machine learning classification algorithms and the data available to us to get to a solution.

# Data 
The data contains several potentially interesting fields derived from website interaction logs.

![web_app_image](images/schema_view.png) 

# Churn Defintion
In our case, Churn is defined as page == "Cancellation Confirmation".
