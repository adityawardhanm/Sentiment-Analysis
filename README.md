# Sentiment Analysis

## Objective

Sentiment Analysis or Opinion Mining is a sub stream of Natural Language Processing that aims to identify the emotional tone behind the body of text. It is considered a very important field in Business as it helps them automate the process of determining and categorising the opinion on a product. 
The main objective of this project is to use Transfer Learning to create program for Sentiment Analysis.  

## About Project

To perform the objective, A dataset named “SMILE Twitter Emotion Dataset” has been used which has 3085 twitter tweets of various emotions categories. Also Google Cloud Platform was used to perform the computation. Tools used in GCP were Cloud Storage Buckets and Dataproc Clusters on which Jupyter Lab was run.

The First Iteration of this project was made using Pytorch and Transformers library to import the BERT Tokenizer and Classifier. Also sklearn were used to calculate the performance metrics like F1score, Validation loss and Training loss.

The original Dataset is available on Kaggle [here](https://www.kaggle.com/datasets/ashkhagan/smile-twitter-emotion-dataset). Still, I have uploaded the dataset in the repository.

## Future Scope

I am planning on developing this further in 

• Second iteration by switching Pytorch with Tensorflow.

• Third Iteration by trying to switch Transformers with KerasNLP's BERT (May take time).

by [adityawardhanm](https://github.com/adityawardhanm)
