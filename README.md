# lstm-emotion-classification

# Emotion Classification using LSTM 

This project builds a deep learning model based on LSTM (Long Short-Term Memory) networks to classify **emotions in English tweets**. The model predicts one of six emotion categories: `joy`, `sadness`, `anger`, `fear`, `love`, and `surprise`.

## Project Overview

- **Task:** Multi-class text classification
- **Dataset:** [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion) (English tweets with emotion labels)
- **Model:** Bi-directional LSTM with GloVe word embeddings
- **Language:** Python
- **Frameworks:** PyTorch, Hugging Face Datasets, Scikit-learn

## Features

- Preprocessing with tokenization and padding
- GloVe word embeddings (100d)
- Bi-directional LSTM classifier
- Training, evaluation, and classification metrics (Accuracy, F1)
- Confusion matrix visualization
