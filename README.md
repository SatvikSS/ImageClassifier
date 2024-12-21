# Cat vs Dog Image Classification
Welcome to the Cat vs Dog Image Classification repository! This project uses Convolutional Neural Networks (CNNs) to classify images of cats and dogs. The model is trained on a dataset sourced from Kaggle, and the goal is to predict whether an image contains a cat or a dog.

## Overview
This project uses a CNN model to classify images into two categories: cats and dogs. The model is built using TensorFlow and Keras. The dataset is a large collection of images from Kaggle's Dogs vs Cats dataset. Due to the size of the dataset, it cannot be uploaded to GitHub, but you can download it from Kaggle.

The project includes a simple script that trains the model on the dataset, visualizes the training history, and evaluates the model’s performance.

## Features
Deep Learning Model: A CNN model to classify images of cats and dogs.

Dataset: Large Kaggle dataset for training and testing the model.

Training and Evaluation: Model training with real-time evaluation and accuracy plots.

Model Performance: Achieved a validation accuracy of around 85% after training.

## Technologies Used

Backend: Python, TensorFlow, Keras

Modeling: Convolutional Neural Networks (CNN)

Image Processing: OpenCV

Visualization: Matplotlib

## Dataset
The data was downloaded from kaggle. Link for data: https://www.kaggle.com/datasets/salader/dogs-vs-cats. It consisting of 25,000 images of cats and dogs, split into a training set and a test set. The data is preprocessed by resizing images to 256x256 pixels, normalizing the pixel values to a range of 0 to 1, and splitting the dataset into training and validation sets.

## Model Architecture
The CNN model consists of:

Convolutional Layers: Three convolutional layers with ReLU activation and batch normalization.

MaxPooling Layers: Used to reduce the spatial dimensions.

Fully Connected Layers: To make the final predictions.

Output Layer: A sigmoid activation function to classify images as either cats or dogs.


## Results
The CNN model achieved the following results after training for 10 epochs:

Validation Accuracy: ~85%
