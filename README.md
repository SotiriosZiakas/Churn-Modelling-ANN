# Churn-Modelling-ANN 

In this project I use the Churn Modelling dataset which containes information about a bank's customers and the goal is to predict whether the customer left the bank or is still a member.

----
The dataset consists of the following features:

1) CustomerId
2) Surname
3) CreditScore
4) Geography
5) Gender
6) Age
7) Tenure
8) Balance
9) NumOfProducts
10) HasCrCard
11) IsActiveMember
12) EstimatedSalary
13) Exited

To solve this problem I use **Artificial Neural Networks** and my work includes the following steps:

1. Data Preprocessing where I use:
    * *LabelEncoder* to encode the Gender column
    * *OneHotEncoder* to encode the Geography column
    * *train_test_split* to split the data into training and test sets
    * *StandardScaler* to scale the features
  
2. Building the ANN
3. Training the ANN
4. Making predictions and evaluating the model

As a small application, I predict whether a new single customer will leave the bank or not based on his information.

