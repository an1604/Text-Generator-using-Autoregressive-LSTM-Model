﻿# Text-Generator-using-Autoregressive-LSTM-Model
This project implements a text generator using an autoregressive LSTM (Long Short-Term Memory) model. The model is trained on a dataset of recipes, and it can generate new text based on a given starting prompt.
# Introduction
This project focuses on creating a text generation model using an LSTM neural network. The model is trained on a dataset of recipes and can generate coherent and contextually relevant text based on user prompts.

# Features
Autoregressive LSTM Model: Utilizes an LSTM architecture to capture sequential dependencies in the text.
Text Preprocessing: Implements text preprocessing techniques, including tokenization and vectorization.
Custom Callbacks: Utilizes custom callbacks for model checkpointing and generating text during training.
TensorBoard Integration: Monitors and visualizes training progress using TensorBoard.

# Model Architecture
The model consists of an embedding layer, an LSTM layer, and a dense layer with softmax activation. The architecture is designed to capture and generate sequential patterns in the input text.
# Training
The model is trained on the specified dataset for a predefined number of epochs. The training progress can be monitored using TensorBoard, and model checkpoints are saved for future use.
# Text Generation
After training, users can interact with the model by providing a starting prompt. The model generates text based on the given prompt, and the probabilities of the next words are displayed.
