# Emotion Classification from EEG Signals

## Overview
This project focuses on classifying emotions using Electroencephalography (EEG) signals. By leveraging deep learning techniques, we aim to improve the accuracy of emotion recognition, which has applications in mental health monitoring, brain-computer interfaces, and affective computing.

## Dataset
The EEG signal data was preprocessed to ensure consistency and reliability before training the models. The key preprocessing steps included:
- **Standardization**: Normalizing the data for better model performance.
- **Visualization**: Exploring signal patterns and distributions.
- **Data Splitting**: Dividing the dataset into training and testing subsets.

## Methodology
### Models Used
Two deep learning models were implemented and compared:
- **Artificial Neural Network (ANN)**: Used as a baseline model.
- **Long Short-Term Memory (LSTM)**: Utilized for its capability to capture temporal dependencies in sequential EEG data.

### Model Training and Evaluation
- The models were trained using the preprocessed EEG dataset.
- Performance evaluation was conducted using a **confusion matrix** and prediction analysis.

## Results
The deep learning models demonstrated the effectiveness of ANN and LSTM in emotion classification from EEG signals. The LSTM model, in particular, showed improved performance due to its ability to recognize patterns over time.

## Installation
To run this project, follow these steps:

### Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

