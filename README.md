# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was 

## Results
### Data Preprocessing
* The IS_SUCCESSFUL variable was considered the target for my model.
* The APPLICATION_TYPE, AFFILLIAION, CLASSIFICATION, USE_CASE, INCOME_AMT, and SPECIAL_CONSIDERATIONS variables were considered to be the features of my model.
* EIN, NAME, and ORGANIZATION were neither targets nor features and were removed from my input data.

### Compiling, Training, and Evaluating the Model
* I selected 5 neurons, 2 layers, and the relu activation function for my neural network.
* I was not able to achieve target model performance.  The best performance I could attain was 69% accurracy.
* I tried adding neurons and layers and changing the activation function to increase the performance of my model.  I also removed several features of the data, but 69% accurracy was the best I could attain.

## Summary
To increase the accurracy of my model, I would like to increase my data set.  I would also like to explore the CLASSIFICATION feature more as it includes many different values and the binning of the values might need to be modified for better results.
