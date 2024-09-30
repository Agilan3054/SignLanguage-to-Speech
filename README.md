# End-to-End AI-Powered Sign Language to Speech Conversion App

This project aims to build an end-to-end AI-powered sign language to speech conversion application, utilizing React for the frontend, TensorFlow for gesture recognition, OpenCV for image preprocessing, and gTTS for speech synthesis. The system recognizes sign language gestures and converts them into speech, enhancing accessibility for individuals with hearing impairments.

## Project Overview

Sign language recognition using computer vision techniques and machine learning bridges communication gaps for the hearing-impaired. This project leverages deep learning and speech synthesis to automatically detect sign language gestures from images and convert them into natural speech, providing a user-friendly and accessible solution.

## Project Structure

The project consists of the following components:

### Frontend (React):
- A React-based frontend interface allowing users to upload sign language gesture images.
- A responsive UI for real-time prediction feedback and speech conversion.

### Backend (Flask):
- A Flask-based backend that serves as the API for handling the image uploads and processing them through the trained model.
- Manages communication between the frontend and the machine learning model for prediction and speech synthesis.

### Data Loading and Preprocessing:
- Loading and preprocessing the Sign Language MNIST dataset for training the Convolutional Neural Network (CNN).
- Using OpenCV for real-time image preprocessing to handle different sign gestures.

### Model Building:
- Implementing a CNN using TensorFlow and Keras for sign language gesture recognition.
- The model architecture includes Conv2D, MaxPooling2D, Flatten, and Dense layers optimized through dropout regularization and early stopping.
- Achieved 92% accuracy after hyperparameter tuning (learning rate, batch size).

### Speech Synthesis:
- Converting the predicted gestures to speech using Google Text-to-Speech (gTTS) and Pyttsx3 for natural audio output.
- Speech synthesis occurs in real-time, making the interaction more intuitive and responsive.

### Deployment:
- The full-stack solution is deployed using Flask as the backend and React as the frontend.
- Ensures seamless interaction between the user interface and the trained model.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Flask
- OpenCV (cv2)
- gTTS
- Pyttsx3
- React
- Axios (for handling frontend-backend communication)
- NumPy
- Pandas

