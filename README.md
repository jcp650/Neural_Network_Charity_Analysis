# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to to create a binary classifier that predicts the success of different types of startups if funded. This task was accomplished by using pandas to organize the data and tensorflow neural networks for predictions in jupyter notebook.

## Results

### Data preprocessing
- The "is successful" column was used as the target for the model
- The features columns are:
  - application type
  - classification
  - use case
  - status
  - income amount
  - special conisderations
  - organization
  - ask amount
- The removed columns that are neither targets nor features are the "name" column and the "EIN" column

### Compiling, training, and evaluating the model
- For the third optimization, I added a third hidden layer and increased the amount of neurons for the first two layers
- I was not able to increase the model performance to the 75% target.
- For the first optimization, I dropped the "organization" column. The model statistics are as follows:
