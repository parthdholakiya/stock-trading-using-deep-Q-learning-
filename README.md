# stock-trading-using-deep-Q-learning-

![image](https://user-images.githubusercontent.com/94167271/189483542-774f5d27-2ba3-4fed-8514-def5364017fc.png)

Prepare an agent by implementing Deep Q-Learning that can perform unsupervised trading in stock trade. The aim of this project is to train an agent that uses Q-learning and neural networks to predict the profit or loss by building a model and implementing it on a dataset that is available for evaluation.

The stock trading environment provides the agent with a set of actions:

-Buy

-Sell

-Sit

***This project has following sections:***

-Import libraries

-Create a DQN agent

-Preprocess the data

-Train and build the model

-Evaluate the model and agent
 

Dependencies:

***Steps to perform:***

In the section “Creating a DQN agent”, create a class called agent where:

--Action size is defined as 3

--Experience replay memory to deque is 1000

--Empty list for stocks that have already been bought

The agent must possess the following hyperparameters:

--gamma= 0.95

--epsilon = 1.0

--epsilon_final = 0.01

--epsilon_decay = 0.995

Note: It is advised to compare the results using different values in hyperparameters.

--Neural network has 3 hidden layers

--Action and experience replay are defined

 
