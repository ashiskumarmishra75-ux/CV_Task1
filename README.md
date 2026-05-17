# CV_Task1
# CIFAR-10 Image Classification using Custom ResNet

## Project Overview:

In this project we implement a custom ResNet architecture from scratch for image classification on the CIFAR-10 dataset using TensorFlow and Keras.
This implementation has been inspired from the paper: Deep Residual Learning for Image Recognition - He et al., 2015
The model applies residual blocks and skips connections to improve deep network training and solve the vanishing gradient problem.
A residual block learns: y = F(x) + x
where x is the original input, F(x) is the transformed input after convolution, and y is the final output.
In the code x is the shortcut or identity path, and F(x) is the residual.

## Benefits of using ResNet
  1. Solves the vanishing gradient problem.
  2. Efficient in Training deeper networks faster with more accuracy
  3. It converges faster.
  4. Prevents the degradation problem.

## Dataset
CIFAR-10 dataset
- 60,000 RGB images
- 10 classes
- 32 × 32 image size

## Custom ResNet Model:
  In the model we have used:
  1.convolutional layers
  2.Batch Normalization
  3.Residual Blocks
  4.Skip connections
  5.Global average pooling
  6.Dense output layer

## Hyperparameters
  Optimizer: Adam
  Learning Rate: 0.001
  Batch Size: 128
  Epochs: 10;
  Loss Function: Sparse Categorical CrossEntropy

## Training

The model was trained using Google Colab with TensorFlow/Keras.
Training metrics tracked:
- Training loss
- Validation loss
- Training accuracy
- Validation accuracy

##Final Results:
  - Accuracy: 
