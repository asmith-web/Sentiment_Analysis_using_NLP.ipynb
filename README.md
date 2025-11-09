This project performs basic sentiment analysis on user-provided text using the TextBlob library in Python. Here's a breakdown:

Installation: It installs the nltk and textblob libraries, which are necessary for the sentiment analysis.
Input: It prompts the user to enter text (a review or comment).
Sentiment Analysis: It uses TextBlob to calculate a sentiment polarity score for the input text. This score ranges from -1 (very negative) to +1 (very positive).
Sentiment Labeling: Based on the sentiment score, it assigns a sentiment label: "Positive", "Negative", or "Neutral".
Output: It prints the original text, the calculated sentiment score, and the assigned sentiment label.


This project demonstrates some fundamental Natural Language Processing (NLP) techniques using Python libraries like NLTK and TextBlob.

The code you see performs the following steps:

Installs and Imports Libraries: It installs nltk and textblob, which are essential for NLP tasks, and then imports them. It also downloads necessary data like stopwords and tokenizers from NLTK.
Tokenization and Stopword Removal: This step takes a sample sentence, breaks it down into individual words (tokenization), and then removes common words (stopwords) that don't carry much meaning, leaving the more significant words.
