This file is for the sentiment analysis of tweets.

You can run this file in Collab or Jupiter Notebook.

Download the dataset from here : https://drive.google.com/file/d/1VKj-pKrJz69_tWb4-WdMvZcQfiS7CwEg/view?usp=drive_link
After the download add this to your drive, add the files location in the ipynb file and then run the file completely. (Here - dataset = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/training.1600000.processed.noemoticon.csv')
traing would take some time affter that u can add your examples to check the results.

This project demonstrates how to build a sentiment analysis model using various machine learning algorithms such as Logistic Regression, Bernoulli Naive Bayes, and Linear SVC. The model is trained on a dataset of tweets and classifies them as **Positive** or **Negative** based on their sentiment.

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Saving Models](#saving-models)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Project Overview

This sentiment analysis project uses Natural Language Processing (NLP) techniques for text preprocessing and machine learning models for sentiment classification. The models are trained on a large corpus of 1.6 million tweets and use **TF-IDF Vectorization** for text representation. The code evaluates three different models:
- Logistic Regression
- Bernoulli Naive Bayes (BNB)
- Linear Support Vector Classifier (SVC)

## Dependencies

Make sure you have the following Python packages installed:

```bash
numpy
pandas
seaborn
matplotlib
nltk
scikit-learn
wordcloud
