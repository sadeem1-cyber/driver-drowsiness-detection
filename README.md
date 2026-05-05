# Driver Drowsiness Detection System

AI-based driver drowsiness detection system using deep learning and computer vision.

## Overview
This project uses a ResNet50-based deep learning model to classify the driver's state as **Drowsy** or **Non-Drowsy** using camera image capture in Google Colab.

## Features
- Camera image capture in Google Colab
- Drowsiness classification: Drowsy / Non-Drowsy
- Transfer learning using ResNet50
- Image preprocessing and data augmentation
- Model evaluation using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve

## Technologies
- Python
- TensorFlow / Keras
- OpenCV
- ResNet50
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Results
- Final validation accuracy: 97.62%
- Evaluation accuracy: 99.77%
- Precision: 99.63%
- Recall: 99.92%
- F1-score: 99.77%
- AUC: 99.98%

## Dataset
The model was trained on the Driver Drowsiness Dataset (DDD), with two classes:
- Drowsy
- Non-Drowsy
