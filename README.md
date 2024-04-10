# Deep-Learning-Challenge
## Overview
In this challenge I was tasked to utilize and optimize a deep learning model from the given prompt: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Requirements 
- Reprocess the Data
- Compile, Train and Evaluate the Model
- Optimize the Model
- Write a Report on the Neural Network Model

## Results
### Data Preprocessing
#### What variable(s) are the target(s) for your model?
- The target variable for the model is IS_SUCCESSFUL.
#### What variable(s) are the features for your model?
- The feature variables for the model include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
#### What variable(s) should be removed from the input data because they are neither targets nor features?
- The EIN column was removed from the input data as useful as features or targets.
### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- It was a guess-and-check method to dial in more accuracy. I selected 3 hidden layers, with 5,10, and 1 neurons, respectively with the RELU activation functions. The output layer uses a sigmoid activation function for binary classification and used Relu for other layers.
#### Were you able to achieve the target model performance?
- Yes, I was able to get a final accuracy of 77.29%
#### What steps did you take in your attempts to increase model performance?
- To increase model performance, the following steps were taken:
  - Dropping additional irrelevant columns from the input data.
  - Adding NAME back to the relevant columns
  - Adding more neurons to a hidden layer.
  - Adding or removing hidden layers.
  - Increasing or decreasing the number of epochs in the training regimen.
## Summary
The deep learning model reached a performance of 77.29% which was above teh 75% desired threshold and therefore considered a success from the given parameters.
