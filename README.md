# TF-IDF-and-NLP-to-create-a-WordCloud
In this project, I will fit a Term Frequency-Inverse Document Frequency (TF-IDF) model on a text dataset and use TF-IDF weights to create a WordCloud that represent word importance. 

# Understanding the Project:

The Dataset used is an open source dataset that consists of Christmas recipes.

A Word Cloud is an image that represents the most important words in a document. The word importance in this project is determed by Term Frequency- Inverse Document Frequency (TF-IDF).  

Term Frequency Document Inverse Frequency (TF-IDF) is 

#Steps taken in this Project: 

1) Importing all of the necessary libraries to complete the task
2) Loading the JSON dataset containing recipes into the Python notebook
4) Writing clear and concise code to clean the dataset by creating a pipeline and: 
   a. removing conventional English stopwords, as well as my own addition of stopwords
   b. removing non alphabetical characters 
   c. creating a function to remove encodings
   d. performing tokenization
4) Lemmatizing the text data 
5) Implementing a TF-IDF Vectorizer to fit and transform the data  
6) Obtaining TF-IDF weights for word pairings and feeding those weights into a word cloud generator which will create an image, that better visualizes word importance. 
