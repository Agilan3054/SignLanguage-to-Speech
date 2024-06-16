# Sign Language to Speech

This project aims to build a Convolutional Neural Network (CNN) to recognize sign language gestures from images using TensorFlow and Keras. The CNN model is trained on the Sign Language MNIST dataset, which consists of grayscale images of hand gestures representing letters A-Z (excluding J and Z) in American Sign Language (ASL).

## Project Overview

Sign language recognition through computer vision and machine learning plays a crucial role in bridging communication gaps for individuals with hearing impairments. By developing an automated system capable of recognizing sign language gestures, we aim to facilitate better interaction and accessibility.

## Project Structure

The project includes the following main components:

### Data Loading and Preprocessing:

- Loading the Sign Language MNIST dataset using Pandas.
- Preprocessing the data to prepare it for training the CNN model.
- Reshaping and normalizing images for input to the CNN.

### Model Building:

- Constructing a CNN using TensorFlow and Keras.
- Defining layers including Conv2D, MaxPooling2D, Flatten, and Dense.
- Compiling the model with Adam optimizer and categorical cross-entropy loss function.

### Training and Evaluation:

- Training the CNN model on the training data.
- Evaluating the model performance using the test data.
- Plotting training history (loss and accuracy over epochs).

### Prediction and Visualization:

- Implementing functions to predict labels from new images.
- Visualizing predictions alongside the corresponding test images.
- Converting predicted labels to alphabetic characters (e.g., 'W', 'E', 'L', etc.).

### Text-to-Speech Integration:

- Using gTTS library to convert predicted words into speech.
- Generating audio files for predicted words to facilitate accessibility.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- OpenCV (cv2)
- gTTS
