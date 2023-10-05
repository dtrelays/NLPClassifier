# NLP Question Pair Classifier

This project is a natural language processing (NLP) classifier designed to determine if two input questions are duplicates or not. It utilizes a dataset from Kaggle, preprocesses the data, tokenizes the text, and employs a Long Short-Term Memory (LSTM) model for training and classification.

## Data Source

The data used for this project is sourced from Kaggle. You can find the dataset here: https://www.kaggle.com/competitions/quora-question-pairs/data

## Data Preprocessing

Before training the model, the data undergoes preprocessing, including text cleaning, tokenization, and sequence padding. You can find the data preprocessing code in the project repository.

## Model Architecture

The classifier employs a Long Short-Term Memory (LSTM) neural network. The LSTM model is designed to capture sequential patterns in the text, making it suitable for NLP tasks. The architecture is detailed in the code within the repository.

## Training

The model is trained on the preprocessed data using the training code provided. The training process involves configuring hyperparameters, such as the LSTM units, embedding dimension, and dropout rates. The trained model's performance is evaluated on the testing data.

## Results

The project's results include the model's accuracy of 0.82 on validation data set.

