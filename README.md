# Neural_Network_Charity_Analysis
## Overview of Project
Working with the Alphabet Soup Charity organization, the goal of this project is to use machine learning to help classify which funding applicants may be successful if they were to receive funding. Looking at previous applicants of 34,000 organizations, this data was used to help us create a prediction model to look for applicants that have an estimated success rate of 75% or more. 

## Results
### Data Preprocessing
During preprocessing, we made our target the Column that was "IS_SUCCESSFUL" as success rate is the main determinate for approving applications. We then determined our features to be APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and STATUS while removing EIN, NAME, SPECIAL_CONSIDERATIONS, and ASK_AMT.

### Compiling, Training, and Evaluating the Model
In round one of processing, the neural network included two hidden layers using the ReLu activation function. This led to about a 72.4 accuracy. After trying optimization by adding a third hidden layer and increasing the neuron per layer, the accuracy decreased. Oh no! 

## Summary
