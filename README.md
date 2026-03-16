# DETECTION-OF-DISTRACTED-DRIVER-USING-CNN

Overview

Driver distraction is one of the major causes of road accidents. This project uses Convolutional Neural Networks (CNN) to automatically detect whether a driver is distracted based on image data. The system analyzes driver images and classifies them into different distraction categories such as texting, talking on the phone, drinking, or safe driving.

The goal of this project is to demonstrate how deep learning and computer vision can be used to build intelligent driver monitoring systems that improve road safety.

Problem Statement

Traditional driver monitoring relies on manual observation or rule-based systems, which are often inaccurate and inefficient. This project uses deep learning-based image classification to automatically identify distracted driving behaviors.

Dataset

The model is trained using a driver distraction dataset containing labeled images of drivers performing different activities such as:
Safe driving
Texting (right/left)
Talking on phone
Drinking
Adjusting radio
Reaching behind
Each image is labeled according to the driver's activity.

Model Architecture

This project uses a Convolutional Neural Network (CNN) for image classification.
Typical CNN layers used:
Convolution layers for feature extraction
ReLU activation functions
Max pooling layers for dimensionality reduction

Technologies Used

Python
TensorFlow / Keras
NumPy
OpenCV
Jupyter Notebook

Workflow

Data preprocessing and image normalization
Train-test data split
CNN model architecture design
Model training using labeled driver images
Model evaluation using validation dataset
Prediction and classification of driver behavior

Results

The trained CNN model can classify different driver behaviors from images and identify distracted driving patterns. Such systems can be integrated into driver monitoring systems in vehicles to improve safety.

Future Improvements
Use transfer learning (ResNet / EfficientNet) for higher accuracy
Deploy the model using a real-time video pipeline
Integrate with edge devices for in-car monitoring
Improve dataset size and diversity



Fully connected layers for classification

Softmax output layer for multi-class prediction
