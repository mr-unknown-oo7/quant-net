# quant-net
This repository holds the code and description used to train a quantized spiking neural network with straing through estimator technique

 This project has trained a 4 layer spiking neural network on MNIST dataset with weight of each later quantized between -8 and 8 into 32 levels. The training of the model was done using a straight to estimator technique to overcome the dead neuron problem due to the heaveside function The model has achieved a mean accuracy of 92\% along with an accuracy of 94\% while training and a weighted f1 score of 0.92.
