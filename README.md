# Disaster Tweets Detection

## Overview
This project focuses on detecting disaster-related tweets using Natural Language Processing (NLP). The goal is to classify tweets as either disaster-related or not, using deep learning techniques. The dataset used for this task comes from a Kaggle competition.


## Dataset
[Kaggle](https://www.kaggle.com/competitions/nlp-getting-started/data)

## Project Structure
The notebook follows a structured pipeline:
2. **Data Loading**: Using a `DisasterTweetAnalysis` class to load and preprocess the dataset.
3. **Data Cleaning**: Applying text preprocessing steps.
4. **Exploratory Data Analysis (EDA)**: Generating visualizations such as word clouds and distributions.
5. **Feature Engineering and Model Training**: Transforming text into features and training a machine learning model.

## Usage
1. Upload the notebook `detecting-disaster-tweets.ipynb` in a google colab environment. Upload your kaggle.json
2. Modify the `run_get_data` flag to `True` to download the dataset from Kaggle if not already done.
3. Execute the cells sequentially to load, clean, and analyze the data.
