# Wids-25

AI for Self-Driving Car: Traffic Sign Classifier
This repository contains the work I’ve completed so far, including Assignment 1 and Assignment 2.

Week-Wise Progress
Week 1
Understood the overall goal of using AI in autonomous systems
Got familiar with neural networks and their basic working
Explored datasets and visualized sample data
Learned about data preprocessing and normalization

Week 2
Built a baseline ANN
Worked with structured (tabular) data
Trained and evaluated models using appropriate metrics
Observed how model performance changes with training

Week 3
Learned how CNNs work and why they are better for image data
Worked with image datasets and reshaped data for CNN input
Compared ANN vs CNN performance
Analyzed accuracy and loss to understand model improvements


Assignments
Assignment 1: Predicting Vehicle Fuel Efficiency
Objective:
Predict a car’s fuel efficiency (MPG) using features like horsepower, weight, displacement, etc.
What I did:
Used the Auto MPG dataset
Cleaned and normalized the data
Split the dataset into training and testing sets
Built a deep neural network with multiple hidden layers
Trained the model for 100 epochs and evaluated performance
Results:
Initial R² score: 0.6843
After increasing neurons to 128: R² improved to 0.6863
Mean Absolute Error: ~2.8 MPG
Model predictions aligned well with actual MPG values
 Colab Notebook:
https://colab.research.google.com/drive/1ioPkTZSk6kaE3lYZTkK6BSfRBFgxy2Cw?usp=sharing

Assignment 2: Handwritten Digit Recognition (ANN vs CNN)
Objective:
Build an image-based digit classifier and compare a standard ANN with a CNN.
What I did:
Used the MNIST handwritten digits dataset
Normalized image pixel values
Built a baseline ANN using flattened images
Built a CNN to preserve spatial information
Trained both models for 5 epochs and compared results
Results:
ANN Test Accuracy: ~97.7%
CNN Test Accuracy: ~98.6%
CNN clearly outperformed ANN by capturing image features like edges and curves
 Colab Notebook:
https://colab.research.google.com/drive/17MpAljMKtaIgKJIuowauPRZsPcdkRfNZ?usp=sharing

