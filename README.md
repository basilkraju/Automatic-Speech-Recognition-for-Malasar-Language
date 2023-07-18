# Automatic Speech Recognition for Malasar Language

This repository contains code for training and evaluating an automatic speech recognition (ASR) system for the Malasar language. The code is written in Python and uses the Whisper Pretrained Model.

The ASR system is trained on a dataset of audio recordings of Malasar speech. The dataset is split into a training set and a test set. The training set is used to train the ASR system, and the test set is used to evaluate the performance of the system.

The ASR system is evaluated using the WER: https://en.wikipedia.org/wiki/Word_error_rate metric. The WER is the percentage of words in the test set that are incorrectly recognized by the ASR system.

To train the ASR system, run the following command:

python ASR_For_Malasar.ipynb
This will train the ASR system on the training dataset and save the trained model to the models/ directory.
