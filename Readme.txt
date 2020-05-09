Building complex model on Pytorch that is able to classify MNIST dataset. 

What is MNIST dataset?

The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset. It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

In this project I have created 2 different models to classify MINST images:-

The first model is a Normal Deep neural network with 1 input layer, 2 hidden layers and 1 output layer. The maximum accuracy after hypertuning was around 95%

The second model I created was a Convolution Neural N/w LeNet model with 2 convolutional layers, one dropout layer and 2 fully connected layers. The accuracy this model yield was 99% which is amazing.



requirements:-

pip install torch===1.5.0 torchvision===0.6.0 -f https://download.pytorch.org/whl/torch_stable.html