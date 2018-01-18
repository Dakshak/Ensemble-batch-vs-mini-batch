# Ensemble-batch-vs-mini-batch
In here I will use ensemble approach with batch and mini-batch methods to improve the accuracy of the 2-layered neural network for MNIST data.  -> This is to show the difference between 2 methods and how mini batch is better if you are deling with a large dataset like most of us usually are.  -> Ensemble is the method of training different algorithms with different initial condition on same training data and averaging the predictions to get the best of all models.   -> Batch update is the process of training the neural network model with entire dataset and mini-batch update is the process of training the neural network model with a sample of training data (So far, in your homeworks, you have used mini-batch training). Training with batch/complete training data is call gradient descent while mini-batch training is called stochastic-gradient descent.  1. I use batch update for training the data 2. I train 5 different models (two layered NN) with different parameter settings. Use the average of the predicted value to calculate the accuracy. (Models should vary regularization, activation functions,learning rate, hidden size)   Compare the time and accuracy between the six models that you trained.
