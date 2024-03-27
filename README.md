In Question 3, we first load the data using Pytorch Dataloader and then we load the pretrained weights for all the models from pytorch.
We preprocess the images, by converting them into tensors and normalizing the images. We will use Cuda to run the codes on GPU.
We also modify the output layer according to the model we use.
We then train all the models and print it's accuracy results.
We get the best results with LeNet while ResNET gives the worst results.

In Question 4, we implement a Fully Connected NN with input size as (32, 32, 3) on CIFAR 100 Dataset.
We use 2 hidden-layers and 64 neurosn per layer with RELU activation.
We use cross entropy loss with Adam Optimizer, we consider accuracy as the perfomance metric
