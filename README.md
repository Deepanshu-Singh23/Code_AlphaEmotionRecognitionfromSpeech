# Emotion Recognition from Speech

A Deep Learning based Speech Emotion Recognition system that classifies human speech into different emotions using MFCC audio features and a Neural Network.

## Project Overview

This project uses the RAVDESS dataset to recognize emotions from speech recordings.

The audio signals are converted into MFCC (Mel-Frequency Cepstral Coefficients) features, which are then provided to a Neural Network for emotion classification.

## Emotions Recognized

- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgust
- Surprised

## Technologies Used

- Python
- NumPy
- Pandas
- Librosa
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Machine Learning Approach

1. Load the RAVDESS speech dataset
2. Extract MFCC features from audio files
3. Encode emotion labels
4. Split data into training and testing sets
5. Train a Neural Network
6. Evaluate the model
7. Generate classification report and confusion matrix
8. Predict emotion from a WAV audio file

## Dataset

RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

## Model

A Feed-Forward Neural Network is used for emotion classification.

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
