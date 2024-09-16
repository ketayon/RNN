# Quantum RNN Model for Spam Detection

## Overview

This project implements a Quantum Recurrent Neural Network (RNN) model for spam detection in text messages. The model leverages quantum computing techniques to enhance traditional RNNs, offering an innovative approach to text classification tasks.

## Data

The model is trained on the SMS Spam Collection Dataset, which contains text messages labeled as "spam" or "ham". The dataset can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). Save the dataset as `spam.csv` or another preferred filename.

## Model Architecture

The model architecture includes:
- **Embedding Layer**: Converts text sequences into dense vectors.
- **LSTM Layer**: Captures sequential dependencies in the text.
- **Dropout Layer**: Prevents overfitting by randomly setting a fraction of input units to 0 at each update during training.
- **Dense Layers**: Performs classification with a final output layer using a sigmoid activation function.
- **Quantum Layer**: A custom quantum-inspired layer for additional feature extraction.

## Jupyter Notebooks

This repository contains two Jupyter notebooks:
- **`RNNs.ipynb`**: Demonstrates how to work with classical RNN models for text classification tasks.
- **`QRNNS.ipynb`**: Contains the implementation of the Quantum RNN model for spam detection, as described in this repository.

## License

This project does not have a formal license. Feel free to use the code for personal or educational purposes. If you plan to use it for commercial purposes, please contact the author.
