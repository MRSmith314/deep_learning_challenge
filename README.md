# deep_learning_challenge
Preprocess data, compile, train, evaluate and optimize NN Model.

# Preprocess Data
Using Pandas and scikit-learn's StandardScaler the data was preprocessed for the variables needed to identify and drop the non-beneficial columns ('EIN', 'NAME', and 'SPECIAL_CONSIDERATIONS'). Further preprocessing involved identifying counts of Application Types and Classifications to determine the appropriate binning for low counts in these columns. Finally, get_dummies was used to cnvert the categorical columns to numerical values.

# Compile, Train, and Evaluate the Model
The data was trained on the "IS_SUCCESSFUL" features using SciKit Learn StandardScalar in order to normalize the input data. The model was then defined using the input features and 2 hidden layers with several attempts using differing number of nodes in order to optimize the accuracy for the test data. 

# Optimize the Model
In attempts to optimize the model addtional columns were dropped and binning values were adjusted The accuracy level could not be optimized to perform with accuracy greater then 73%.

# Contents of Repository
  - Project Report
  - Three .h5 files with results for 3 of multiple trials
  - Three jupyter notebook files with the code for each of the three attempts saved.

# References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.
