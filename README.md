# Neural_networks

## Purpose of the Analysis
The purpose of this analysis was to create a machine learning model that will predict if an organization that receives funding from AlphabetSoup will be successful.

## Results

### Data Preprocessing
- The target variable in this analsysis is the 'IS_SUCCESSFUL' column.
- The features of this model are 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_TYPE', 'ORGANIZATION', 'STATUS', 'INCOME_AMOUNT', SPECIAL_CONSIDERATIONS', and 'ASK_AMOUNT'.
- The variables that needed to be dropped were 'NAME' and 'EID'.

### Compiling, Training, and Evaluating the Model
- The first time I ran my neural network model. I used 13 nodes, 2 hidden layers, the relu activation function for the inputs and the sigmoid activation function as the output. Using these activation functions, I achieved a 53% accuracy score and a .8 loss score. The model accuracy was below the target accuracy score of 75%, so I tried increasing the amount of nodes to 10 and 7 for the two hidden layers. This lowered the accuracy score to 43%, and also lowered the loss to .7. I tried two more times to increase the accuracy score. I attempted to change the output activation function from sigmoid to softmax, which was unsucessful. Finally, I tried changing the input activation functions from relu to elu, but this did not increase the accuracy either.

## Conclusion
Overall, this model did not accurately predict if an organization given funds by AlphabetSoup would be successful or not. I'd recommend trying an SVM deep learning model because it works well when there are specifically only two outcomes.