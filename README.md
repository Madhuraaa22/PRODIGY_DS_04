## PRODIGY_DS_04
# 📌 Task Overview
This repository contains Task-04 of my Data Science internship with Prodigy InfoTech.
The objective of this task is to analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.
I have used the Twitter Sentiment dataset provided in the task.

The main objectives are:

Perform data cleaning and preprocessing on raw text.

Apply sentiment analysis techniques to classify text as Positive, Negative, or Neutral.

Visualize sentiment distribution and key trends.

# 📊 Dataset
File name: twitter_sentiments.csv

Source: Prodigy InfoTech - Task 4 Dataset

Description: Contains tweets along with sentiment labels.

# 🛠️ Tools & Libraries Used
Google Colab / Jupyter Notebook

Python 3.x

# Libraries:

pandas – Data handling and cleaning

numpy – Numerical operations

matplotlib – Data visualization

seaborn – Statistical plots

nltk – Natural Language Processing (tokenization, stopwords, lemmatization)

wordcloud – Visualizing most frequent words

scikit-learn – Model building (if classification applied)

# 🧹 Data Preprocessing Steps
Text Cleaning

Removed punctuation, special characters, numbers, and extra spaces.

Converted all text to lowercase.

Tokenization

Split tweets into individual words.

Stopword Removal

Removed common words (like "is", "the", "and") using NLTK.

Lemmatization

Reduced words to their base forms.

Label Encoding

Converted sentiment labels (Positive, Negative, Neutral) into numeric codes for analysis.

# 📊 Exploratory Data Analysis (EDA)
Sentiment Distribution → Count plot of Positive, Negative, Neutral tweets.

Word Frequency Analysis → Most common words for each sentiment category.

Word Clouds → Visual representation of frequent words in each sentiment group.

Hashtag Analysis → Most used hashtags per sentiment.

# 📈 Key Insights
Majority of tweets in the dataset were Positive.

Negative tweets often contained words related to complaints, dissatisfaction, or urgent concerns.

Positive tweets highlighted satisfaction, recommendations, and appreciation.

Hashtags showed clear topic trends in user opinions.


