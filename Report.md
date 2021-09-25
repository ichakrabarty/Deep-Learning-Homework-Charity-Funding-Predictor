### Overview

The purpose of this analysis is to predict whether or not funding certain organizations will yield successful results by developing a deep learning model.

### Results

- Data Preprocessing
  - The target variable is the IS_Successful column of the table.
  - The rest of the columns were the features of the model.
  - EIN and NAME columns are removed because they don't offer any useful data to include in the model.
- Compiling, Training, and Evaluating the Model
  - For the since there are a multitude of features within the model, more than one hidden layer was used and many different nodes were included to account for the complexity. The first layer had a ReLu activation method to return negative values to zero then sigmoid activation function was used since previous nodes were converted to values of 0 and 1.
  - I was close to the target accuracy with the highest accuracy score being .7329 from all my attempts.
  - I tried to increase epochs, different activation methods, and increase layering to attempt to increase the accuracy of the model.

### Summary

Overall, the results obtained was close to the target accuracy, however; there may have been features that were accounted that created bigger outliers and had more effect of lower accuracy of the model. I would look into each of the features more and determine the variability and then make a decision whether or not to keep it as a feature.  
