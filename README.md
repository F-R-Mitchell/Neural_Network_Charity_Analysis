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
I had 3 layers for the network, two hidden layers, one with 80 nodes and the other with 30 nodes, and  an output layer. The hidden layers has the relu activation function and the output layer has the sigmoid activation function. I created the number of nodes and number of layers to avoid underfitting and overfitting, the model has a decent accuracy as seen below. Even though the accuracy is relatively good, I would like to create a model with a higher accuracy due to the high amount of funds involed. Overall, I dont think I achieved the target.


![model_acc](https://user-images.githubusercontent.com/87910875/149022997-4aae2d0a-fc98-486a-a2d2-2ae80702eb80.png)


I created three models and was unable to increase the accuracy to over 75%. The three models are displayed below.

![attempt_1](https://user-images.githubusercontent.com/87910875/149023504-b73cc613-8879-434a-8aa8-1530aa8a4f84.png)

* Number of layers: 5
* Number of nodes per layer from first to last: 100, 100, 50, 3
* Activation function of each layer from first to last: relu, tanh, relu, softmax

![attempt_2](https://user-images.githubusercontent.com/87910875/149023934-3373f8c6-682f-4e31-aeca-d81a8e59118f.png)

* Number of layers: 4
* Number of nodes per layer from first to last: 50, 50, 50
* Activation function of each layer from first to last: tanh, tanh, tanh, sigmoid

![attempt_3](https://user-images.githubusercontent.com/87910875/149023942-6cf63b89-a1a5-45ef-910c-dd8ae0c7deb3.png)

* Number of layers: 5
* Number of nodes per layer from first to last: 100, 100, 50, 3
* Activation function of each layer from first to last: relu, relu, relu, sigmoid 
