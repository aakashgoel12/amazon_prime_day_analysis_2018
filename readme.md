Amazon Prime Day Analysis - 2018
--------------------------------

Objective:
---------

To understand sentiment of buyers from amazon prime day and what they talk about (word of mouth)?

Data Source: 
-----------

Twitter (Extracted around 6300 tweets using hashtag "#primeday" and date : 14-July-18 to 19-July-18 )

Preprocessing Steps:
--------------------

a) Removing URL,number
b) case conversion - lowering of tweets 
c) Removing NLTK Stopwords 
For Topic Modelling 
d) Removing common stopwords manually 
e) Keeping only Alphabetic character including (a-z and space) 
f) Lemmatization

Sentiment Analysis:
--------------------

Used VADER to get positive, negative and neutral score. VADER is lexicon and rule based.

Topic Modelling:
-----------------

Used LDA Model from gensim.
