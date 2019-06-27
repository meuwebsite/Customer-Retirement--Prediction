# Customer-Retirement--Prediction


![fb](images/cr7.png)


# Background

#### BANK CUSTOMERS RETIREMENT PREDICTIONS USING SUPPORT VECTOR MACHINES

You work as a data scientist at a major bank in NYC and you have been tasked to develop a model that can predict whether a customer is able to retire or not based on his/her features. Features are his/her age and net 401K savings (retirement savings in the U.S.). You though that Support Vector Machines can be a great candidate to solve the problem.


# Goals

* IMPORTING DATA
* VISUALIZING THE DATA
* MODEL TRAINING
* EVALUATING THE MODEL
* IMPROVING THE MODEL


# How to run 

Open Google Colab https://colab.research.google.com/ and in the Navbar go to:
* File
* Upload Notebook
* Run the Cells


# Proccess

Import the data set and visualizing the properties
# 

![fb](images/cr1.png)

With Pairgrid from Seaborn library, vizualizing the data points
#  
![fb](images/cr2.png)

With .count function, vizualing false and positives input
#  
![fb](images/cr3.png)

Transforming the data andSplinting into train and test
#  
![fb](images/cr4.png)

Using Confusion Matrix to Evaluating the Model
#  
![fb](images/cr5.png)

#### Improving the model
* Scalling X_train
* Visualing points for X_train
* Visualing points for X_train_Scalled
#  
![fb](images/cr6.png)


#### Improving even more the model
* Importing Gridsearch  from Sklearn library
* Match best combinations to find the best parameters to the model
* Confusion Matrix with the result
#  
![fb](images/cr7.png)
