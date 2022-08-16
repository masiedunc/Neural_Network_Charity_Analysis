# Neural_Network_Charity_Analysis
## Overview of Project
Working with the Alphabet Soup Charity organization, the goal of this project is to use machine learning to help classify which funding applicants may be successful if they were to receive funding. Looking at previous applicants of 34,000 organizations, this data was used to help us create a prediction model to look for applicants that have an estimated success rate of 75% or more. 

## Results
### Data Preprocessing
During preprocessing, we made our target the Column that was "IS_SUCCESSFUL" as success rate is the main determinate for approving applications. We then determined our features to be APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and STATUS while removing EIN, NAME, SPECIAL_CONSIDERATIONS, and ASK_AMT.

### Compiling, Training, and Evaluating the Model
In round one of processing, the neural network included two hidden layers using the ReLu activation function. This led to about a 72.4 accuracy. After trying optimization by adding a third hidden layer and increasing the neuron per layer, the accuracy decreased. Oh no! 

**Round 1:**

![AlphabetSoupCharity1](https://user-images.githubusercontent.com/102122063/184793503-8244db70-2d62-473f-bab9-10947813f6fe.PNG)


**Optimization Attempt 1&2:** Increased nuerons and dropped columns SPECIAL_CONSIDERATIONS and ASK_AMT

![Optimization1](https://user-images.githubusercontent.com/102122063/184793550-be30f287-fe78-4eeb-ae2d-5d71333cb439.PNG)


**Optimization Attempt 3:** Added one more Hidden Layer, using Tanh activation function. 

![Optimization2](https://user-images.githubusercontent.com/102122063/184793612-a7cb19b2-6a66-4b93-b9a1-ef961b86205a.PNG)

## Summary
