# Neural Network Charity Analysis

## Analysis:

The purpose this analysis is to ensure that the financial-backing of a non-profit organization distributes funds to third parties effectively. In the past after recieving funding, beneficiaries have simply dissappeared without a trace; effectively stealing the money and not keeping their promises. Understandably, the non profit wishes to minimize risk via machine learning. To do so, we classified data to help predict what third party entities are most likely to utilize given funds appropriately. 

## Results

* What variable(s) are considered the target(s) for your model?
  * The variable considered the (y) variable AKA "target" is: "IS_SUCCESSFUL".
* What variable(s) are considered to be the features for your model?
  * The variables considered features by my model are Application type, affiliation, classification, organization, income amount, user case, and status.
* What variable(s) are neither targets nor features, and should be removed from the input data?
 * EIN and name were neither targets nor features and should be removed from the input data.
 
### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * the initial model contained 1 input layer, 3 hidden layers and 1 output layer with a sigmoid activation function attached 
* Were you able to achieve the target model performance?
 * The initial model recieved a 77% accurracy rating without any optimization. 
* What steps did you take to try and increase model performance?
 * I tried to increase model performance by decreasing the number of features. It worked in the opposite manner and decreased accurracy to 68%.
 * 
## Summary

#Reccomendation

The intial model outputted an acceptable accurracy rating on its own. If I was to add a reccommendation to this process, I would reccommend experimenting with other classification models to see if one could increase accurracy percentage.

