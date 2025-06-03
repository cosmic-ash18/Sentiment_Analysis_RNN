# SMS Spam Classification using RNN

This project performs SMS spam classification using a Recurrent Neural Network (RNN). It uses pre-trained GloVe word embeddings from the Stanford NLP website to represent words.

## Description

- The model takes SMS messages as input and classifies them as either "spam" or "ham" (not spam).
- Pre-trained GloVe embeddings are used to initialize the embedding layer for better word representation.
- The dataset is tokenized and fed into an RNN-based model using PyTorch for binary classification.
