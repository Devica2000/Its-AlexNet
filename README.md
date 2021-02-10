# Its-AlexNet
In class, we were taught different neural networks. I coded the architecture of AlexNet so that it could be understood well. 
AlexNet is the name of a convolutional neural network (CNN) that was designed by Alex Krizhevsky in collaboration with Ilya Sutskever and Geoffrey Hinton. AlexNet competed in the ImageNet Large Scale Visual Recognition Challenge on September 30, 2012.
The input to AlexNet has a dimension of 227x227x3. It has 8 layers in total. 5 convolutional layers and 3 fully connected layers. The last 3 layers are fully connected.

The order of layers is as follows:
1. Convolution Layer 1
2. Max pooling layer
3. Convolution Layer 2
4. Max pooling layer
5. Convolution Layer 3
6. Convolution Layer 4
7. Convolution Layer 5
8. Max pooling layer
9. Fully connected layer 1
10. Fully connected layer 2
11. Fully connected layer 3

Note that the max pooling layers are not counted as a layer. Only the convolutional layers and fully connected layers are counted.  
In AlexNet, there are 660k neurons, 61M prameters and 600M connections! 
AlexNet had some novel features:
1. Image Augmentation
2. Dropout in the fully connected layers
3. It showed that training ReLU non-linearity, deep CNN could be trained much faster than using the saturating activation function like sigmoid, tanh etc.
4. Use of convolutional layers for feature extraction
5. Fully connected layers for classification/regression
