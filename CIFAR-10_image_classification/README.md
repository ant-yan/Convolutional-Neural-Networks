
# CIFAR-10 Image Recognition Project

This repository is dedicated to the classification of images in the CIFAR-10 dataset. The project explores multiple convolutional neural network (CNN) architectures to determine the most effective model for this task. After comparative testing, the ResNet-50 model yielded the highest accuracy.

## Architectures Evaluated

The following deep learning models were utilized and benchmarked:

- ResNet-18
- VGG-16
- ResNet-50 *(Top performer)*

## Optimal Training Configuration

- **Batch Size:** 128  
- **Epochs:** 20  
- **Learning Rate:** 0.001  

## Summary

Out of all the architectures explored, ResNet-50 demonstrated superior performance, attaining a test accuracy of **91.17%** on the CIFAR-10 dataset. This makes it a strong candidate for further image classification tasks in similar domains.
