# Information_Retrieval_System

This project focuses on building an Information Retrieval System using pre-trained language models. It involves working with a set of provided documents and aims to arrange these documents in descending order of relevance for a given query, employing the following key methods:
All the Codes are available in the [Notebook](https://github.com/Amin-Saeidi/Information_Retrieval_System/blob/main/Information_Retrieval_System.ipynb).

## IDF-TF Similarity
Utilizing term frequency-inverse document frequency (IDF-TF) weights to compute document similarity.

## Persian BART Embedding
Employing the Persian BART model to embed both questions and documents, subsequently assessing similarity using an appropriate distance metric.

## Semantic Space Exploration
Analyzing the advantages and disadvantages of representing words and phrases in a semantic space using language models, in contrast to traditional IDF-TF. Additionally, devising strategies for combining these two approaches in data retrieval and implementing them.

## Machine Learning Classifier
Creating a dataset that includes pairs of related query-document and unrelated query-document samples. Training a classifier on the CLS token to determine positive and negative samples and discussing the data compilation strategy.
