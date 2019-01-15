
# OWM
Code for **CelebA** in paper *[Continual Learning of Context-dependent Processing in Neural Networks](https://arxiv.org/abs/1810.01256)*

CelebFaces Attributes Dataset [(CelebA)]( http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations.

## OS Requirements:

Linux: Ubuntu 16.04

Cuda compilation tools, release 9.0, V9.0.176

## Package  Requirements:

Python 3.5.4

torch 0.3.0 (pytorch)

torchvision 0.2.0

numpy 1.15.1

scipy 1.0.0

## Instructions
1. Deal with the data in http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
2. Training the [ResNet50](https://github.com/beijixiong3510/OWM/tree/master/celebA/celebA_pytorch_50) to extract features of all data
3. Use the [CDP Code (PFC-like Module)](https://github.com/beijixiong3510/OWM/tree/master/celebA/celebA_PFC) to reproduce the result