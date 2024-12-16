This project implements a machine learning model to classify news articles as real or fake. 
The model is built using TensorFlow and Keras, employing a Recurrent Neural Network (RNN) architecture 
with Long Short-Term Memory (LSTM) layers for text classification.

Model Overview

Data: The model uses a dataset of news articles where each article is labeled as either fake or real.

Preprocessing: The text data (news article titles) is preprocessed by removing special characters, converting text to lowercase, stemming words, and removing stopwords.

Model Architecture:

  Embedding Layer: Converts the text data into dense vectors, capturing semantic meaning.
  LSTM Layer: A type of RNN designed to capture long-range dependencies and patterns in sequences, making it ideal for text data.
  Dense Layer: A fully connected layer with a sigmoid activation function that outputs a binary classification (real or fake).
