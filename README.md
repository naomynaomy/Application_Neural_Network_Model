# Funding Application Classifier - Deep Neural Network

Purpose:  To use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.

# Technologies 

* Jupyter Notebook
* Tensorflow
* Keras: Dense, Sequential
* SKlearn: train_test_split, StandardScaler, OneHotEncoder
* Pandas

# Preprocessing Data Process

1) Drop unnecessary columns from dataframe
2) Create a list of catergorical variables
3) Encode the categorcal variables using OneHotEncoder and create dataframe
4) Concat numerical variables from original dataframe to the one-hot encoded dataframe from step 3
5) Create features (X) and target (y) datasets

Concatenated dataframe:

https://user-images.githubusercontent.com/112917950/226462334-4150ba6f-8c9b-4a89-9d69-a6dc3bf3a866.mov

# Deep Neural Network Model Comparisons

## Description

Model 1 nn - Deep neural network 2 hidden layers, activations "relu"


Model 2 nn_A1 - Deep neural network 3 hidden layers, activations "tanh"


Model 3 nn_A2 - Deep neural network 3 hidden layers, activations "relu"


## Shape

- Model 1 (nn)

<img width="576" alt="Screenshot 2023-03-20 at 1 51 22 PM" src="https://user-images.githubusercontent.com/112917950/226462958-7a02aae7-d551-457d-8902-e6ad171a7bb6.png">

- Model 2 (nn_A1)

<img width="576" alt="Screenshot 2023-03-20 at 1 51 46 PM" src="https://user-images.githubusercontent.com/112917950/226463051-95388df8-0b70-4938-b5a3-458b8b93ae12.png">

- Model 3 (nn_A2)

<img width="576" alt="Screenshot 2023-03-20 at 1 52 08 PM" src="https://user-images.githubusercontent.com/112917950/226463130-d851e486-9f40-4da0-9f06-a03ecf2d5297.png">

## Loss Accuracy Results

- Model 1 (nn)

<img width="813" alt="Screenshot 2023-03-20 at 1 54 11 PM" src="https://user-images.githubusercontent.com/112917950/226463551-723bba91-d454-4f4a-81f4-6c77f72cb0aa.png">

- Model 2 (nn_A1)

<img width="813" alt="Screenshot 2023-03-20 at 1 54 41 PM" src="https://user-images.githubusercontent.com/112917950/226463634-0593b0f8-836e-47ce-9151-cde6d2e03751.png">

- Model 3 (nn_A2)

<img width="813" alt="Screenshot 2023-03-20 at 1 54 55 PM" src="https://user-images.githubusercontent.com/112917950/226463694-dc721eec-5ac8-4f76-9829-143c7c0f3103.png">


# Conclusion 

Model 2 had the highest accuracy of 0.7306122183799744
