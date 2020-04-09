# Using CNN(LeNet) with Pytorch to train Some famous Dataset
In this repo I have used 2 Famous Dataset i.e CIFAR10, MNIST

# CIFAR10
In this we have seen by using tanh Activation function with LeNet we overfit our model.So we try using ReLU Activation Function and improve our condition of overfit but Still Data overfit in our model, so we use L2 regularization using weight_decay in our optimization i.e Adam.
After that all model overall accuracy is low but we have removed overfitting of our data in model.For Higher accuracy we can Use VGG16,ResNet18,MobileNetV2 and much more.


# MNIST
In this we from start we used ReLU Activation Function with L2 regularization using weight_decay and can see overall accuracy of our model close to 99%.
