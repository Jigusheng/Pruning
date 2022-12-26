# Pruning: A pruning algorithm based on SynaPrune to prune neural networks

The purpose of this repository is to post on a new algorithm in pruning neural networks.

On the other SynaPrune repository, we introduced work done as a measure for significance or contribution by a parameter to the neural network hence loss. Thus, using the same ideology, work done hence significance of a parameter can also be a measure of importance of it hence determining whether we should prune it or not.
In addition, we also make use of regularization techniques by including standard deviation of total work done by a parameter compared to others in the same layer. This helps to minimize the standard deviation and restrict the number of parameters with high work done hence importance thus helps in pruning off more useless parameters.
