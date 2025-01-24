# Customer Credit Card Churn Prediction

![Customer Churn Prediction](https://camo.githubusercontent.com/d1346722bf2d371d306e2a5e00511a7c67d37326ea155974b36a8f18669b8a2e/68747470733a2f2f696d616765732e756e73706c6173682e636f6d2f70686f746f2d313539393035303735313739352d3663646161666263323331393f697869643d4d5877784d6a4133664442384d48787761473930627931775957646c6648783866475675664442386648772533442669786c69623d72622d312e322e31266175746f3d666f726d6174266669743d63726f7026773d3131303026713d3830)

## Project Goal: 
This project aims to predict customer churn—whether a customer will stop using the bank’s credit card services—based on their demographic and account information.

## Dataset Information

The dataset contains information about 10,000 bank customers, including features such as age, credit score, geography, and more. It consists of 14 features, and the target variable is whether or not the customer has exited (churned). This model will help banks gain insights into customer behavior and identify potential churners, ultimately improving customer retention strategies.

## Features

The dataset includes the following features:
- `RowNumber`: Row number of the customer in the dataset
- `CustomerId`: Unique customer identifier
- `Surname`: Customer’s surname
- `CreditScore`: Customer’s credit score
- `Geography`: Customer’s country of origin
- `Gender`: Customer’s gender
- `Age`: Customer’s age
- `Tenure`: Number of years the customer has been with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of products the customer has with the bank
- `HasCrCard`: Whether the customer has a credit card (1 if yes, 0 if no)
- `IsActiveMember`: Whether the customer is an active member (1 if yes, 0 if no)
- `EstimatedSalary`: Customer’s estimated salary
- `Exited`: Target variable (1 if the customer has churned, 0 if the customer has not)

## Libraries

The following libraries were used to analyze and model the dataset:
- `pandas`: Data manipulation and cleaning
- `matplotlib`: Visualization of data
- `keras`: Deep learning framework to build the neural network model
- `tensorflow`: Backend for building the neural network
- `scikit-learn`: Data preprocessing, model training, and evaluation

## Model

A basic Artificial Neural Network (ANN) model is used for predicting customer churn.

### Model Accuracy
The model achieved an accuracy of 86.0% on the test data, indicating high predictive performance.

## Conclusion

This project demonstrates the potential of using artificial neural networks to predict customer churn and help banks improve their customer retention strategies.
