# Credit Card Fraud Detection Model
 
## Overview
This project is a credit card fraud detection system that uses a Deep Autoencoder built with Keras. The system is designed to reconstruct what non-fraudulent transactions look like and discriminate between fraudulent and non-fraudulent transactions.

## Features
* Deep Autoencoder: The system uses a Deep Autoencoder implemented in Keras for feature extraction and reconstruction of non-fraudulent transactions.
* Simplification: The use of a Deep Autoencoder simplifies the feature extraction process and allows the system to learn the characteristics of non-fraudulent transactions.
* Magic Dataset: The dataset used in this project is described as "magical" because the original features are not known. The Deep Autoencoder learns the features from the data itself.
* Clean API: Keras provides a clean and easy-to-use API for building and training Deep Autoencoders. Compared to TensorFlow implementations, Keras requires less boilerplate code.

## Requirements
* Python 3.x
* Keras
* TensorFlow (Required for GPU acceleration)
