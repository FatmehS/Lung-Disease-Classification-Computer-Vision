Lung Disease Classification using Deep Learning
This repository contains the implementation of a computer vision project for classifying lung diseases using four different deep learning models: EfficientNet_B0, MobileNet, ResNet50, and SqueezeNet.

Table of Contents
Introduction
Models
Dataset
Installation
Usage
Results
Contributing
License
Introduction
Lung disease classification is a critical task in medical diagnosis. This project utilizes state-of-the-art convolutional neural network (CNN) architectures to classify lung diseases from medical images. The models implemented are EfficientNet_B0, MobileNet, ResNet50, and SqueezeNet, each uploaded in separate files for better organization.

Models
EfficientNet_B0: Known for its efficiency and accuracy, EfficientNet_B0 scales up neural networks effectively.
MobileNet: Designed for mobile and edge devices, MobileNet is lightweight and performs well with limited resources.
ResNet50: A deeper network with 50 layers, ResNet50 uses residual connections to overcome the vanishing gradient problem.
SqueezeNet: A smaller model with fewer parameters, SqueezeNet achieves AlexNet-level accuracy with 50x fewer parameters.
Dataset
The dataset used for training and evaluating the models consists of medical images labeled with different lung diseases. (Provide more details about the dataset if applicable, including source, preprocessing steps, and any augmentation applied.)

Installation
To run the models, ensure you have the following dependencies installed:

Python 3.x
TensorFlow
Keras
NumPy
OpenCV
Matplotlib
You can install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Each model is contained in a separate file. You can run the models by executing the respective Python scripts.

For example, to run the EfficientNet_B0 model:

bash
Copy code
python efficientnet_b0.py
Replace efficientnet_b0.py with the filename of the model you want to run.

Results
Each model's performance is evaluated based on accuracy, precision, recall, and F1-score. The results for each model are documented in their respective files.

Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.
