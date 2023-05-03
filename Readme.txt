Here is short brief:

Solution details:
Data Source & Data Extraction
Data will be extracted from the following Social Media sites through methods such as scraping or connecting to their APIs: 
  ▪ Twitter 
  ▪ Amazon Reviews
  ▪ YouTube
We will leverage on twitters fast streaming data  as well as its popularity and openness of ideas Amazon and Youtube will be leverage for a 
more focused Dataset, with Amazon reviews as a labelled dataset.


Twitter Data Extraction
To massively extract related data from twitter, we  have performed the following procedures:
1. Create Twitter Developer Account and Obtain Consumer Keys & Authentication Tokens.
2. Code Data Extraction Solutions by Python Tweepy Library.
3. Data Wrangling on Extracted data, transform it into readable format.

Data Cleaning/ Preprocessing
Text preprocessing will be performed using various python packages. Approaches includes the following:
Word Correction: 
    ▪ Lower casing 
    ▪ Spelling correction 
    ▪ Convert emojis and emoticons into words
Word Reduction: 
    ▪ Removal of punctuations 
    ▪ Stop-word removal – stop-words are a set of commonly used words in a language (e.g. “a”, “we”, “the”, “is” etc.)
    ▪ Removal of URLs 
    ▪ Lemmatization – process of converting a words to its base form (e.g. “studies” -> “study”)
    
Solution details
Analysis: 
    ▪ Sentiment Analysis 
    ▪ Sentiment analysis will be performed,using python packages, on processed data using two approaches:
            1. Simple sentiment analysis on twitter data based on positive/negative, subjective/objective words. 
               Pre-Trained Machine Learning Algorithm will be used over both Amazon and twitter dataset. For Amazon 
               dataset, generated sentiment will be cross-referenced with original rating to analyze the performance of the algorithm.
            2. Naïve Bayes modelling trained on labelled data(Amazon reviews) to classify twitter data into positive and negative sentiment
    ▪ Motivation for using two approaches is to compare the results between both approaches and select one that is most suitable.
