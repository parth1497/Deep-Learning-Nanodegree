# Sentiment Analysis

Implemented a recurrent neural network that performs sentiment analysis on movie reviews. 

## Network Architecture
- Pass words to an embedding layer. In this case the word embedding is trained during the time of training. 
- Word encoded vectors are fed to a layers of LSTM cells.
- Output from the LSTM cells are fed to a sigmoid output layer.