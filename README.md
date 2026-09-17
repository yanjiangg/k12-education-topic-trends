# K–12 Education Topic Trends

This repository contains code accompanying the manuscript:

**Tracing Shifts in K–12 Education Research: A Topic Modeling Analysis of Journal Abstracts from 1990 to 2023**

The study uses BERTopic to examine topical trends in abstracts from 22,921 articles published in 27 U.S.-based education journals between 1990 and 2023.

## Repository contents

- `bertopic_k12_education_trends_codes.ipynb`: Code for training the BERTopic model, reducing outliers, and plotting topic trends.
- `requirements.txt`: Python packages used for the analysis.

## Data availability

The full article abstracts are not included in this repository because of potential copyright and redistribution concerns. The code is provided to document the analytic workflow and modeling decisions used in the manuscript.

## Note

This notebook is designed for use in Google Colab. Using a GPU runtime can make the embedding and topic modeling steps faster.

Because the Colab environment and package versions change over time, successful application of the code may depend on the versions of Python, BERTopic, UMAP, HDBSCAN, sentence-transformers, and related dependencies available at the time of use.
