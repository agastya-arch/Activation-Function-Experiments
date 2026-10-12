# Activation-Function-Experiments

An experimental study of ReLU and Sigmoid activation functions in a toy neural network built from scratch using NumPy (Check the previous repository). Explores forward propagation, backpropagation, gradient descent, loss convergence, and loss landscape visualisation to compare training behaviour under different activation functions

## Observations

1. When the ReLU activation function was used, the training loss curve dropped sharply while in the case of Sigmoid function, the loss curve dropped gradually.
2. The most important observation of all was that the loss after a 1000 iterations of backpropagation in ReLU was very less (~0.008) compared to the Sigmoid (~0.467).
3. Both ReLU and Sigmoid were able to reduce the training loss, demonstrating that the network can either learn the given three-class dataset using either activation functions.
4. Visualising the loss landscape provides a way to examine how the loss varies with changes in model parameters. The landscapes can help compare the behaviour of the two experiments, depending on how the visualisations were generated.

## Note

1. The results are specific to the chosen dataset, network architecture, initial weights, and training settings. They do not establish that Sigmoid generally outperforms ReLU or that vanishing gradients occurred.
2. The original toy neural network implementation is available in the (https://github.com/agastya-arch/toy-neural-network). The primary difference in the current experiment is that the weights are predefined rather than randomly initialised, allowing the experiments to use specific initial weights.
3. AI assistance was used to generate the initial code for the loss curve visualisation. The resulting plots were used to examine and compare the training behaviour of the two experiments.
