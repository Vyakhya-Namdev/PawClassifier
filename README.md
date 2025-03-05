## Overview
This project is a deep learning-based image classification model that distinguishes between cats and dogs. Built using TensorFlow & Keras, the model utilizes Convolutional Neural Networks (CNNs) to achieve high accuracy. BatchNormalization and Dropout were implemented to improve real-time training performance.

## Features
✔ Image classification using CNN
✔ Implemented BatchNormalization for stable training
✔ Dropout added to prevent overfitting
✔ Real-time prediction capability
✔ Trained with data augmentation for better generalization

## Dataset
The dataset consists of labeled images of cats and dogs.
Labeling:
0 → Cat
1 → Dog
Download the dataset from Kaggle - Dogs vs. Cats

 ## Tech Stack Used
Programming Language: Python
Deep Learning Framework: TensorFlow, Keras
Libraries Used: OpenCV, NumPy, Matplotlib

## Model Architecture
Conv2D layers for feature extraction
MaxPooling2D for reducing spatial dimensions
BatchNormalization for faster convergence
Dropout to prevent overfitting
