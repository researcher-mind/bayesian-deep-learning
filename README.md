# bayesian-deep-learning
Bayesian inferences with neural networks

We learn how to use bayesian theorem and incorporate it with a simple neural network architecture to sample out uncertainties.

Firstly, we know that deep learning networks are prone to overfitting and they become "overconfident" in predicting. Now since mst of the networks have "softmax" as their activation function in the output, the networks are forced to predict. But we cannot really know if they are confident or not.
Hence, instead of having point estimates for weights and baises , we like to have a numerous range of values for these parameters , plug it our network and make a 
"new" model with each set of new weights and baises and then average them. Bayesian neural networks are actually a special case of ensemble learning.

The jupyter notebook attached has further details about variational bayes for finding the "surrogate" posterior distribution and ELBO used as loss function to train Bayesian neural network

Requires following packages:

1. PyTorch
2. Pyro
3. Numpy
4. Matplotlib


