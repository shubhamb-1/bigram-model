# Bigram Model for Character Prediction

## Introduction
This project implements a Bigram Model with and Without Neural Networks for predicting the next character in a sequence, based on the last character, using a list of names. It's designed to demonstrate the basics of probabilistic language models in natural language processing and Neural Networks.

## Features
- Implementation of a Bigram Model using a 27x27 tensor array to store character occurrences.
- Utilizes a `.txt` file containing a list of names as the training dataset.
- The model accounts for all character occurrences, appending '.' as a start and end character for each name.
- Character prediction based on calculated probabilities, selecting the next character using a probability-driven approach.

## Dataset
The model is trained on a `names.txt` file, which is a collection of names. This dataset is used to understand and learn the patterns in the sequence of characters in names.

## Neural Network Approach
- The neural network component is used to enhance the prediction accuracy of the Bigram Model.
- The tensor `W` represents the weights of the neural network, which are adjusted during the training process based on the bigram occurrences in the training data.
