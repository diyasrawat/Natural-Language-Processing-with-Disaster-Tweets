# Natural-Language-Processing-with-Disaster-Tweets
## Objective
Predict which Tweets are about real disasters and which ones are not
This repository contains the code and resources for analyzing disaster-related tweets using natural language processing (NLP) techniques. The goal is to classify tweets as related to disasters or not.

## Table of Contents

- [Dataset](#dataset)
- [Methodology](#methodology)
- [Data Preprocessing Techniques](#data-preprocessing-techniques)
- [Results](#results)
- [Conclusion](#conclusion)

## Dataset

The dataset used in this project is sourced from Kaggle's "Real or Not? NLP with Disaster Tweets" competition. It includes the following files:

- `train.csv`: Contains the training data with tweet text and corresponding labels (1 for disaster-related and 0 for not).
- `test.csv`: Contains the test data with tweet text but without labels.
- `sample_submission.csv`: A sample submission file in the correct format.

The training dataset comprises 7,613 tweets, each labeled as either a disaster tweet or not.

## Methodology

The methodology of this project involves the following steps:

1. **Exploratory Data Analysis (EDA)**: Understanding the dataset by examining the distribution of classes, the length of tweets, and other relevant features.
2. **Data Preprocessing**: Cleaning the text data to make it suitable for NLP tasks.
3. **Feature Engineering**: Creating features that can improve the text analysis.

## Data Preprocessing Techniques

To prepare the tweets for analysis, several preprocessing steps were applied:

1. **Removing URLs**: Stripping out URLs from the tweet text.
2. **Removing HTML Tags**: Cleaning HTML tags from the text.
3. **Removing Punctuation**: Stripping out punctuation marks to focus on the words.
4. **Tokenization**: Splitting the text into individual words or tokens.
5. **Stop Words Removal**: Removing common words that do not contribute much to the meaning (e.g., "and", "the").
6. **Stemming**: Reducing words to their base or root form using the Porter Stemmer.
7. **Vectorization**: Converting text into numerical representations using TF-IDF.

## Results

After preprocessing the data, several insights were derived from the exploratory data analysis, such as the distribution of tweet lengths, common words in disaster vs. non-disaster tweets, and more.

## Conclusion

This project successfully demonstrated the application of various NLP preprocessing techniques to prepare disaster-related tweets for further analysis. The steps outlined provide a foundation for future model training and prediction tasks.

Future improvements could involve fine-tuning the preprocessing steps, experimenting with advanced NLP techniques like transformer-based models, and incorporating more external data to enhance performance.
