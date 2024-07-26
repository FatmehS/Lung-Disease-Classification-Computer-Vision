Lung Disease Classification using Deep Learning

Welcome to the Lung Disease Classification project! This repository contains the implementation of a computer vision project that classifies lung diseases using four different deep learning models: EfficientNet_B0, MobileNet, ResNet50, and SqueezeNet.

Table of Contents

Introduction

Models

Installation

Usage

Results


Introduction

Lung disease classification is a crucial task in medical diagnosis. This project leverages state-of-the-art convolutional neural network (CNN) architectures to classify lung diseases from medical images. We have implemented and uploaded each model in separate files for better organization and ease of use.

Models

EfficientNet_B0: Known for its efficiency and accuracy, EfficientNet_B0 scales up neural networks effectively.

MobileNet: Designed for mobile and edge devices, MobileNet is lightweight and performs well with limited resources.

ResNet50: A deeper network with 50 layers, ResNet50 uses residual connections to overcome the vanishing gradient problem.

SqueezeNet: A smaller model with fewer parameters, SqueezeNet achieves AlexNet-level accuracy with 50x fewer parameters.

Installation

To get started with the models, make sure you have the following dependencies installed:

Python 3.x

TensorFlow

Keras

NumPy

OpenCV

Matplotlib

You can install the required packages using the following command:

pip install -r requirements.txt

Usage

Each model is contained in a separate file. To run a model, simply execute the corresponding Python script.

For example, to run the EfficientNet_B0 model:

python efficientnet_b0.py

Replace efficientnet_b0.py with the filename of the model you want to run.



Results

The performance of each model is evaluated based on metrics such as accuracy, precision, recall, and F1-score. Detailed results for each model are documented in their respective files.


