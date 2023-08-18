# deep-learning-challenge

Utilizing my understanding of Pandas and the StandardScaler() function from scikit-learn, I performed data preprocessing on the dataset.

Dropped the non-beneficial ID columns EIN and NAME.
The target variable for the model was labeled "IS_SUCCESSFUL" and has the value of 1 for yes and 0 for no. 
Application data was analyzed and Classification value was used for binning. 
The Application type and Classification columns contained an excessive amount of unique values which were then broken into smaller buckets of unique values.

In the original model AlphabetSoupCharity.ipynb file the accuracy rate was 72%. 
After a few attempts to to improve accuracy rate, I reached 74% in the optimization model.
This was after adding another hidden layer and lowering epochs.
In another optimization model I increased the number of neurons, however I did not see an increase in the accuracy rate.

In conclusion, I believe more testing is required to reach a 75% or higher accuracy rate.
