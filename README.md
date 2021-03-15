# Neural_Network_Charity_Analysis

## Overview of the analysis:
We are requested to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup

## Technology:
Jupyter notebook w/ Pandas, tensorflow and sklearn packages.

## Results:
* "EIN" and "NAME" columns were dropped because there was no contributing data for the model
* The "IS_SUCCESSFUL" column is understood as the target of our model.
* The rest of the columns in the dataset where chosen to be model features.
* For the first attempt the number of neurons in the hidden layers used was 120 neurons(almost triple the number of the features) and 60 neurons in the second layer.  This model has the accuracy of 45.6%
* Second attempt a hidden layer containing 90 neurons was added to the model. Accuracy of this model is 72.6%
* For the 3rd and final attempt the activation function in the hidden layers were changed to "TANH".  The activation function used was "SOFTPLUS" for the output layer.  The accuracy of this model is 72.8%

![Model 3 Structure](https://github.com/basecipher/Election_Analysis/blob/main/Election%20Results.png)

## Summary: 
No models met the 75% standard however the best outcome was rendered by the 3rd model by achieving 72.8% accuracy.

![Best Results - Model 3](https://github.com/basecipher/Election_Analysis/blob/main/Election%20Results.png)
