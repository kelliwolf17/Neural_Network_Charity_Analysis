# Neural_Network_Charity_Analysis

# Overview
The purpose of this analysis is to create a model that will determine whether or not the 34,000 organizations Alphabet Soup's business team has data on will be successful if funded by Alphabet Soup.

# Results

## Data Preprocessing
* What variable(s) are considered the target(s) for your model?
  * IS_SUCCESSFUL
* What variable(s) are considered to be the features for your model?
  * APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* What variable(s) are neither targets nor features, and should be removed from the input data?
  * EIN and NAME

## Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
 * basic model: layer1=100, layer2=50 | I was trying to achieve higher accuracy with more layers and a high number of neurons. The same idea was applied to optimized model.
* Were you able to achieve the target model performance?
 * In the optimized model, I could only reach 73% accuracy. 
* What steps did you take to try and increase model performance?
 * I added more layers, and tried several different neuron variations.

# Summary
