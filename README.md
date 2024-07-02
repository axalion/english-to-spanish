# English to Spanish Sequence-to-Sequence Translation with Bi-LSTM

This repository contains a Jupyter Notebook implementing a sequence-to-sequence model for English to Spanish translation using Bi-LSTM (Bidirectional Long Short-Term Memory) for the encoder and LSTM for the decoder.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Data Preparation](#data-preparation)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [References](#references)

### Introduction

This project demonstrates how to build a sequence-to-sequence model for translating English sentences into Spanish. The encoder utilizes Bi-LSTM, while the decoder employs a standard LSTM.

### Setup

To run this notebook, you will need to have the following dependencies installed:

- Python 3.x
- TensorFlow
- NumPy
- Pandas

You can install the required packages using:

```bash
pip install tensorflow numpy pandas
```

### Data Preparation
- Download Spanish-English data from ManyThings.org.
- You can also try other language pairs if desired.
- Unzip the downloaded .zip file.
- Place the .txt file (e.g., spa.txt) in the directory ./Data/.
- Update the data directory path in section 1.1 of the notebook.


### Model Architecture
The model architecture consists of the following components:

- Encoder: A Bi-LSTM layer that processes the input sequence and returns the states.
- Decoder: An LSTM layer that uses the encoder states to generate the translated output sequence.

### Training
The notebook includes code for training the model. You can adjust the training parameters such as the number of epochs, batch size, and learning rate as needed.

### Evaluation
The model's performance is evaluated using metrics such as BLEU score to measure the quality of the translations.

### Results
Results and model performance will be displayed in the notebook after training and evaluation.
