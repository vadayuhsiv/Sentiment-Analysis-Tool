# Sentiment-Analysis-Tool

Sentiment analysis is a techniqe that tries to understand the context of a sentence/statement.

We can classify the data based on the key features and the reactions of the customer.

Using RNN the ability to analyze text has improved a lot recently.

Backend of the project:

LSTM based model

Frontend:

Flask Application

We will use Imdb dataset

Basics of NLP

Tokenization: process of segmenting text into words/sentences.

In some cases using spaces to tokenize isn’t correct because a word like San Fransisco would not make sense when evaluated separately, so we can use pre made libraries and build over them to handle such issues.


Remove punctuation's after tokenizing.

Stop Words: Words that are not of much use and can be discarded.

one of the ways is by doing a lookup on a list and removing the unecesary words.

Stemming : 

Text normalization technique, to change words to root words.

Remove prefixes and affixes of a word.

Helps in improving speed.

Lemmatization :

Is a more advanced form of stemming as it tries to understand the context and it requires a part of speech. It uses a different approach than stemming. It requires more computation but provides better results.

Word Embedding: 

A method to represent words into numeric forms.

The final project was deployed using a flask web app

