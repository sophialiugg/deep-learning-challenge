# Module 21 Report

## Background 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this anlysis is to construct a deep learning model utilizing the 'application_df' dataset with the aim of predicting the success of an application based on its features.


## Results: Using bulleted lists and images to support your answers, address the following questions:

  - Data Preprocessing

     1. What variable(s) are the target(s) for your model? 
     The target variable is the "IS_SUCCESSFUL" column
     2. What variable(s) are the features for your model?
     "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".
     3. What variable(s) should be removed from the input data because they are neither targets nor features?
     "NAME" and "EIN". They are neither targets nor features.

  - Compiling, Training, and Evaluating the Model

     1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
     In the initial attempt, I used 80 hidden_nodes_layer1 and 30 hidden_nodes_layer2 and relu as the activation function so that I can work with non-linear models.
     2. Were you able to achieve the target model performance? I was not able to achieve the 75% accuracy.
     3. What steps did you take in your attempts to increase model performance?
     I changed neurons on my other attempts.

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The overall accuracy for the deep learning model was about 72% to 73%. The most accurate modle in my different attempts of optimization is my first attempt, with 72.50% of accuracy. Recommendations to help improving the model could include tetsing with different activiation functions and doing more cleanups with the data initially.


