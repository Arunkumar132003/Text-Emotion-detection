
# Emotion Detection using Random Forest Classifier

This project aims to classify emotions in text data using a Random Forest Classifier. The dataset used for training and testing consists of textual data labeled with emotions.

## Installation
To run this project, ensure you have the following dependencies installed:

- pandas
- scikit-learn
- matplotlib
- neattext

## Dataset
The dataset used in this project contains textual data labeled with emotions such as joy, sadness, anger, etc. The dataset is loaded using pandas and preprocessed using the neattext library to remove user handles and stopwords.

## Model

The emotion classification model is implemented using a Random Forest Classifier from scikit-learn. The textual features are vectorized using the CountVectorizer from scikit-learn.