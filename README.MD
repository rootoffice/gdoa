# Gradient descent variants
* Batch gradient descent
* Stochastic gradient descent(SGD)
* Mini-batch gradient descent

# Gradient descent optimization algorithms
* Momentum
* Nesterov accelerated gradient(NAG)
* Adagrad
* Adadelta
* RMSprop
* Adam
* AdaMax
* Nadam

# Tricks
* Gradient noise
  >adding this noise makes networks more robust to poor initialization and 
  helps training particularly deep and complex networks. added noise gives 
  the model more chances to escape and find new local minima.
* Shuffling and Curriculum Learning
  >avoid providing the training examples in a meaningful order to our 
  model as this may bias the optimization algorithm.  it is often a good 
  idea to shuffle the training data after every epoch.
* Batch normalization
  >reestablishes these normalizations for every mini-batch and changes 
  are back-propagated through the operation as well. 
* Early stopping
  >Geoff Hinton: "Early stopping (is) beautiful free lunch"
* Parallelizing and distributing
  >the ubiquity of large-scale data solutions and the availability of 
  low-commodity clusters.

# Paper or Literatures
Some source about Gradient Gescent Optimization Algoritms. You can obtain 
some source click [here](./link.md).
