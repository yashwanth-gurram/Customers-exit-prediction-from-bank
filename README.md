# Customer Churn Prediction from Bank: Project overview
The project was build from a very well known kaggle dataset https://www.kaggle.com/shrutimechlearn/churn-modelling, we can use deep learning models to observe the customer exit patterns from the bank.
This data set contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer left the bank (closed his account) or he continues to be a customer.

## Code and Resources Used
**Python Version**: 3.7

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn, pickle

## Model building
* First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
* I tried an ANN model with two hidden layers and used  *he-uniform* for weight initialization.
* Compiled using *adam optimizer* and evaluated them using *binary cross-entropy*.

## Model Performance
* The model achieved an accuracy of 86% after performing 100 epochs.

![](https://github.com/yashwanth-gurram/Customers-exit-prediction-from-bank/blob/master/Images/churn.png)
