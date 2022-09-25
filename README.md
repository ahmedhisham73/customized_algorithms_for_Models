# customized_algorithms_for_Models


1- SGoptimizer is the implementation of Stochastic gradient descent algorithm from scratch , generally gardient descent works as the following equation 


W = W-alpha*dW,

B= B-alpha*dB

where W : is the weights 
alpha is the learning_rate 
dW: gradient 
B:bias 
dB : gradient bias


during Network learning , the Network usually passes through 2 stages 
which are : forward pass and backprop 
during forward pass the network computes its components linearly while the main or the most effective scenario is during backprop 
where in backpropagtion there's a gradient computing so that we cant update the w and b with respect to the loss function provided 
