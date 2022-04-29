# Asset-Pricing-using-Deep-Neural-Network
Given: A monthly stock price returns for 690 months (about 58 years) has been provided The dataset has 64 features after pre-processing A total of 18719 stocks  Goal: To predict the stock return accurately for 42 years by creating the portfolio to sell bottom 10% stocks and buy top 10% stocks The model prediction is evaluated by Sharpe Ratio

# StockPrice-Prediction
1.Introduction
2.Objective
3.Why Neural Networks
4.Hyperparameters tuning
5.Challenges
6.Learnings
# Introduction
We are provided with monthly stock price returns for 58 years, number of stocks is 18719 and we are provided with a dataset of these having 64 features to be modelled with. We are predicting the stock returns for 42 years, creating portfolio to buy top 10% and sell bottom 10% and determining portfolio returns for 42 years. Sharpe ratio is calculated for 42x12 months. Annualized sharpe ratio is then calculated.

# Objective
1.The objective is to explore the hyperparameters of deep neural networks to understand the intuition behind the final architecture 2.End goal of the tuning is to have the sharpe ratio more than 5.2 and the R-square ratio to be around 0 using different hyperparameters

# Why Neural networks
Non-linear relationship

Huge data availability

Fit highly complex data using large number of parameters

Infer relationships well on unseen data

Proven very effective in many applications

# Hyperparameters considered
Number of Layers Number of Neurons Optimizer Activation function Batch Size Learning rate Patience for early stopping

Hyperparameters analysis
#1 (comment) #2 (comment)

# Challenges encountered
Gradient Vanishing problem Gradient Exploding problem Running time Memory error due to large datasets

# Overall Learnings
It is very important to use our intuition while training the deep neural networks as it is not practical to use all the possible combinations There are new combinations that have been tried Kernel Initializer Encountered Vanishing Gradient descent Encountered Exploding Gradient descent Importance of Dropout Alternate activation functions The Modelling exercise is all about trying different parameters and understanding the directions  “We learned a lot about what not to do!!”    - Deep Learning thoughts

Thank You!
