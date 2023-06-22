# Social Media Sentiment Analysis

This project focuses on performing sentiment analysis on social media data extracted from Twitter, Amazon Reviews, and YouTube. The goal is to analyze the sentiment of the users' opinions and comments on these platforms.

## Data Source & Data Extraction

Data is extracted from the following social media sites through methods such as scraping or connecting to their APIs:

- Twitter
- Amazon Reviews
- YouTube

Twitter is used for fast streaming data and its popularity and openness of ideas, while Amazon Reviews provide a labeled dataset for sentiment analysis. YouTube is leveraged for a more focused dataset.

### Twitter Data Extraction

To extract related data from Twitter, the following procedures were performed:

1. Create a Twitter Developer Account and obtain Consumer Keys & Authentication Tokens.
2. Code data extraction solutions using Python's Tweepy library.
3. Data wrangling on the extracted data to transform it into a readable format.

## Data Cleaning/Preprocessing

Text preprocessing is performed using various Python packages. The following approaches are applied:

- Word Correction:
  - Lowercasing
  - Spelling correction
  - Conversion of emojis and emoticons into words

- Word Reduction:
  - Removal of punctuations
  - Stop-word removal (commonly used words in a language)
  - Removal of URLs
  - Lemmatization (converting words to their base form)

## Solution Details

### Analysis

The analysis includes sentiment analysis using the following approaches:

1. Simple Sentiment Analysis:
   - Based on positive/negative and subjective/objective words.
   - Pre-trained machine learning algorithms are used on both the Amazon and Twitter datasets.
   - Sentiment generated on the Amazon dataset is cross-referenced with the original rating to evaluate the algorithm's performance.

2. Naïve Bayes Modelling:
   - Trained on labeled data (Amazon Reviews) to classify Twitter data into positive and negative sentiment.

The motivation for using two approaches is to compare the results and select the most suitable one.

## Dataset

The dataset used for this project can be downloaded from the following source:
[Amazon Reviews - Unlocked Mobile Phones](https://www.kaggle.com/datasets/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones)

## Project Repository

The project is available on GitHub under the project name [Social Media Sentiment Analysis]([https://github.com/your-username/social-media-sentiment-analysis](https://github.com/Pranay62/SentimentalAnalysis_Project/)).

Please refer to the project repository for the code implementation and additional details.

