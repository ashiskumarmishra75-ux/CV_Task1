# CV_Task1
# CIFAR-10 Image Classification using Custom ResNet

# Project Overview:

In this project we implement a custom ResNet architecture from scratch for image classification on the CIFAR-10 dataset using TensorFlow and Keras.
This implementation has been inspired from the paper: Deep Residual Learning for Image Recognition - He et al., 2015
The model applies residual blocks and skips connections to improve deep network training and solve the vanishing gradient problem.
A residual block learns: y = F(x) + x
where x is the original input, F(x) is the transformed input after convolution, and y is the final output.
In the code x is the shortcut or identity path, and F(x) is the residual.
