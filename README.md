# English to French Translation Using Deep Learning

This project involves building a sequence-to-sequence learning model for translating English sentences into French using TensorFlow and Keras.

## Project Overview

The project uses a recurrent neural network (RNN) with Long Short-Term Memory (LSTM) units to build an encoder-decoder model. This model learns to translate from English to French from a given dataset of English-French sentence pairs.

## Prerequisites

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib (for plotting training results)

## Dataset

The dataset used in this project is `fra.txt`, a file containing English-French sentence pairs. 

## Model Architecture

The model consists of:
- An encoder LSTM that processes the input English sentences.
- A decoder LSTM that generates the corresponding French translations.

## How to Run

1. Clone the repository
2. Install the required packages
3. Run the script

## Training the Model

To train the model, run the script `translation_model.py`. This script will:
- Load and preprocess the data.
- Build and compile the LSTM-based sequence-to-sequence model.
- Train the model on the English-French sentence pairs.
- Save the trained model.

## Using the Model for Translation

Once the model is trained, you can use it to translate English sentences into French. A function `decode_sequence` is provided for this purpose in the script.

## Results

The training process outputs the loss and accuracy metrics, which are plotted using Matplotlib. Sample translations by the model are also provided.

## Authors

- Ameya Deshmukh

## License

This project is licensed under the MIT License
