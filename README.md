# News Classification Using NLP & LSTM

A deep learning project for classifying news articles into five categories using Natural Language Processing (NLP) and an LSTM neural network.

## Project Overview

This project focuses on building a news classification system using text preprocessing and deep learning techniques.

The dataset contains 50,000 news articles categorized into five classes:

- Business
- Entertainment
- Lifestyle
- Politics
- Sports

## Technologies

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- LSTM
- Natural Language Processing (NLP)

## Data Preprocessing

The project includes several preprocessing steps:

- Text cleaning
- Tokenization
- Stop-word removal
- Label encoding
- Sequence padding
- Preparing text data for deep learning

## Model

An LSTM-based neural network was developed using:

- Embedding Layer
- LSTM Layers
- Dropout
- Softmax Output Layer

The model is trained to classify news articles into the five predefined categories.

## Project Structure

```text
news-classification-lstm/
│
├── data/
│   ├── NewsCategorizer.csv
│   └── NewsCategorizer_modified.csv
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   └── news_classifier_lstm.ipynb
│
├── README.md
└── requirements.txt
