Cat and Dog Image Classifier using Data Science

This project is an image classifier built using convolutional neural networks (CNNs) to classify images as either cats or dogs.
Table of Contents

    Introduction
    Requirements
    Installation
    Dataset
    Model Training
    Evaluation
    Contributing

Introduction

This project aims to classify images as either cats or dogs using deep learning techniques. We trained a convolutional neural network (CNN) on a dataset consisting of thousands of cat and dog images. The model achieves high accuracy in distinguishing between the two classes.
Requirements

    Python 3.7 or higher
    TensorFlow 2.5.0
    Keras 2.4.3
    NumPy 1.19.5
    Matplotlib 3.4.3

Installation

Install the required dependencies

Dataset

We used the Kaggle Cats and Dogs dataset, which contains labeled images of cats and dogs. We split the dataset into training and testing sets, with 80% of the images used for training and 20% for testing. 

Model Training

The model architecture consists of multiple convolutional and pooling layers followed by fully connected layers. We trained the model using the Adam optimizer with a learning rate of 0.001 and categorical cross-entropy loss. The training process took approximately 4 hours on a GPU-enabled machine.

Evaluation

We evaluated the model on the test set and achieved an accuracy of 97%. Additionally, the model achieves high precision and recall for both cat and dog classes

Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
