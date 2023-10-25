# IMDB-Sentiment-Analysis

## Introduction

In this project, IMDB sentiment analysis was made using Recurrent Neural Network (RNN) algorithm.

## Exploring Dataset

The dataset used in this study: (http://ai.stanford.edu/~amaas/data/sentiment/). This dataset contains 25,000 highly polar movie reviews for training, and 25,000 for testing. In this dataset, words are sorted as integers according to their frequent use. In this project, we got the comments again by reversing this process with the help of a function (decoder function) to examine the comments.

## Data Preprocess

In the data preprocessing part, first all the data is synchronized to a certain word length (150), and the data with less than 150 words is filled in up to 150 words with "!".

## Model

The RNN model has 4 layers. The first layer is the embedding layer, the second layer is the SimpleRNN layer, the third layer is the dense layer and the last layer is the activation layer with sigmoid function.

## Result

 The accuracy rate of the model was determined as 85.12% at 5 epochs. 
