# Deep-Learning-for-HFT
Implementation of the first Deep Reinforcement Learning algorithm for Active High Frequency Trading

## Overview
We train DRL agents to trade one unit of Intel Corporation stock by employing the Proximal Policy Optimization algorithm. The training is performed on three contiguous months of high frequency Limit Order Book data, of which the last month constitutes the validation data. In order to maximise the signal to noise ratio in the training data, we compose the latter by only selecting training samples with largest price changes. The test is then carried out on the following month of data. Hyperparameters are tuned using the Sequential Model Based Optimization technique. We consider three different state characterizations, which differ in their LOB-based meta-features. Analysing the agents' performances on test data, we argue that the agents are able to create a dynamic representation of the underlying environment. They identify occasional regularities present in the data and exploit them to create long-term profitable trading strategies. Indeed, agents learn trading strategies able to produce stable positive returns in spite of the highly stochastic and non-stationary environment.

# Paper Implemented 
https://arxiv.org/abs/2101.07107
