# Text Sentiment Analysis using LSTM

## Description
This project uses Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), to classify IMDB movie reviews into Positive and Negative sentiments.

## Features
- IMDB Movie Reviews Dataset
- Text Sequence Padding
- Word Embedding
- LSTM-based Deep Learning Model
- Binary Sentiment Classification
- Model Training and Evaluation
- Sentiment Prediction

## Model Architecture
Input Review → Embedding Layer → LSTM Layer → Dense Layer → Sigmoid Activation → Sentiment Prediction

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- LSTM
- Deep Learning

## Dataset
IMDB Movie Reviews Dataset (provided by TensorFlow Keras).

## How to Run

1. Install required libraries:
   `pip install -r requirements.txt`

2. Run the Python file:
   `python sentiment_analysis_lstm.py`

## Output
The model predicts whether a movie review expresses Positive or Negative sentiment.