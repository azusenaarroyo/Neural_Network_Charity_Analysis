# Neural_Network_Charity_Analysis

## Overview of the Analysis
The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing
* The IS_SUCCESSFUL variable is the target for the model.
* The features for the model are; APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* EIN and NAME variables are neither targets or features.

### Compiling, Training, and Evaluating the Model
* I added three hidden layers with eight, four, and two neurons respectively.
* I was not able to achieve the target model performance of 75% accuracy.
* I tried adding a third hidden layer, changing activation function to sigmoid, and increasing the number of epochs to 200.

## Summary 
The optimized model has a 53% accuracy and a loss of 69%.
