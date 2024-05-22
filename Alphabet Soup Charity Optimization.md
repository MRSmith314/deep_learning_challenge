# Alphabet Soup Charity Optimization Report

## Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing
Using Pandas and scikit-learn's StandardScaler the data was preprocessed for the variables needed to identify and drop the non-beneficial columns ('EIN', 'NAME', and 'SPECIAL_CONSIDERATIONS'). Further preprocessing involved identifying counts of Application Types and Classifications to determine the appropriate binning for low counts in these columns. Finally, get_dummies was used to cnvert the categorical columns to numerical values.

What variable(s) are the target(s) for your model?
The target variable was "Is_Successful".

What variable(s) are the features for your model?
The variable features for the model are "Ask Amount", Application Type, Affiliation, Classification, Use Case, Organization, Income Amount, and Ask Ammount.

What variable(s) should be removed from the input data because they are neither targets nor features?
The variables removed were the EIN, NAME and Special_Considerations.

Compiling, Training, and Evaluating the Model
The data was trained on the "IS_SUCCESSFUL" features using SciKit Learn StandardScalar in order to normalize the input data. The model was then defined using the input features and 2 hidden layers with several attempts using differing number of nodes in order to optimize the accuracy for the test data.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
The number of nuerons varied from 50 - 200 in many trials with 2 hidden layers.  Less than 100 neurons were used for the analysis since the accuracy rate did not change with high nunber of neurons.

Were you able to achieve the target model performance?
A target of 75% accuracy was not achieved. The highest accuracy performance obtained was 73%
