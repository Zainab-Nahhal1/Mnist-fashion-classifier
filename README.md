# Mnist-fashion-classifier

A neural network built with TensorFlow/Keras to classify images of clothing from the Fashion MNIST dataset.  
This project demonstrates end-to-end image classification: data preprocessing, model building, training, evaluation, and prediction visualization.

## Features

- Loads and preprocesses the Fashion MNIST dataset  
- Builds a *fully connected neural network* (Dense layers)  
- Trains the model to classify 10 types of clothing items:  
  T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot  
- Evaluates accuracy on unseen test data (~90% accuracy)  
- Visualizes predictions with color-coded correctness (blue = correct, red = incorrect)  
- Predicts single images and outputs probability scores  


Note: Since this model uses only fully connected layers (no CNN), some visually similar items may be misclassified.