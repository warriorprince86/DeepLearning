# Assignment 3
The purpose of this assignment is to understand the importance of contextualized word embeddings with Deep Learning based model such as BERT and its impact on NLP tasks such as information retrievals.

Search is a standard tool for finding content. Calculation of similarity between textual information is an important factor for better search results.

In this assignment you are going to use the sample text provided (Document repository sample_repository.json(https://q.utoronto.ca/courses/243234/files/17079583?wrap=1 Download sample_repository.json) to calculate the similarity of text between queries and sample documents.

This assignment’s objective is to includes calculating similarity measure between queries and sample documents using 3 NLP techniques and comparing the results. 

NLP approaches to calculate similarity measures include:

1. Term Frequency-inverse document frequency (TF-idf)– This is a traditional NLP technique to look at words that appear in both pieces of text, and scores them based on how often they appear. For this part you can use TF-idf implementation in scikit- learn.
2. Semantic similarity using GloVe. For semantic similarity, you can use functions from gensim library and pre-trained word vectors from the GloVe algorithm.  
3. Semantic similarity using a BERT model.

NOTE: you don't have to use the suggested libraries or any specific type of function. So just please do the task and provide an interpretation of the findings. 

At minimum, you need to use the 3 queries below (You can have more queries as you wish) and calculate and compare the similarity scores of the given 3 queries with the sample documents.


Queries:
“fruits”
“vegetables”
“healthy foods in Canada”