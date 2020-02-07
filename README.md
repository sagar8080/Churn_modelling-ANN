# Churn Modelling using ANN

## Aim :
create a geographic segmentation model to tell which of the customers are at highest risk of leaving.

### Business Problem: 
Dataset of a bank with 10,000 customers measured lots of attributes of the customer and is seeing unusual churn rates at a high rate. Want to understand what the problem is, address the problem, and give them insights. 10,000 is a sample, millions of customer across Europe. 

Took a sample of 10,000 measured six months ago lots of factors (name, credit score, grography, age, tenure, balance, numOfProducts, credit card, active member, estimated salary, exited, etc.). For these 10,000 randomly selected customers and track which stayed or left.

Valuable to any customer-oriented organisations. Geographic Segmentation Modeling can be applied to millions of scenarios, very valuable. (doesn't have to be for banks, churn rate, etc.). Same scenario works for (e.g. should this person get a loan or not? Should this be approved for credit => binary outcome, model, more likely to be reliable). Fradulant transactions (which is more likely to be fradulant)

# Steps
  * Training the ANN with Stochastic Gradient Descent 
  * First layer - input layer 
  * Step 1: Randomly initialise the weights to small numbers close to 0 (but not 0)
  * Step 2: Input the first observation of the dataset in the input layer, each feature in one input node (11 input nodes)
  * Step 3: Activation function hidden layer (rectifier), sigmoid (good for output layer)
  * Step 4: Compare the predicted result o the actual result, measure the generated error
  * Step 5: Back-propagation - learning rate decideds how much we update the weights
  * Step 6: update the weights after each observation
  * Step 7: Train
