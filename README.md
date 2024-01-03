# Similar_Plot_Summaries

## Project Overview

In this project, our goal was to analyze similarities among movies based on their plot summaries and perform hierarchical clustering to uncover patterns and relationships within the movie dataset. The project involved natural language processing (NLP) techniques, tokenization, stemming, and the application of the TF-IDF vectorization method.

## Data Preprocessing

- ### Data Loading:
Loaded movie data containing plot summaries from multiple sources, such as Wikipedia and IMDb.
- ### Text Preprocessing:
Combined plot summaries from different sources into a single column ('plot') in the dataset.

Tokenized and stemmed the text to extract meaningful features from the plot summaries.

Utilized TF-IDF vectorization to represent each movie's plot as a numerical feature vector.

## Similarity Analysis

- ### Cosine Similarity:
Calculated the cosine similarity between each pair of movies based on their TF-IDF representations.

Produced a similarity matrix that quantifies the similarity between movies.
- ### Hierarchical Clustering:
Applied hierarchical clustering using the complete-linkage method on the similarity matrix.

Generated a dendrogram to visualize the hierarchical structure of movie clusters.

## Visualization and Interpretation

- ### Dendrogram Plotting:
Plotted a dendrogram to represent the hierarchical clustering of movies.

Adjusted the plot to enhance readability, including setting leaf label colors.
- ### Cluster Analysis:
Identified clusters of movies based on the dendrogram structure.

Explored relationships between movies within and across clusters.
