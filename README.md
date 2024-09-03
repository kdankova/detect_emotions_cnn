# Emotion Detection Using CNN

## Overview

This project is an implementation of an emotion detection system using a Convolutional Neural Network (CNN). The system is trained to recognize various emotions from images, leveraging a deep learning model based on the EfficientNetB2 architecture. The dataset consists of labeled images of faces categorized by different emotions, which are used to train, validate, and test the model.

## Features

- **Data Preprocessing**: Loading and preprocessing images from the dataset for training, validation, and testing.
- **Model Training**: Training a CNN model (EfficientNetB2) to classify emotions.
- **Evaluation**: Evaluating the model's performance using confusion matrix, classification report, and plotting training history.
- **Prediction**: Predicting the emotion of a face in a given image using the trained model.

## Installation

To run this project, you'll need to have Python installed on your machine along with several dependencies. You can install the necessary packages using pip:

```bash
pip install numpy pandas seaborn matplotlib tensorflow keras pillow scikit-learn
