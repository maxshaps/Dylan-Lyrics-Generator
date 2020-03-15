# Dylan-Lyrics-Generator
PyTorch implementation of a Long Short-Term Memory (LSTM) recurrent neural network for learning Bob Dylan's lyrical style and generating lyrical output. Incorporating a Word2vec-like embedding scheme for vectorizing text input, the LSTM model uses two LSTM layers with 256 hidden layer neurons and p=0.2 dropout. For training, the model uses cross entropy loss, Adam optimization, L2 regularization, and gradient clipping.


## Background
Project idea and execution adapted from https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/ and https://machinetalk.org/2019/02/08/text-generation-with-pytorch/.


## Data Source
Data was taken from here: https://github.com/alexing/lyrics_prediciton. The data was acquired using the Spotify API to identify all of the songs in Dylan's catalog and then the Genius API to scrape each song's lyrics.  The entire lyrical corpus is aggregated into a single text file.
