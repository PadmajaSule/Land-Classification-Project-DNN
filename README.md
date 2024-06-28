# Land-Classification-Project-DNN

Problem Statement:
In the realm of remote sensing and environmental monitoring, accurate classification of satellite imagery plays a pivotal role in various applications such as land cover mapping, urban planning, and ecological assessment. The task at hand involves the classification of satellite images into distinct land cover classes using the provided dataset, RSI-CB256.

Dataset-RSI-CB256: 
* The dataset has 4 different classes mixed from Sensors and google map snapshot
* classes: cloudy, desert, green_area, water
* Dataset link: https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification

Brief about the models used:

* VGGNet (Visual Geometry Group Network): <br>
VGGNet is a deep convolutional neural network architecture proposed by the Visual Geometry Group at the University of Oxford.
It is characterized by its simplicity and uniform architecture, consisting primarily of repeated blocks of convolutional layers followed by max-pooling layers.
VGGNet achieved excellent performance on image classification tasks but is computationally expensive due to its large number of parameters.

* ResNet (Residual Network): <br>
ResNet is a deep convolutional neural network architecture proposed by Microsoft Research.
It introduced the concept of residual learning, where shortcut connections (skip connections) are added to the network to bypass one or more layers. This helps address the vanishing gradient problem and enables training of much deeper networks.
ResNet architectures typically come in variants like ResNet-50, ResNet-101, etc., which denote the number of layers in the network.

* MobileNet: <br>
MobileNet is a family of lightweight convolutional neural network architectures designed for mobile and embedded devices.
It utilizes depthwise separable convolutions, which factorize standard convolutions into a depthwise convolution followed by a pointwise convolution. This reduces the computational cost significantly while maintaining performance.
MobileNet architectures are efficient in terms of both model size and inference speed, making them suitable for resource-constrained environments.

* EfficientNet: <br>
EfficientNet is a scalable convolutional neural network architecture proposed by Google Research.
It introduces a compound scaling method that uniformly scales the network's depth, width, and resolution in a principled way to achieve better performance.
EfficientNet achieves state-of-the-art performance on image classification tasks with significantly fewer parameters and FLOPs compared to other architectures.
