Project README: Spotify Hit Predictor
For access to the colab, DM me.

Dataset Overview:

The dataset to be analyzed is "Spotify_dataset.csv," containing information regarding music tracks. This dataset is sourced from Kaggle and is primarily derived from the Hit Predictor dataset. It comprises over 40,000 tracks labeled as hits or flops, along with their features. The dataset aims to support machine learning tasks related to predicting track success and characterizing music tracks.
In this notebook, I will aim to undertake the following tasks:

    Task 1: Supervised Learning
        Objective: Predicting whether a track is a hit or a flop.
        Secondary Objective: Predicting discrete valence.
    Task 2: Unsupervised Learning
        Objective: Characterizing music tracks.

Dataset Information:

    Name: Spotify Hit Predictor Dataset (1960-2019)
    Content:
        Features for tracks fetched using Spotify's Web API.
        Tracks labeled '1' or '0' (Hit or Flop) based on certain criteria.
    Purpose: This dataset enables the creation of classification models predicting a track's success.

Project Resources:

    Dataset: "Spotify_dataset.csv" provided alongside this project description.
    Additional Information:
        The dataset from which this one was created: https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset

Models Applied:

Several models were applied, including:

    Multinomial logistic regression
    Tree Model
    Multi-Layer Perceptron
    Bernoulli Bayes
    K-nearest neighbor classifier distance model

These models were selected based on comparisons with other models of each type, such comparisons are found in the code, (E.G.: Comparing Gaussian and Bernoulli Naive Bayes)
