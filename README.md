# Wikipedia Pages NLP Project

## Description

The goal of this project is to uncover underlying clusters from a sample of Wikipedia pages, using unsupervized learning.

## Dataset

The data comes from the Wikipedia API named [MediaWiki](https://www.mediawiki.org/wiki/API:Main_page). The dataset contains 8595 titles and contents extracted from random page. Each text contains at least 300 characters.

## Libraries Used

- gensim
- kneed
- matplotlib
- numpy
- pandas
- requests
- sklearn
- spacy
- pytorch
- transformers

## Methods & Models

https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2
https://huggingface.co/nomic-ai/nomic-embed-text-v1

## Results

## Featured Notebooks

Preprocessing:

Clean the text data by removing irrelevant sections, stop words, and performing tokenization.

Optionally, apply lemmatization or stemming.​

Feature Extraction:

Convert the text into numerical representations using techniques like TF-IDF or word embeddings (e.g., Word2Vec, GloVe).​

Unsupervised Learning:

Apply clustering algorithms (e.g., K-Means, DBSCAN) to uncover underlying patterns or groupings.

Alternatively, use topic modeling methods like Latent Dirichlet Allocation (LDA) to identify prevalent themes.​

Evaluation and Interpretation:

Analyze the resulting clusters or topics to interpret their meanings and relevance.

Visualize the findings using dimensionality reduction techniques (e.g., t-SNE, PCA) for better understanding.
