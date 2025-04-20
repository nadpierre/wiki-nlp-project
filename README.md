# Wikipedia Pages NLP Project

## Description

The goal of this project is to uncover underlying clusters from a sample of Wikipedia pages, using unsupervized learning.

## Dataset

The dataset contains 8595 pages from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page). Each text contains at least 300 characters.

## Libraries Used

- gensim
- kneed
- matplotlib
- numpy
- pandas
- requests
- scipy
- seaborn
- sentence_transformers
- sklearn

## Methods & Models

1. **Data Collection**

   The pages title and content were fetched at random from the Wikipedia API named [MediaWiki](https://www.mediawiki.org/wiki/API:Main_page).

2. **Data Preprocessing**

   Two feature extraction methods were explored:

   - Global Vectors for Word Representaion (GloVe)
   - Sentence Transformers

   The one that performed the best was used for the clustering.
   The sentence transformer used in this project is named [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)

3. **Unsupervised Learning**

- Two clustering methods were used: **K-Means** and **Hierarchical Clustering**.
- For K-Means, different cluster numbers were evaluated using the elbow method and the silhouette score.
- A Dendogram was plotted to determine the optimal number of clusters for Hierarchical Clustering.

4. **Interpretation**
   Each cluster was analyzed to uncover the trends and the similarities and differences of the two clustering methods were analyzed.

5. **Cluster Visualization**

   The t-distributed Stochastic Neighbor Embedding (t-SNE) was used to reduce the dimensionality of the data in order to display the clusters in two dimensions.

## Featured Notebooks

[NLP Project](./nlp_project.ipynb)
