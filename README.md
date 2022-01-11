# Neural_Network_Charity_Analysis

# Overview
The purpose of this project is to create an neural network that can accurately predict whether applicants will be successful if funded by Alphabet Soup. More athn 34,000 organizations have received funding, some have done well with the funds while some haven't.

# Results 
The target variable is the IS_SUCCESSFUL variable which displayed whether the company was successful with their funds


###  Data Preprocessing
The feature variables are :
* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested

The removed varibles are:
* EIN and NAME—Identification columns

###  Compiling, Training, and Evaluating the Model
I had 3 layers for the network, two hidden layers, one with 80 nodes and the other with 30 nodes, and  an output layer. The hidden layers has the relu activation function and the output layer has the sigmoid activation function. I created the number of nodes and number of layers to avoid underfitting and overfitting, the model has a decent accuracy as seen below.


![model_acc](https://user-images.githubusercontent.com/87910875/149022997-4aae2d0a-fc98-486a-a2d2-2ae80702eb80.png)
